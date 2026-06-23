# S6-NetHunter-HID-Conversion – Kernel Package

This repository provides the custom kernel package required to enable **USB HID (Human Interface Device) emulation** on a Samsung Galaxy S6 Edge (SM-G925F) running Android 7 (Nougat) with Kali NetHunter.

## What’s inside

- **kernel-nethunter-20231005_083817-zerolte-nougat.zip** – a pre‑built Android kernel that unlocks:
  - USB gadget simulation (`/dev/hidg*`) for keyboard/mouse injection.
  - Raw USB hardware permissions (usually blocked on stock devices).
  - Support for advanced Wi‑Fi injection and other NetHunter features.

This package is a critical component for turning your S6 Edge into a fully functional pentesting device capable of DuckHunter payloads and physical USB attacks.

## Installation

1. Download the `kernel-nethunter-*.zip` from this repository.
2. Transfer the file to your device (already running LineageOS 14.1 with Magisk root).
3. Open the Magisk app → **Modules** → **Install from storage** and select the zip.
4. Reboot the device.

For the complete step‑by‑step guide (flashing TWRP, LineageOS, NetHunter, and testing HID), please refer to the main tutorial: 

[Full Guide – Samsung S6 Edge NetHunter HID Conversion](https://nullsect-portfolio.vercel.app/blog/rooting_s6)  


## ⚠️ Disclaimer

This kernel is provided for educational and authorized security testing purposes only. Use it responsibly and only on devices you own or have explicit permission to test. The author is not responsible for any damage or misuse.