Full logo:<img width="2048" height="768" alt="Nova OS Futuristic Blue Logo" src="https://github.com/user-attachments/assets/6e7c8b89-c8b7-43b6-b1ad-613e8bb20ab6" /> 
Single Letter logo:<img width="1254" height="1254" alt="Cosmic N Emblem with Orbital Star" src="https://github.com/user-attachments/assets/ba860b94-e7c4-4455-b44d-5adddab351e2" />


Nova OS (As of November 3, 2026) is an AI made project. This tests if Ai could really take over the OS side of computers.
Here is the versions so far:

**Nova OS 1 Beta 1 Build 1267**

How the name came:

{[Name][Base ver][Beta/Update/None][Build number of **that** version]}

it has:

32 Bit, Runs on a iso, Bios only.
<img width="716" height="391" alt="Screenshot 2026-11-03 162500" src="https://github.com/user-attachments/assets/3fd872ae-1f4b-4223-98ee-bfb6d49a8b86" />

**Nova OS 1 Beta 2 Build 9739**

How the name came:

{[Name][Base ver][Beta/Update/None][Build number of **that** version]}

it has:

64 Bit, Runs on a iso, Bios only.

What did it add?

Build 9739 added/changed 

64-Bit Long Mode Transition:

Upgraded the system from the legacy 32-bit protected mode kernel to a 64-bit kernel (ORG 0x10000).
Configured PAE, long mode enablement via EFER.LME MSR (0xC0000080), and full identity mapping using PML4, PDPT, and PD0–PD3 page tables.

High-Resolution VBE Framebuffer:

Replaced the standard 80×25 VGA text mode console with high-resolution 1024×768×32 Linear Framebuffer rendering directly into video RAM at PhysBasePtr (0xE0000000).

NovaFS Resource Filesystem:

Introduced NovaFS at sector offset 133 (loaded to memory at 0x20000), allowing directory-based indexing, sector tracking, and loading of system fonts and graphic assets.

Typography & Font Engine (.FNT):

Added dynamic monochrome bitmap text rendering (12×20 pixel cell size) generated from TrueType sources.
Integrated system fonts: SEGOEUI.FNT, SEGOEBD.FNT, SEGOEIT.FNT, and SEGOEBI.FNT.
Added runtime font switching commands in the shell (font list, font current, font use <id>).

Graphical Boot Screen & Animated Spinner:

Embedded the official 220×220 RGBA branding logo (NOVALOGO.RAW).
Added a 122-frame animated circular boot spinner (BOOTSPIN.FNT) clocked by the Programmable Interval Timer (PIT Channel 0).

PC Speaker Audio Synthesizer:

Implemented PIT Channel 2 audio driver and startup chime playing an ascending chord sequence (C5, E5, G5, C6).

Expanded 64-Bit Interactive Shell:

Added built-in commands: help, about, version, clear / cls, echo, cpu (CPUID vendor string lookup), time & date (CMOS RTC clock queries), mem (kernel memory address inspection), add & sub (integer arithmetic), font, reboot, and halt.

GDT Bootstrap & Memory Alignment Fixes:

Separated the 32-bit protected mode code descriptor (0x00CF9A000000FFFF) from the 64-bit long-mode descriptor (0x00AF9A000000FFFF), resolving the #GP triple-fault reboot loop.
Memory-bounded NovaFS loading to 512 sectors (256 KB) to prevent DMA collision with video RAM/BIOS addresses.
