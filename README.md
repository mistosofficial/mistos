# 🌬️ Mist OS (Alpha)

> **Where the surgical stability of Ubuntu meets the ethereal fluidity of Deepin.**

Mist OS is a custom Linux distribution built on the **Ubuntu 24.04 LTS** base, featuring the **Deepin Desktop Environment (DDE) 25**. It is designed for creators and developers who value a crystalline, "painterly" aesthetic without sacrificing the robust package support of the Ubuntu ecosystem.

---

## 🛠️ System Specifications (Build 24.14.1)

| Component | version |
| :--- | :--- |
| **OS Base** | Ubuntu 24.04.4 LTS (Noble Numbat) |
| **Desktop** | Deepin Desktop Environment (DDE) 25 |
| **Kernel** | Linux 6.8 |
| **Node.js** | v24.14.1 (Pre-baked) |
| **Architecture** | x86_64 |

---

## 🚀 Getting Started

### 1. Download the ISO
The current Alpha build is **7.06 GB**. 
[**Download Mist OS Alpha**](https://drive.usercontent.google.com/download?id=1p0YVIureMBWWFAIRQm9Gp8MigwK0tEbl&export=download)

**SHA256 Checksum:** `35e1538468327c2d7eebffaa2146df6a`

### 2. Flashing to Media
For the best experience on real hardware or SD cards, we recommend using **Rufus**:
* **Crucial:** When prompted, select **Write in DD Image mode**.
* Using standard ISO mode may result in an `(initramfs)` boot error on certain hardware.

### 3. Virtual Machine Setup
If testing in **VirtualBox**:
* Enable **EFI** in System settings.
* Set Video Memory to **128MB+**.
* Use the **VBoxSVGA** or **VMSVGA** controller with 3D Acceleration enabled.
* *Note: If you hit a black screen, use `Ctrl+Alt+F3` to access the console.*

---

## 🎨 Visual Philosophy
Mist OS is inspired by "epic fantasy" visuals—soft blurs, translucent glass effects, and a breathable digital atmosphere. It aims to reduce "UI noise" and provide a focused workspace for modern development.

---

## ⚠️ Alpha Notice
This is a **Resolute Build (v0.1)**. 
* **Known Issue:** Some Ubuntu branding may still appear during the GRUB bootloader.
* **Known Issue:** High-end transparency effects may lag in non-accelerated virtual machines.

## 🤝 Contributing
If you want to help clear the mist, feel free to fork the repo and submit a PR. We are currently looking to scrub the remaining Ubuntu branding and optimize the boot splash.

---
**Mist OS** is a community-driven project. Built with Resolute. 🌫️
