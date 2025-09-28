---
aliases:
  - libffi
tags:
  - license/unknown
  - maintainers/matthewbauer
  - outputs/dev
  - outputs/info
  - outputs/man
  - outputs/out
---

# libffi

## 📝 Description

The libffi library provides a portable, high level programming
interface to various calling conventions.  This allows a
programmer to call any function specified by a call interface
description at run-time.

FFI stands for Foreign Function Interface.  A foreign function
interface is the popular name for the interface that allows code
written in one language to call code written in another
language.  The libffi library really only provides the lowest,
machine dependent layer of a fully featured foreign function
interface.  A layer must exist above libffi that handles type
conversions for values passed between the two languages.


## 📋 Package Information

- **Name**: `libffi`
- **Version**: `3.5.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Foreign function call interface library
- **Homepage**: [http://sourceware.org/libffi/](http://sourceware.org/libffi/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @matthewbauer


## 🔧 Build Information

- **Derivation Path**: `/nix/store/b7g7w8fpp6xqbq6z76rdyr1g5jww7f81-libffi-3.5.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/libraries/libffi/default.nix:74`
- **Outputs**:
  - `dev`:  `/nix/store/b7g7w8fpp6xqbq6z76rdyr1g5jww7f81-libffi-3.5.1`
  - `info`:  `/nix/store/b7g7w8fpp6xqbq6z76rdyr1g5jww7f81-libffi-3.5.1`
  - `man`:  `/nix/store/b7g7w8fpp6xqbq6z76rdyr1g5jww7f81-libffi-3.5.1`
  - `out`:  `/nix/store/b7g7w8fpp6xqbq6z76rdyr1g5jww7f81-libffi-3.5.1`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[m9n1yfax19aj2hfryd78jww2mp18w411-libffi-3.5.1.tar.gz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[v4dbfbxcdcywcfqmns3lfklh26b35s48-dejagnu-1.6.3]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:45:43 UTC*
