---
aliases:
  - tinyemu
tags:
  - license/unknown
  - outputs/out
---

# tinyemu

## 📝 Description

TinyEMU is a system emulator for the RISC-V and x86 architectures. Its
purpose is to be small and simple while being complete.

Main features:

- RISC-V system emulator supporting the RV128IMAFDQC base ISA (user level
  ISA version 2.2, priviledged architecture version 1.10) including:
  - 32/64/128 bit integer registers
  - 32/64/128 bit floating point instructions (using the SoftFP Library)
  - Compressed instructions
  - Dynamic XLEN change
- x86 system emulator based on KVM
- VirtIO console, network, block device, input and 9P filesystem
- Graphical display with SDL
- JSON configuration file
- Remote HTTP block device and filesystem
- Small code, easy to modify, few external dependancies
- Javascript version running Linux and Windows 2000.


## 📋 Package Information

- **Name**: `tinyemu`
- **Version**: `2019-12-21`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: System emulator for the RISC-V and x86 architectures
- **Homepage**: [https://bellard.org/tinyemu/](https://bellard.org/tinyemu/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/kc93kal8qld8b4md5slhl77q9cy31zsw-tinyemu-2019-12-21.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ti/tinyemu/package.nix:41`
- **Outputs**:
  - `out`:  `/nix/store/kc93kal8qld8b4md5slhl77q9cy31zsw-tinyemu-2019-12-21`

## 🔗 Dependencies

- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[g1smgp5dhq2ii8np7vm7n5znki3ak1b1-curl-8.14.1]]
- [[jqjb48yqql5qqngxpgzgfs76b0pmsa4p-tinyemu-2019-12-21.tar.gz]]
- [[n4hamrwqckas4h8qbzzbrdrgw64f6s7r-SDL_compat-1.2.68]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:12:05 UTC*
