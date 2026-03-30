# InspireX OS

**InspireX** is a modernized, DOS-based operating system designed to run on everything from legacy PCs to modern multi-core 64-bit rigs. It combines retro DOS compatibility with modern features like multi-core support, mouse input, and preinstalled browsers.

---

## Features

- **Base System:** FreeDOS  
- **Memory Support:** Marketed to use up to **128 TB RAM** (can theoretically address up to 256 TB on 64-bit hardware)  
- **CPU Support:**  
  - x16 (16-bit real DOS)  
  - x64 (DOS64SMP, 64-bit long mode, SMP)  
- **Multi-core & SMP:** Supported via DOS64SMP  
- **Mouse Support:** CuteMouse (`HIMALAYA.SYS`)  
- **Preinstalled Applications:**  
  - K-Meleon browser  
  - Pale Moon browser  
- **Boot Media:** Hard Drive or DVD images  
- **Lightweight Compatibility:** Runs `.COM` and `.EXE` programs, works on low-RAM / low-core systems  
- **Hardware Agnostic:** Even extremely slow CPUs or very low-RAM machines can boot via USB/DVD using Rufus  
- **Open Source:** MIT License

---

## Installation

1. Download the **InspireX `.img` or `.iso`** image.  
2. Use **Rufus** or any USB/DVD writer to create a bootable drive.  
3. Boot your PC from the drive.  
4. Enjoy InspireX with mouse support, preinstalled browsers, and DOS compatibility.

---

## Usage Notes

- **Drivers:** Configurable via `CONFIG.SYS` and `AUTOEXEC.BAT`  
- **Programs:** Small utilities should be `.COM` files; larger programs use `.EXE`  
- **Memory Management:** DOS64SMP allows large memory usage and multi-core features  
- **Sharing:** MIT License allows free copying, modification, and redistribution

---

## License

This project is licensed under the MIT License:




















## Requirements
Single core or more
Single thread or more
640KB ram or more
128TB ram MAX
can even run on the oldest PCs with the lightweight version.
