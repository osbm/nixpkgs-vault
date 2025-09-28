---
aliases:
  - xob
tags:
  - license/unknown
  - maintainers/florentc
  - outputs/out
---

# xob

## 📝 Description

A lightweight configurable overlay volume/backlight/progress/anything bar
for the X Window System (and Wayland compositors with XWayland). Each
time a new value is read on the standard input, it is displayed as a
tv-like bar over other windows. It then vanishes after a configurable
amount of time. A value followed by a bang '!' is displayed using an
alternate color to account for special states (e.g. muted audio). There
is also support for overflows (when the value exceeds the maximum).


## 📋 Package Information

- **Name**: `xob`
- **Version**: `0.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Lightweight overlay bar for the X Window System
- **Homepage**: [https://github.com/florentc/xob](https://github.com/florentc/xob)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @florentc


## 🔧 Build Information

- **Derivation Path**: `/nix/store/rw976djigzh0xswm2as18lh5zds18pld-xob-0.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/xo/xob/package.nix:31`
- **Outputs**:
  - `out`:  `/nix/store/rw976djigzh0xswm2as18lh5zds18pld-xob-0.3`

## 🔗 Dependencies

- [[1j4w72gp535nddl6sa8yc1fjd8cfc004-source]]
- [[a11zhx32xg78ffjgam489wrkd6k1fc87-libxrender-0.9.12]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[nncd4f9vl1alqwmiff6a138ppbsgbp5l-libx11-1.8.12]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qw4xq2c5qjcyjfzrd20ww7r2pxcxsy5n-libconfig-1.8]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:13:12 UTC*
