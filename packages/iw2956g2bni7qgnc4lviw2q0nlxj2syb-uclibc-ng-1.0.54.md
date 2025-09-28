---
aliases:
  - uclibc-ng
tags:
  - license/unknown
  - maintainers/rasendubi
  - outputs/out
---

# uclibc-ng

## 📝 Description

uClibc-ng is a small C library for developing embedded Linux systems. It
is much smaller than the GNU C Library, but nearly all applications
supported by glibc also work perfectly with uClibc-ng.

Porting applications from glibc to uClibc-ng typically involves just
recompiling the source code. uClibc-ng supports shared libraries and
threading. It currently runs on standard Linux and MMU-less (also known as
uClinux) systems with support for Aarch64, Alpha, ARC, ARM, AVR32,
Blackfin, CRIS, C-Sky, C6X, FR-V, H8/300, HPPA, i386, IA64, KVX, LM32,
M68K/Coldfire, Metag, Microblaze, MIPS, MIPS64, NDS32, NIOS2, OpenRISC,
PowerPC, RISCV64, Sparc, Sparc64, SuperH, Tile, X86_64 and XTENSA
processors. Alpha, FR-V, HPPA, IA64, LM32, NIOS2, Tile and Sparc64 are
experimental and need more testing.


## 📋 Package Information

- **Name**: `uclibc-ng`
- **Version**: `1.0.54`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Embedded C library
- **Homepage**: [https://uclibc-ng.org](https://uclibc-ng.org)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @rasendubi


## 🔧 Build Information

- **Derivation Path**: `/nix/store/iw2956g2bni7qgnc4lviw2q0nlxj2syb-uclibc-ng-1.0.54.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/uc/uclibc-ng/package.nix:130`
- **Outputs**:
  - `out`:  `/nix/store/iw2956g2bni7qgnc4lviw2q0nlxj2syb-uclibc-ng-1.0.54`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fbxk5nfg01rmpy29mlf5mfavciywyqml-stdenv-linux]]
- [[h52lzzip82l66c7bv23g7xckp89y5kgr-linux-headers-6.16]]
- [[i9kj1nhzkg91xsq8ny4z4hipl0b42kad-gcc-wrapper-14.3.0]]
- [[v1rhkmhcd02nlgm3jfljab9xjgqdwda2-uClibc-ng-1.0.54.tar.xz]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:17:51 UTC*
