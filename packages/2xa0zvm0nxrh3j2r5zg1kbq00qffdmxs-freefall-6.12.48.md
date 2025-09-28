---
aliases:
  - freefall
tags:
  - license/unknown
  - outputs/out
---

# freefall

## 📝 Description

Provides a shock protection facility in modern laptops with spinning hard
drives, by stopping all input/output operations on the internal hard drive
and parking its heads on the ramp when critical situations are anticipated.
Requires support for the ATA/ATAPI-7 IDLE IMMEDIATE command with unload
feature, which should cause the drive to switch to idle mode and unload the
disk heads, and an accelerometer device. It has no effect on SSD devices!


## 📋 Package Information

- **Name**: `freefall`
- **Version**: `6.12.48`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Free-fall protection for spinning HP/Dell laptop hard drives
- **Homepage**: [https://www.kernel.org/](https://www.kernel.org/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/2xa0zvm0nxrh3j2r5zg1kbq00qffdmxs-freefall-6.12.48.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/freefall/default.nix:25`
- **Outputs**:
  - `out`:  `/nix/store/2xa0zvm0nxrh3j2r5zg1kbq00qffdmxs-freefall-6.12.48`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i7ciyvjvlc6vy7hcg6ji26lr7w0fa86j-linux-6.12.48.tar.xz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:50:08 UTC*
