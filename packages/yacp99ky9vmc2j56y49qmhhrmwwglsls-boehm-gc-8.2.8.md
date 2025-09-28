---
aliases:
  - nixDependencies.boehmgc
tags:
  - license/unknown
  - outputs/debug
  - outputs/dev
  - outputs/doc
  - outputs/out
---

# nixDependencies.boehmgc

## 📝 Description

The Boehm-Demers-Weiser conservative garbage collector can be used as a
garbage collecting replacement for C malloc or C++ new.  It allows you
to allocate memory basically as you normally would, without explicitly
deallocating memory that is no longer useful.  The collector
automatically recycles memory when it determines that it can no longer
be otherwise accessed.

The collector is also used by a number of programming language
implementations that either use C as intermediate code, want to
facilitate easier interoperation with C libraries, or just prefer the
simple collector interface.

Alternatively, the garbage collector may be used as a leak detector for
C or C++ programs, though that is not its primary goal.


## 📋 Package Information

- **Name**: `nixDependencies.boehmgc`
- **Version**: `8.2.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Boehm-Demers-Weiser conservative garbage collector for C and C++
- **Homepage**: [https://hboehm.info/gc/](https://hboehm.info/gc/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/yacp99ky9vmc2j56y49qmhhrmwwglsls-boehm-gc-8.2.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/bo/boehmgc/package.nix:100`
- **Outputs**:
  - `debug`:  `/nix/store/yacp99ky9vmc2j56y49qmhhrmwwglsls-boehm-gc-8.2.8`
  - `dev`:  `/nix/store/yacp99ky9vmc2j56y49qmhhrmwwglsls-boehm-gc-8.2.8`
  - `doc`:  `/nix/store/yacp99ky9vmc2j56y49qmhhrmwwglsls-boehm-gc-8.2.8`
  - `out`:  `/nix/store/yacp99ky9vmc2j56y49qmhhrmwwglsls-boehm-gc-8.2.8`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[n4p250r8n65bdchg2ybbkhci48paq47b-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/r989dk196nl9frhnfsa1lb7knhbyjxw6-separate-debug-info.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:22:52 UTC*
