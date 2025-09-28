---
aliases:
  - game-devices-udev-rules
tags:
  - license/unknown
  - maintainers/keenanweaver
  - outputs/out
---

# game-devices-udev-rules

## 📝 Description

These udev rules are intended to be used as a package under 'services.udev.packages'.
They will not be activated if installed as 'environment.systemPackages' or 'users.user.<user>.packages'.

Additionally, you may need to enable 'hardware.uinput'.


## 📋 Package Information

- **Name**: `game-devices-udev-rules`
- **Version**: `0.24`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Udev rules to make supported controllers available with user-grade permissions
- **Homepage**: [https://codeberg.org/fabiscafe/game-devices-udev](https://codeberg.org/fabiscafe/game-devices-udev)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @keenanweaver


## 🔧 Build Information

- **Derivation Path**: `/nix/store/9j480h652fxrvyfdhr3m8sb0sw8nm9ds-game-devices-udev-rules-0.24.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ga/game-devices-udev-rules/package.nix:34`
- **Outputs**:
  - `out`:  `/nix/store/9j480h652fxrvyfdhr3m8sb0sw8nm9ds-game-devices-udev-rules-0.24`

## 🔗 Dependencies

- [[02nvbmkaqzxp5jbnl7i1rcsj85r5cl5p-udev-check-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[my6728zi3443hwa2xac9xf3m8jkhli4v-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[v28sdl3535sxb6a71z5faqdzbns9pv0h-bash-interactive-5.3p3]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:54:11 UTC*
