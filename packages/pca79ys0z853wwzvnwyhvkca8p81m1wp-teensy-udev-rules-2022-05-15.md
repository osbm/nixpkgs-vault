---
aliases:
  - teensy-udev-rules
tags:
  - not-available
  - license/unknown
  - maintainers/aidalgol
  - outputs/out
---

# teensy-udev-rules

## 📝 Description

udev rules that give non-root users permission to communicate with the
Teensy family of microcontrolers.

ModemManager (part of NetworkManager) can interfere with USB Serial
devices, which includes the Teensy.  See comments in the .rules file (or
this package's homepage) for possible workarounds.


## 📋 Package Information

- **Name**: `teensy-udev-rules`
- **Version**: `2022-05-15`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: udev rules for the Teensy microcontrollers
- **Homepage**: [https://www.pjrc.com/teensy/00-teensy.rules](https://www.pjrc.com/teensy/00-teensy.rules)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @aidalgol


## 🔧 Build Information

- **Derivation Path**: `/nix/store/pca79ys0z853wwzvnwyhvkca8p81m1wp-teensy-udev-rules-2022-05-15.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/te/teensy-udev-rules/package.nix:26`
- **Outputs**:
  - `out`:  `/nix/store/pca79ys0z853wwzvnwyhvkca8p81m1wp-teensy-udev-rules-2022-05-15`

## 🔗 Dependencies

- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/9sznzkmm9z6fp9jcw6lj715yv48vagpx-teensy.rules`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:05:21 UTC*
