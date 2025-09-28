---
aliases:
  - gnomeExtensions.workspace-buttons-with-app-icons
tags:
  - license/unknown
  - maintainers/honnip
  - outputs/out
---

# gnomeExtensions.workspace-buttons-with-app-icons

## 📝 Description

Replaces the original workspaces (activities) indicator with buttons. Each button contains the icons of the windows opened in that workspace.

FEATURES
Multi Monitor Support: Creates extra topbars for other monitors. Each workspace button contains only the icons for that workspace-monitor combo.
Dynamic and Fixed Workspaces Support
Lots of customization options
Window Switcher Improvements: Shows only the windows from the current monitor (and workspace) and the popup appears on the currently focused monitor.
App icons ordered by most recently focused.
Efficiency: No render loops - detects small changes and updates only the affected sub-part of the UI.

ACTIONS
Mouse Scroll: Just like the original indicator switches workspaces but without the delay.
Left Click: Activates workspace that was clicked (or overview if active workspace is clicked)
Right Click: Opens window switcher menu

Ways to navigate the custom right click window switcher:
Double right-click to switch back and forth between the two most recent apps.
Scroll to select the window you want, followed by a click anywhere on the screen (outside of the popup) to switch to the last selected app.
Click on the window you want to select inside of the popup.
Use left and right arrow keys or the regular Alt+Tab/Alt+Shift+Tab keys (Enter or Escape to exit).

--------------------------

Window buttons and draggable workspace buttons (reorder workspaces) coming soon too

## 📋 Package Information

- **Name**: `gnomeExtensions.workspace-buttons-with-app-icons`
- **Version**: `10`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Replaces the original workspaces (activities) indicator with buttons. Each button contains the icons of the windows opened in that workspace.
- **Homepage**: [https://extensions.gnome.org/extension/7777/workspace-buttons-with-app-icons/](https://extensions.gnome.org/extension/7777/workspace-buttons-with-app-icons/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @honnip


## 🔧 Build Information

- **Derivation Path**: `/nix/store/05i6jqbsz6234arl59hzwzqqjjqjpsch-gnome-shell-extension-workspace-buttons-with-app-icons-10.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/desktops/gnome/extensions/buildGnomeExtension.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/05i6jqbsz6234arl59hzwzqqjjqjpsch-gnome-shell-extension-workspace-buttons-with-app-icons-10`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[kj835zxl7qafsb7vr73cgy65lbdvzg5z-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:46:45 UTC*
