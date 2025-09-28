---
aliases:
  - samurai
tags:
  - license/unknown
  - maintainers/dtzWill
  - outputs/out
---

# samurai

## 📝 Description

samurai is a ninja-compatible build tool with a focus on simplicity,
speed, and portability.

It is written in C99, requires various POSIX.1-2008 interfaces, and
nowadays implements ninja build language through version 1.9.0 except for
Microsoft (R) Visual C++ (TM) dependency handling (deps = msvc).

It is feature-complete (but not bug-compatible) and supports most of the
same options as ninja, using the same format for .ninja_log and
.ninja_deps as the original ninja tool, currently version 5 and 4
respectively.


## 📋 Package Information

- **Name**: `samurai`
- **Version**: `1.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Ninja-compatible build tool written in C
- **Homepage**: [https://github.com/michaelforney/samurai](https://github.com/michaelforney/samurai)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @dtzWill


## 🔧 Build Information

- **Derivation Path**: `/nix/store/1cvfdigyqi1dyyswad4cnxwm2a9gdmjw-samurai-1.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sa/samurai/package.nix:42`
- **Outputs**:
  - `out`:  `/nix/store/1cvfdigyqi1dyyswad4cnxwm2a9gdmjw-samurai-1.2`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[ql946ia5chr50shk4nb50cbkvjnffw10-CVE-2021-30219.patch]]
- [[s5ndm0r7hv6jl6cq73qp69s0m4gl0jav-source]]
- [[wzkh4z8gdqa3pk6mcnsyf9fp0y3jqq1l-CVE-2021-30218.patch]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:19:17 UTC*
