---
aliases:
  - gnomeExtensions.alternate-menu-for-hplip2
tags:
  - license/unknown
  - maintainers/honnip
  - outputs/out
---

# gnomeExtensions.alternate-menu-for-hplip2

## 📝 Description

control your hp printers by calling the device manager hp-toolbox, also some useful links
Motivation: the hp-systray doesn't work reliably under gnome shell
you need to have installed hplip in order to use this
Choice of using a printer icon or a hp_logo.png if it's installed in the same place as mine on Ubuntu
you could use symbolic links to fake the path.
This is a replacement for the old "Alternate Menu for Hplip" which doesn't work under the new Gome-Shell I have cleaned it up a bit and it has a few new menu's but it is still basically the same thing.
 Added even more menus all most all system settings ones.

New: the menu will be too big if your resolution is way too low like 800x600 I have implemented a compact option in the settings, if you use it the menu will become a two colomn compact format and will fit even on such a low resolution.

New: you can now choose a custom icon in settings

Dutch language support added by Vistaus (Heimen Stoffels) https://github.com/Vistaus

In the past you needed to restart gnome-shell after upgrades so either reboot,
log out and back in again, or if your using X11 then alt+F2 then run r; But that should be good now in most cases.

## 📋 Package Information

- **Name**: `gnomeExtensions.alternate-menu-for-hplip2`
- **Version**: `48`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: control your hp printers by calling the device manager hp-toolbox, also some useful links
- **Homepage**: [https://extensions.gnome.org/extension/4739/alternate-menu-for-hplip2/](https://extensions.gnome.org/extension/4739/alternate-menu-for-hplip2/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @honnip


## 🔧 Build Information

- **Derivation Path**: `/nix/store/675ygf4k4893pwv8d4ydhv0j3bfs7sl9-gnome-shell-extension-alternate-menu-for-hplip2-48.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/desktops/gnome/extensions/buildGnomeExtension.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/675ygf4k4893pwv8d4ydhv0j3bfs7sl9-gnome-shell-extension-alternate-menu-for-hplip2-48`

## 🔗 Dependencies

- [[62cjx6rb7d31z1fgvanrw61kd0vh9ymx-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:11:50 UTC*
