---
aliases:
  - gmpxx
tags:
  - license/unknown
  - outputs/dev
  - outputs/info
  - outputs/out
---

# gmpxx

## 📝 Description

GMP is a free library for arbitrary precision arithmetic, operating
on signed integers, rational numbers, and floating point numbers.
There is no practical limit to the precision except the ones implied
by the available memory in the machine GMP runs on.  GMP has a rich
set of functions, and the functions have a regular interface.

The main target applications for GMP are cryptography applications
and research, Internet security applications, algebra systems,
computational algebra research, etc.

GMP is carefully designed to be as fast as possible, both for small
operands and for huge operands.  The speed is achieved by using
fullwords as the basic arithmetic type, by using fast algorithms,
with highly optimised assembly code for the most common inner loops
for a lot of CPUs, and by a general emphasis on speed.

GMP is faster than any other bignum library.  The advantage for GMP
increases with the operand sizes for many operations, since GMP uses
asymptotically faster algorithms.


## 📋 Package Information

- **Name**: `gmpxx`
- **Version**: `6.3.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GNU multiple precision arithmetic library
- **Homepage**: [https://gmplib.org/](https://gmplib.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/5fnl19ibazlhzcrmxg56s11v29rw1cqc-gmp-with-cxx-6.3.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/libraries/gmp/6.x.nix:83`
- **Outputs**:
  - `dev`:  `/nix/store/5fnl19ibazlhzcrmxg56s11v29rw1cqc-gmp-with-cxx-6.3.0`
  - `info`:  `/nix/store/5fnl19ibazlhzcrmxg56s11v29rw1cqc-gmp-with-cxx-6.3.0`
  - `out`:  `/nix/store/5fnl19ibazlhzcrmxg56s11v29rw1cqc-gmp-with-cxx-6.3.0`

## 🔗 Dependencies

- [[4yqg8zj3kr39kp96mkzwl7dpbwk0pnyb-gmp-6.3.0.tar.bz2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i9kj1nhzkg91xsq8ny4z4hipl0b42kad-gcc-wrapper-14.3.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[sp2vq01660i7gmsgddk4x9di14gwny4m-gnum4-1.4.20]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:07:03 UTC*
