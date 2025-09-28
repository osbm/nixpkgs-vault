---
aliases:
  - tllist
tags:
  - license/unknown
  - maintainers/fionera
  - outputs/out
---

# tllist

## 📝 Description

Most C implementations of linked list are untyped. That is, their data
carriers are typically void *. This is error prone since your compiler
will not be able to help you correct your mistakes (oh, was it a
pointer-to-a-pointer... I thought it was just a pointer...).

tllist addresses this by using pre-processor macros to implement dynamic
types, where the data carrier is typed to whatever you want; both
primitive data types are supported as well as aggregated ones such as
structs, enums and unions.


## 📋 Package Information

- **Name**: `tllist`
- **Version**: `1.1.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: C header file only implementation of a typed linked list
- **Homepage**: [https://codeberg.org/dnkl/tllist](https://codeberg.org/dnkl/tllist)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @fionera


## 🔧 Build Information

- **Derivation Path**: `/nix/store/yskzdpnm13rk4dc3sk699hx05np0qxnr-tllist-1.1.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/tl/tllist/package.nix:33`
- **Outputs**:
  - `out`:  `/nix/store/yskzdpnm13rk4dc3sk699hx05np0qxnr-tllist-1.1.0`

## 🔗 Dependencies

- [[a3s53lrwjx3c78q471kfnw10x3sjpqbj-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:48:27 UTC*
