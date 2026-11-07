Full logo: 
<img width="2048" height="768" alt="Nova OS Futuristic Blue Logo" src="https://github.com/user-attachments/assets/0bd70e3a-745b-4bca-ad0b-4a071ff3e35d" />

Single Letter logo: 
<img width="1254" height="1254" alt="Cosmic N Emblem with Orbital Star" src="https://github.com/user-attachments/assets/f890685e-840d-4da1-a78a-f8a4f663de25" />

Nova OS (As of November 7, 2026) is an AI made project. This tests if AI could really take over the OS side of computers. Here are the versions so far:
Nova OS 1 Beta 1 Build 1267

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][1267]}

It has:
32 Bit, Runs on a iso, Bios only.

What did it add?
Build 1267 added/changed:

Initial 32-bit Core Bootloader & Kernel Architecture
BIOS El Torito ISO Boot Support
Basic VGA Text Mode Console Display (80x25 characters)
Protected Mode Initialization (GDT Setup & A20 Gate)
Low-Level Hardware Interrupt Handling (PIC 8259 Remapping)
Initial Prototype Memory Layout
Basic TTY Character & String Output Routines
Foundational Proof of Concept for AI-Constructed OS Environments
Nova OS 1 Beta 2 Build 9739

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][9739]}

It has:
64 Bit, Runs on a iso, Bios only.

What did it add?
Build 9739 added/changed:

64-Bit Long Mode Transition
High-Resolution VBE Framebuffer
NovaFS Resource Filesystem
Typography & Font Engine (.FNT)
Graphical Boot Screen & Animated Spinner
PC Speaker Audio Synthesizer
Expanded 64-Bit Interactive Shell
Added built-in commands
GDT Bootstrap & Memory Alignment Fixes
Nova OS 1 Beta 3 Build 1254

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][1254]}

It has:
16 Bit, Runs on a iso, Bios only.

What did it add?
Build 1254 added/changed:

Earliest Documented BIOS Boot Foundation (MBR Architecture)
Real Mode 16-Bit Register & Segment Reset (DS=ES=SS=0x0000, SP=0x7C00)
Single-Sector Master Boot Record (512-Byte Footprint)
BIOS Teletype Output Routine (INT 10h, AH=0Eh)
BIOS Drive Parameter & DL Boot Register Detection
System Identification Banner & Safe CPU Halt Sequence
Floppy Disk Emulation El Torito ISO Architecture
Nova OS 1 Beta 4 Build 9457

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][9457]}

It has:
32 Bit, Runs on a iso, Bios only.

What did it add?
Build 9457 added/changed:

Multi-Stage Bootloader Architecture (MBR Stage 1 + Stage 2 Loader)
Extended BIOS Disk Read Support (INT 13h Extensions, AH=42h DAP)
Fast A20 Gate Activation via System Control Port 0x92
Global Descriptor Table (GDT) Flat 4GB Memory Model Setup
Transition from 16-Bit Real Mode to 32-Bit Protected Mode (CR0.PE = 1)
VGA Text Buffer Driver (0xB8000) with Custom Color Attributes
Direct Kernel Loading to Address 0x10000
Nova OS 1 Beta 5 Build 1342

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][1342]}

It has:
32 Bit, Runs on a iso, Bios only.

What did it add?
Build 1342 added/changed:

NovaFS Custom Operating System Filesystem Implementation
NovaFS Superblock Specification & Magic Verification (NOVAFS)
32-Byte Structured Directory Entries (Filename, Sector Offset, Byte Size)
Multi-Sector Filesystem Loading Routine from Disk (LBA 69 Chunking)
Memory-Mapped Filesystem Parser & Boot Directory Enumeration
File Indexing & Sector Allocation Table Foundation
Automated Boot-Time File Listing on VGA Text Console
Nova OS 1 Beta 6 Build 9653

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][9653]}

It has:
32 Bit, Runs on a iso, Bios only.

What did it add?
Build 9653 added/changed:

VESA BIOS Extensions (VBE 2.0/3.0) High-Resolution Graphics Subsystem
VBE Mode 0x0144 / 0x4144 Linear Framebuffer Initialization (1024×768×32bpp)
32-Bit Video Parameter Handoff Protocol (0x9000 Structure)
El Torito Hard Disk Emulation (hdemul) Geometry & Active Partition MBR
Primitive Graphical Engine: draw_rect with Scanline Pitch Stride
NovaOS Midnight Blue Desktop Theme Rendering (0x000F172A)
Graphical Window & Titlebar Desktop Foundations
Nova OS 1 Beta 7 Build 1842

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][1842]}

It has:
32 Bit, Runs on a iso, Bios only.

What did it add?
Build 1842 added/changed:

Custom NFNT Binary Typography Architecture (NFNT File Format)
NovaFS Font Asset Loading (SEGOEUI.FNT, Segoe UI 12×20 Proportional Font)
1-Bit-per-Pixel Glyph Unpacker & Linear Framebuffer Character Rasterizer
High-Resolution Look with True Color Font Foreground (#F8FAFC)
Graphical Screen Text Driver: Dynamic Character Columns & Row Positioning
Multi-Line String Printing Routine with Automatic Row Wrapping
Elimination of VGA Legacy 80×25 Text Buffer in Favor of Pure Framebuffer Text
Nova OS 1 Beta 8 Build 9274

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][9274]}

It has:
32 Bit, Runs on a iso, Bios only.

What did it add?
Build 9274 added/changed:

Interactive PS/2 Keyboard Controller Driver (Ports 0x64 Status / 0x60 Data)
Scan Code Translation Table (US QWERTY Layout)
Real-Time Command-Line Buffer with Backspace, Space, and Enter Processing
Full-Featured Interactive Command Shell (nova-b8>)
Built-in Shell Command Interpreter:
help (List commands)
info (System architecture and memory layout)
ver (NovaOS version string and build number)
clear (Framebuffer screen clear)
ls (NovaFS directory listing)
reboot (Hardware reset via PS/2 0xFE pulse)
Nova OS 1 Beta 9 Build 1568

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][1568]}

It has:
64 Bit, Runs on a iso, Bios only.

What did it add?
Build 1568 added/changed:

Transition from 32-Bit Protected Mode to 64-Bit Long Mode (x86-64)
PML4 4-Level Paging Hierarchy (PML4, PDPT, PD0–PD3)
Identity-Mapping of First 4GB of Physical RAM via 2MB Huge Pages (0x83)
Physical Address Extension (CR4.PAE = 1) & Long Mode Enable (EFER.LME = 1)
Dual-Mode Global Descriptor Table (32-Bit Descriptor + 64-Bit L=1, D=0 Segment)
Prevention of Long-Mode Bootstrap #GP Triple-Fault Loops
64-Bit General-Purpose Register Utilization (RAX, RBX, RCX, RDX, RSI, RDI, RSP)
64-Bit Re-implementation of Framebuffer Driver, Font Engine, and Interactive Shell
Nova OS 1 Beta 10 Build 9831

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][9831]}

It has:
64 Bit, Runs on a iso, Bios only.

What did it add?
Build 9831 added/changed:

Official NovaOS Branding Visual Identity Integration
32-Bit RGBA High-Resolution Logo Driver (NOVALOGO.RAW, 220×220 True Color)
Centered Boot Logo Placement at Screen Coordinates (402, 110)
122-Frame Circular Animated Boot Spinner Subsystem (BOOTSPIN.FNT)
Multi-Cycle Boot Presentation Sequence before Shell Activation
Alpha Channel Transparency Blending for Screen Overlays
Dual Resource Discovery in NovaFS (Simultaneous Font, Logo, and Animation Loading)
Nova OS 1 Beta 11 Build 1746

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][1746]}

It has:
64 Bit, Runs on a iso, Bios only.

What did it add?
Build 1746 added/changed:

Dynamic Multi-Font Typography Discovery in NovaFS
Bundled Multiple Typeface Styles:
SEGOEUI.FNT (Segoe UI Regular, 12×20)
SEGOEBD.FNT (Segoe UI Bold, 12×20)
SEGOEIT.FNT (Segoe UI Italic, 12×20)
Runtime Font Switching Shell Commands:
font list (Enumerate available typography assets in NovaFS)
font current (Display active typography engine & dimensions)
font use <1-3> (Dynamically switch active font pointer on the fly)
Spinner Bounding-Box Boundary Clearing to Eliminate Visual Ghosting
Calibrated Animation Frame Pacing
Nova OS 1 Beta 12 Build 9612

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][9612]}

It has:
64 Bit, Runs on a iso, Bios only.

What did it add?
Build 9612 added/changed:

Initramfs / RAM-Based Live Storage Installer Engine
Interactive Shell Installer Command (install)
Storage Device Discovery & Target Disk Enumeration
Safety Confirmation Prompt (Proceed with installation? yes/no)
Multi-Step Animated Progress Bar:
Target disk partitioning (MBR Partition Table)
NovaFS filesystem image deployment
x86-64 kernel and bootloader placement
Standalone Python ISO Build & Validation Tool (tools/validate_iso.py)
ISO9660 PVD and El Torito Boot Descriptor Verification
Nova OS 1 Beta 13 Build 1385

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][1385]}

It has:
64 Bit, Runs on a iso, Bios & UEFI Ready.

What did it add?
Build 1385 added/changed:

UEFI Graphics Output Protocol (GOP) Architectural Support
Unified GOP Handoff Structure Definition (include/uefi_gop.inc)
Stage 2 Resolution Selection Menu with 15-Second Selection Timeout
Safe Default Resolution Fallback to 640×480×32
Multi-Resolution Support:
640×480×32 (Safe Default)
800×600×32
1024×768×32 (Standard)
1280×1024×32
Runtime GUI & Terminal Adaptive Sizing (Dynamic Rows, Cols, and Centering)
New Shell Command res to Inspect Active Framebuffer Geometry
Nova OS 1 Beta 14 Build 9749

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][9749]}

It has:
64 Bit, Runs on a iso, Bios & UEFI Ready.

What did it add?
Build 9749 added/changed:

Cumulative Master Release Incorporating all Documented Enhancements
Clean 6-Page Page-Table Zeroing Hierarchy (PML4, PDPT, PD0–PD3)
Stage 2 15-Second Timed Resolution Menu Defaulting to 640×480
Programmable Interval Timer (PIT) ~25 FPS Spinner Pacing (~40ms / Frame)
122-Frame Circular Spinner Animation Cycle
Instant Keyboard-Based Spinner Skip (Press any key to bypass boot animation directly into shell)
Pitch-Corrected draw_rect Row Advancement Preventing Scanline Skewing
Dynamically Centered Branding Logo Across All Resolutions
Normalized YES Installer Confirmation (Accepts "yes", "YES", "Yes", "y", "Y")
Full Comprehensive Command Suite (help, res, font, install, info, ver, ls, clear, reboot, shutdown)
Verified Live Boot in VirtualBox with Screen Captures
Nova OS 1 Beta 15 Build 5648

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][5648]}

It has:
64 Bit, Runs on ISO & Installed Hard Disk, Native Dual BIOS + UEFI Boot.

What did it add?
Build 5648 added/changed:

Native UEFI Bootloader Engine (BOOTX64.EFI):
Fully compliant PE32+ application adhering to UEFI 2.x Specification.
Resolved blinking cursor / black screen hangs caused by missing PE32+ Optional Header entry point (corrected AddressOfEntryPoint RVA offset at 0x1000).
Implemented runtime RIP-relative GDT physical base calculation (lea rax, [rel gdt64]; mov [rel gdt64_base], rax) to eliminate high-memory page faults during long-mode reload after ExitBootServices.
Added automated fallback filesystem protocol discovery (BootServices->LocateProtocol for EFI_SIMPLE_FILE_SYSTEM_PROTOCOL) enabling resilient payload resolution directly from root or /EFI/NOVA.
Compliant FAT16 EFI System Partition (efiboot.img):
Full BPB specification with 0x80 drive signature, 5760 sectors (2880 KB), 2 FAT tables, and 512 root directory entries.
Complete /EFI/BOOT/BOOTX64.EFI and /EFI/NOVA/ directory hierarchies alongside root payload mirrors.
Dual BIOS + UEFI Hard Disk Partitioning (Hybrid MBR + ESP):
Unified disk layout allowing the exact same hard disk to boot seamlessly under both legacy BIOS and native UEFI firmware.
LBA 0..1023 holds the BIOS MBR, Stage 2 loader, 64-bit Kernel, and NovaFS.
Injected MBR Partition Entry 1 at offset 446 with Type 0xEF (EFI System Partition), Active Flag 0x80, starting LBA 2048, and 5760 sectors.
Windows XP-Style Hard Drive Setup Wizard:
Complete 5-step installer wizard (Hardware Detection, RAM Allocation, Disk Selection, Storage Profile, and Hardware RTC Clock Setup).
Fixed BusyBox ash ANSI console escaping corruption (//33...) by replacing echo -e with POSIX printf byte sequence expansion.
In-flight SHA-256 payload integrity verification adjusted to ignore LBA 0 partition table injection.
Enhanced File Explorer & Navigation:
Embedded on-screen navigational key guidance: [UP/DN] Move  [ENTER] Open  [ESC] Close  [PgUp/PgDn] Jump.
Non-destructive ESC window dismissal cleanly returning to the desktop environment.
Categorized Shell Help System:
Comprehensive reorganization of shell commands into distinct functional categories (SYSTEM, DISPLAY, FILE SYSTEM, GUI, DRIVES, FONT, MATH).
Interactive VirtualBox Live Verification:
Verified live booting directly from virtual hard drive under native UEFI firmware at 
1920
×
1200
1920×1200 resolution.
Verified version shell command reporting NovaOS v0.8.5648 (Build 5648) (x86_64).
Verified legacy BIOS boot splash, animated spinner, and desktop execution on the identical disk image.
NOTE

Evolution of Bitness & Architecture:

16-Bit Real Mode: Beta 3 (Build 1254) laid the bare-metal MBR roots.
32-Bit Protected Mode: Beta 1 (Build 1267) and Beta 4–8 (Builds 9457 to 9274) developed the early text console, VBE graphics, custom NFNT fonts, and PS/2 keyboard drivers.
64-Bit Long Mode: Beta 2 (Build 9739) and Beta 9–15 (Builds 1568 to 5648) completed the transition to x86-64 with PML4 4-level paging, identity mapping, high-resolution desktop rendering, AC97 audio, and live storage installation.

Boot Medium & Firmware Milestones:

Builds 1267 – 9612: Exclusively BIOS-based El Torito ISO media.
Builds 1385 – 9749: Introduced GOP specifications and dual BIOS/UEFI readiness.
Build 5648: First release delivering Native UEFI Hard Disk Booting from an installed disk image (BOOTX64.EFI on a Type 0xEF FAT16 ESP) alongside Hybrid MBR BIOS Booting, eliminating the dependency on legacy CSM firmware.

Versioning Formula Breakdown:

All documented releases strictly follow:
{[Name][Base ver][Beta/Update/None][Build number of that version]}
(e.g., Nova OS + 1 + Beta + 5648 = Nova OS 1 Beta 15 Build 5648, internally labeled v0.8.5648).

Nova OS 1 Beta 16 Build 5167

How the name came:
{[Name][Base ver][Beta/Update/None][Build number of that version]} -> {[Nova OS][1][Beta][5167]}

It has:
64 Bit, Runs on ISO & Installed Hard Disk, Native Dual BIOS + UEFI Boot.

What did it add?
Build 5167 added/changed:

- Nova OS Program (.nosp) Executable Architecture:
  - Proprietary 64-bit binary executable specification serving as the native replacement for legacy Windows .exe executables.
  - Verification of 4-byte header magic (0x50534F4E / NOSP).
- Live ISO Startup Installer (startup.nosp):
  - Bundled directly on the live optical media (Drive D:\startup.nosp).
  - Native shell direct execution support (startup.nosp and d:\startup.nosp).
- Storage Drive Explorer Subsystem (list drive):
  - Interactive shell command list drive / list drives enumerating detected media:
    - [A] Floppy Disk (1.44MB)
    - [C] Hard Disk NovaFS
    - [D] ATAPI CD-ROM / ISO (Live Media)
  - Interactive file selection on Drive D: displaying file types (<APP>, <FILE>, <CFG>, <DIR>).
- Contextual Action Menu:
  - Selecting any file opens the action prompt:
    - [1] Open / Run
    - [2] Edit (Header inspection)
    - [3] Cancel
- Safe Installer Flow with User File Preservation:
  - Opening startup.nosp presents the official warning prompt:
    ==================================================
               Welcome to NovaOS Installer
    ==================================================

    Press [ENTER] to continue, or [C] to cancel.

    (WARNING: This will erase your current OS,
     but the files you made will be saved!)
    ==================================================
  - Pressing [C] or [ESC] cancels and cleanly returns to the NovaOS shell.
  - Pressing [ENTER] executes the 4-phase deployment sequence:
    - [1/4] Preserving user files and documents... OK.
    - [2/4] Formatting target partition (NovaFS)... OK.
    - [3/4] Deploying NovaOS v0.9.5167 64-bit kernel & UEFI... OK.
    - [4/4] Restoring user files to Hard Disk C:... OK.
    - Displays [SUCCESS] NovaOS v0.9.5167 successfully installed! and returns cleanly to desktop.
- File Explorer GUI Integration:
  - Added startup.nosp as an executable entry in the graphical File Explorer (files command).
- Low-Level Disk & Firmware Safety Fixes:
  - Fixed MBR sector 0 byte size discrepancy in build_target_disk.py (removing 2-byte alignment offset to restore clean BIOS boot on installed disks).
  - Added balanced stack cleanup and floating bus (0xFF) abort logic in ata_write_sectors to prevent CPU faults across hardware and VM setups.
