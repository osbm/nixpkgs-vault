---
aliases:
  - gnomeExtensions.campeek
tags:
  - license/unknown
  - maintainers/honnip
  - outputs/out
---

# gnomeExtensions.campeek

## 📝 Description

CamPeek is a powerful yet lightweight GNOME Shell extension inspired by the popular macOS app Hand Mirror, providing instant webcam access directly from your Linux desktop's top bar with advanced camera compatibility and intelligent detection.

🎥 Key Features:
• ✨ Instant Access: Open your webcam feed in one quick click—perfect for a last-minute check before video calls.
• 🖼️ Minimalist Design: A sleek, always-on-top, frameless window for a distraction-free preview.
• 🔒 Privacy First: CamPeek streams your webcam feed directly without recording or saving any data.
• 🚀 Lightweight &amp; Simple: Fast, unobtrusive, and integrates smoothly into your GNOME desktop experience.

🔧 Advanced Camera Support:
• 🎯 Intelligent Detection: Advanced multi-method camera detection with 95%+ compatibility across camera types.
• 📹 Multi-Camera Support: Right-click to switch between multiple cameras with real camera names (not just "Camera 0").
• 🔄 Adaptive Resolution: Automatically detects and uses optimal resolutions (16:9 preferred, 4:3 fallback).
• 🏗️ Enhanced Compatibility: Works with built-in laptop cameras, USB webcams, professional cameras, and capture cards.
• ⚡ Optimized Performance: 60-80% faster camera detection with intelligent testing order (capability → format → GStreamer).
• 🛠️ Smart Fallback: Multiple detection methods ensure compatibility with non-standard drivers and older cameras.

🎛️ Technical Excellence:
• 📊 Expanded Device Range: Scans up to 20 camera devices (/dev/video0-19) for comprehensive coverage.
• 🔍 Dual Capability Detection: Primary method checks Device Caps, fallback method for older cameras.
• 📐 Format Validation: Counts actual video formats to distinguish capture devices from metadata devices.
• 🎬 Enhanced GStreamer Pipeline: Adaptive capabilities with videoconvert, videoscale, and quality optimization.
• ⚠️ Intelligent Error Handling: Specific error types with helpful solutions (missing GStreamer, permissions, etc.).

📍 Ideal For:
• Quickly checking your appearance or environment before meetings.
• Confirming camera functionality instantly—no need to open heavy applications.
• Privacy-conscious users looking for a fast and straightforward webcam preview tool.
• Users with multiple cameras who need easy switching between devices.
• Systems with built-in cameras, professional equipment, or non-standard camera drivers.

## 📋 Package Information

- **Name**: `gnomeExtensions.campeek`
- **Version**: `25`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: CamPeek is a powerful yet lightweight GNOME Shell extension inspired by the popular macOS app Hand Mirror, providing instant webcam access directly from your Linux desktop's top bar with advanced camera compatibility and intelligent detection.
- **Homepage**: [https://extensions.gnome.org/extension/8092/campeek/](https://extensions.gnome.org/extension/8092/campeek/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @honnip


## 🔧 Build Information

- **Derivation Path**: `/nix/store/m7g6a9xwpl61l3qb6fdlbn5xh1hs6z3y-gnome-shell-extension-campeek-25.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/desktops/gnome/extensions/buildGnomeExtension.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/m7g6a9xwpl61l3qb6fdlbn5xh1hs6z3y-gnome-shell-extension-campeek-25`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dq2if921a0sgl39wha8jl1jiaf9q8jph-source]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:13:01 UTC*
