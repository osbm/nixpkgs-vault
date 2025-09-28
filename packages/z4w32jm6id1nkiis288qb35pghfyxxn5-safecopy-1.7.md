---
aliases:
  - safecopy
tags:
  - license/unknown
  - outputs/out
---

# safecopy

## 📝 Description

Safecopy is a data recovery tool which tries to extract as much data as possible from a
problematic (i.e. damaged sectors) source - like floppy drives, hard disk partitions, CDs,
tape devices, etc, where other tools like dd would fail due to I/O errors.

Safecopy includes a low level IO layer to read CDROM disks in raw mode, and issue device
resets and other helpful low level operations on a number of other device classes.


## 📋 Package Information

- **Name**: `safecopy`
- **Version**: `1.7`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Data recovery tool for damaged hardware
- **Homepage**: [https://safecopy.sourceforge.net](https://safecopy.sourceforge.net)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/z4w32jm6id1nkiis288qb35pghfyxxn5-safecopy-1.7.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sa/safecopy/package.nix:17`
- **Outputs**:
  - `out`:  `/nix/store/z4w32jm6id1nkiis288qb35pghfyxxn5-safecopy-1.7`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[iih7b0hz7c4pwqppwwzvf2c3bc2zyf0k-safecopy-1.7.tar.gz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:18:22 UTC*
