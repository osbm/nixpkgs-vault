---
aliases:
  - gnomeExtensions.power-tracker
tags:
  - license/unknown
  - maintainers/honnip
  - outputs/out
---

# gnomeExtensions.power-tracker

## 📝 Description

GNOME PowerTracker is a simple application that helps users monitor their power consumption on GNOME-based systems.

- Does not use any dependency
- Autodetects battery (BAT0, BAT1, BATT: /sys/class/power_supply)
- You can configure refresh rate

IMPORTANT.
- This will only work with laptops. Afaik there's no simple way to track desktop power consumption
- Power when fully charged is 0W
- Power when charging has a plus sign
- Power when discharging has a minus sign

If you have any issue, please report it so I can take a look at it!
Enjoy!


## 📋 Package Information

- **Name**: `gnomeExtensions.power-tracker`
- **Version**: `12`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GNOME PowerTracker is a simple application that helps users monitor their power consumption on GNOME-based systems.
- **Homepage**: [https://extensions.gnome.org/extension/7341/power-tracker/](https://extensions.gnome.org/extension/7341/power-tracker/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @honnip


## 🔧 Build Information

- **Derivation Path**: `/nix/store/axbnh27q05ry7d8szs7jjx915khf9djq-gnome-shell-extension-power-tracker-12.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/desktops/gnome/extensions/buildGnomeExtension.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/axbnh27q05ry7d8szs7jjx915khf9djq-gnome-shell-extension-power-tracker-12`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vjyafvksnq8iv23pgbkdafy2px62mlkm-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:42:07 UTC*
