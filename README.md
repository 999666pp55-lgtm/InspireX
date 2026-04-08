# InspireX OS 1.0 — Multi‑Mode Edition
### README.md — 2026 Release

---

## 🏛️ History

InspireX has two major branches:

### **InspireX 1.0 DEV (Early Development Builds)**
- ✔ DOS‑compatible  
- ✔ Ran `.COM` and `.EXE` files  
- ✔ Used FreeDOS components  
- ✔ Booted in real mode  
- ✔ Functioned like a DOS‑enhanced experimental OS  

This was the phase where InspireX still behaved like a DOS‑based system.

---

### **InspireX 1.0 STABLE (Final Release)**
**This is the version documented here.**

- ❌ NOT DOS‑compatible  
- ❌ Does NOT run `.COM`  
- ❌ Does NOT run x16 `.EXE`  
- ❌ No DOS drivers  
- ❌ No DOS memory model  

InspireX STABLE evolved into a **fully modern, standalone operating system** with its own executable format, kernel extensions, and hardware‑adaptive architecture.

The DOS era is part of its history — but InspireX STABLE is built for **32 bit+ hardware**.

---

## 🚀 Overview

InspireX OS is a **hardware‑adaptive x86/x64 operating system** designed to scale from older pre‑2014 CPUs to modern GPUs capable of simulating TOPS‑class NPU workloads.

It features:

- A VRAM‑intensive GUI  
- Custom InspireX themes  
- Wine integration for Windows apps  
- A multi‑mode installer that selects the best mode for your hardware  

InspireX uses its **own binary format** and relies on Wine for Windows compatibility.

---

## 🧬 Supported Architectures

- **x86 (32‑bit)**  
- **x64 (64‑bit)**  

Both architectures support all three InspireX modes, depending on hardware capability.

---

## ✨ Core Features

- Three hardware‑aware operating modes  
- Automatic mode detection  
- Native InspireX binary format  
- Wine preinstalled  
- VRAM‑aware graphics subsystem  
- **256 MB VRAM minimum**  
- **1028 MB RAM minimum (≈1 GB)**  
- **Single‑core CPU minimum (OS boots)**  
- **Dual‑core CPU minimum for browsing and Wine**  
- Multi‑core and SMP support  
- Custom GUI themes  
- MIT‑licensed  

---

# ⚙️ Operating Modes

InspireX includes **three internal OS modes**, selected automatically during installation.

---

## 1. Modern Gaming PC Mode (2024+ / NPU‑Simulated GPU Mode)
### 🔥 Highest‑performance mode  
### 🧮 **NPU accelerates math, gaming, graphics, rendering, and rasterization — NOT AI**

### Requirements
- **Dual‑core CPU minimum**  
- CPU manufactured **2024 or newer**  
  **OR**
- GPU capable of **simulating TOPS‑class NPU operations**  
- **High‑end GPU required** (no exceptions)  
- **256 MB VRAM minimum** (512 MB+ recommended)

### Description
This mode activates the **InspireX Compute Engine**, which intercepts compute and graphics math calls and routes them to the GPU’s NPU‑simulation layer.

### ✔ The NPU accelerates:
- Math  
- Gaming  
- Graphics  
- Rendering frames  
- GPU rasterization  
- Shaders  
- Physics  
- Geometry  
- Lighting  
- Post‑processing  
- Compute workloads  

### ❌ The NPU does NOT accelerate:
- AI  
- Machine learning  
- Neural networks  
- Tensor operations  
- Deep learning  

The NPU is a **universal compute engine**, not an AI processor.

---

## 2. 2015+ Mode (Modern Native)
### ⚡ Optimized for modern CPUs

### Requirements
- **Dual‑core CPU minimum**  
- Intel/AMD CPU from **2015 or newer**  
- AVX2 / SSE4.2 instruction sets  
- No NPU‑capable GPU  
- 256 MB VRAM minimum  

### Description
Balanced performance and compatibility.  
Ideal for modern laptops and desktops without NPU‑class GPUs.

---

## 3. 2014‑ Mode (Legacy Compatible)
### 🧩 Maximum compatibility

### Requirements
- **Single‑core CPU supported**  
- Intel/AMD CPU from **2014 or earlier**  
- SSE2/SSE3 instruction sets  
- No NPU support  
- 256 MB VRAM minimum  

### Description
Designed for older ThinkPads, Core 2 Duo systems, and retro x86/x64 hardware.

**Note:**  
Single‑core CPUs can boot InspireX, but browsing and Wine require **dual‑core or better**.

---

# 🧠 Mode Selection Logic

The installer chooses the best mode automatically:

- **Only one mode supported → auto‑install**  
- **Two modes supported → user chooses**  
- **All three supported → full selection menu**  

This ensures InspireX always installs the optimal configuration.

---

# 🖥️ System Requirements

### Minimum (OS boots)
- **Single‑core CPU (x86 or x64)**  
- **1028 MB RAM (≈1 GB)**  
- **256 MB VRAM**  
- VGA‑compatible graphics  
- Bootable USB/DVD  

### Minimum for browsing + Wine
- **Dual‑core CPU**  

### Recommended
- Quad‑core x64 CPU  
- 2 GB RAM or more  
- 512 MB VRAM or more  
- SATA/IDE storage  

### Maximum Supported
- Up to **128 TB RAM** (practical)  
- Up to **256 TB addressable** (hardware‑dependent)  

---

# 📦 Executable Support

### ❌ InspireX STABLE does **NOT** run:
- `.COM`  
- `.EXE`  
- DOS binaries  
- Windows binaries natively  

### ✔ InspireX DEV **did** run:
- `.COM`  
- `.EXE`  
- DOS apps  
- FreeDOS tools  

### ✔ InspireX STABLE supports:
- Native InspireX binaries  
- Windows apps via **Wine**  
- Portable Windows apps (user‑mode only)  

### ⚠ Limitations
- Kernel‑mode Windows drivers cannot run  
- Enterprise antivirus “sensors” cannot install  
- Disk‑level Windows tools cannot access hardware  

---

# 📚 Included Software

- InspireX GUI  
- Wine (preinstalled)  
- InspireX input subsystem  
- K‑Meleon browser  
- Pale Moon browser  
- InspireX tools and scripts  
- Editors and file utilities  

---

# 🧭 Philosophy

InspireX is a **retro‑modern hybrid OS**:

- Started as DOS (DEV builds)  
- Evolved into a modern OS (STABLE)  
- Not DOS  
- Not Linux  
- Not Windows  
- A unique x86/x64 OS with Wine integration  
- Enhanced by NPU compute acceleration  
- Designed for experimentation, workstation use, and secure sandboxing  

InspireX combines simplicity, speed, and modern hardware capabilities into a single adaptive operating system.

---

# 📜 License

InspireX OS is released under the **MIT License**.

---

# ✅ End of README.md
