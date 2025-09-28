---
aliases:
  - open-watcom-v2-unwrapped
tags:
  - not-available
  - license/unknown
  - maintainers/OPNA2608
  - outputs/out
---

# open-watcom-v2-unwrapped

## 📝 Description

A fork of Open Watcom: A C/C++/Fortran compiler and assembler suite
targeting a multitude of architectures (x86, IA-32, Alpha AXP, MIPS,
PowerPC) and operating systems (DOS, OS/2, Windows, Linux).

Main differences from Open Watcom 1.9:

- New two-phase build system - Open Watcom can be built by the host's
  native C/C++ compiler or by itself
- Code generator properly initializes pointers by DLL symbol addresses
- DOS tools now support long file names (LFN) if appropriate LFN driver
  is loaded by DOS
- Open Watcom is ported to 64-bit hosts (Win64, Linux x64)
- Librarian supports x64 CPU object modules and libraries
- RDOS 32-bit C run-time compact memory model libraries are fixed
- Resource compiler and Resource editors support Win64 executables
- Open Watcom text editor is now self-contained, it can be used as
  standalone tool without any requirements for any additional files or
  configuration
- Broken C++ compiler pre-compiled header template support is fixed
- Many C++ compiler crashes are fixed
- Debugger has no length limit for any used environment variable

The documentation has been excluded from this build for build time reasons. It can be found here:
https://github.com/open-watcom/open-watcom-v2/wiki/Open-Watcom-Documentation


## 📋 Package Information

- **Name**: `open-watcom-v2-unwrapped`
- **Version**: `0-unstable-2025-05-07`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: V2 fork of the Open Watcom suite of compilers and tools
- **Homepage**: [https://open-watcom.github.io](https://open-watcom.github.io)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`, `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @OPNA2608


## 🔧 Build Information

- **Derivation Path**: `/nix/store/v21l20i81f70vxjfb37axf6lhza433bc-open-watcom-v2-unwrapped-0-unstable-2025-05-07.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/compilers/open-watcom/v2.nix:101`
- **Outputs**:
  - `out`:  `/nix/store/v21l20i81f70vxjfb37axf6lhza433bc-open-watcom-v2-unwrapped-0-unstable-2025-05-07`

## 🔗 Dependencies

- [[16xidmjcnhzh766inxnpkhy5jmjcnabx-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[mdgwas2pfaxyp0shdmi69a450nsas46w-dosbox-0.74-3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:55:09 UTC*
