---
aliases:
  - wiggle
tags:
  - license/unknown
  - outputs/out
---

# wiggle

## 📝 Description

Wiggle applies patches to a file in a similar manner to the patch(1)
program. The distinctive difference is, however, that wiggle will
attempt to apply a patch even if the "before" part of the patch doesn't
match the target file perfectly. This is achieved by breaking the file
and patch into words and finding the best alignment of words in the file
with words in the patch. Once this alignment has been found, any
differences (word-wise) in the patch are applied to the file as best as
possible. Also, wiggle will (in some cases) detect changes that have
already been applied, and will ignore them.


## 📋 Package Information

- **Name**: `wiggle`
- **Version**: `1.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tool for applying patches with conflicts
- **Homepage**: [https://blog.neil.brown.name/category/wiggle/](https://blog.neil.brown.name/category/wiggle/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/kislls361x06f3vfhv1qx9r1g710d61v-wiggle-1.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/wi/wiggle/package.nix:41`
- **Outputs**:
  - `out`:  `/nix/store/kislls361x06f3vfhv1qx9r1g710d61v-wiggle-1.3`

## 🔗 Dependencies

- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[kdcdz479ki44cig1n9zxb42b3j3z5g3s-groff-1.23.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vxnjasi4i2c36fyymsr0n8bixrqxjiiy-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:13:50 UTC*
