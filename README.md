# USBIF  
**Universal Serial Bus Image Flasher**

USBIF is a cross-platform image flashing and disc burning utility with a strong focus on safety, transparency, and a modern SwiftUI-inspired interface.  
It supports USB flash drives, DVD/CD burning, GRUB-based multiboot setups, and game media preparation.

---

## Features

### USB Image Flashing
- Flashes `.iso`, `.img`, and similar images to **removable USB drives only**
- System and internal drives are hard-blocked
- Mounted volume detection and protection
- Optional verification after write
- Optional automatic ejection on completion

### DVD / CD Burning
- Burns ISO images to optical media
- Automatic optical drive detection
- Optional verification and disc finalization
- Burn speed selection when supported

### GRUB Mode (Multi-ISO USB)
- Prepares a USB drive with GRUB
- Downloads ISO images directly from the internet
- Automatically installs and configures GRUB
- Detects and lists installed ISOs in the boot menu
- Supports custom GRUB themes

### Game Media Support
- Flash and prepare **game content** on USB drives
- Supports:
  - `.zip` games, where the user selects which executable or boot file to launch
  - ROM files for supported emulators or boot environments
- Allows manual selection of the entry file when multiple bootable files exist
- Designed for legitimate backups, homebrew, and legally owned software

### Safety Systems
- System drive detection and blocking
- Removable-media-only enforcement
- Mounted disk validation
- ISO validation and checksum verification
- **Quick Time Event (QTE) safety gate** requiring user interaction before destructive actions

### Transparency & Logging
- Live progress window showing all operations
- Step-by-step action logging
- Optional timelapse-style replay of the flashing or burning process
- Exportable session logs

### UI / UX
- SwiftUI-inspired interface design
- Clean, card-based layout
- Sidebar navigation
- Progress indicators with speed and ETA
- Expandable advanced log views

---

## Tech Stack

- **Language:** Python
- **UI Framework:** PySide6 (Qt 6) with QML
- **Bootloader:** GRUB2
- **Supported Platforms:** Linux, Windows, macOS

---

## License

USBIF is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.

This software is free and open-source under the terms of the GPL-3.0:
- You may use, study, modify, and redistribute the software
- Any redistribution or modification must remain licensed under GPL-3.0
- The source code must remain available to users

See the `LICENSE` file for the full license text.

---

## Anti-Piracy Notice

USBIF **does not condone piracy**.

This software is intended for:
- Flashing operating system images
- Creating bootable recovery or installer media
- Using legally owned game backups
- Homebrew software and ROMs you are legally permitted to use

Users are responsible for ensuring they have the legal right to use, copy, or flash any content processed by USBIF.

---

## Disclaimer

USBIF performs **destructive operations** on storage devices.  
Improper use may result in **permanent data loss**.

Always verify the selected target device before proceeding.

---

## Author

Created and maintained by **HatD3V**.
