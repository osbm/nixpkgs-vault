---
aliases:
  - zstd
tags:
  - license/unknown
  - maintainers/orivej
  - outputs/bin
  - outputs/dev
  - outputs/man
  - outputs/out
---

# zstd

## 📝 Description

Zstd, short for Zstandard, is a fast lossless compression algorithm,
targeting real-time compression scenarios at zlib-level compression
ratio. Zstd can also offer stronger compression ratio at the cost of
compression speed. Speed/ratio trade-off is configurable by small
increment, to fit different situations. Note however that decompression
speed is preserved and remain roughly the same at all settings, a
property shared by most LZ compression algorithms, such as zlib.


## 📋 Package Information

- **Name**: `zstd`
- **Version**: `1.5.7`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Zstandard real-time compression algorithm
- **Homepage**: [https://facebook.github.io/zstd/](https://facebook.github.io/zstd/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @orivej


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/tools/compression/zstd/default.nix:141`
- **Outputs**:
  - `bin`:  `/nix/store/ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7`
  - `dev`:  `/nix/store/ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7`
  - `man`:  `/nix/store/ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7`
  - `out`:  `/nix/store/ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7`

## 🔗 Dependencies

- [[9rabgh1zgc8x557hx0h9xklfn0fb2nbg-cmake-minimal-3.31.7]]
- [[a8lks340bd5pdbnh7cwcq6fmyhrdxsai-file-5.45]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cflrzgbglppcagf2jfix9hgq25126m9z-gnugrep-3.12]]
- [[infpk3q9h9nsf8wbms0l1kwvsb716mji-source]]
- [[l24r82yr0kkhl29v0rccy9l7fd13plmg-man-fix.patch]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/6k4n3g5jahyxqn6m7bdviydxibzp7xx1-playtests-darwin.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:13:39 UTC*
