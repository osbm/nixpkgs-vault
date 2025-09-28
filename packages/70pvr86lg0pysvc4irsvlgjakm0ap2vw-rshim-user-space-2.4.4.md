---
aliases:
  - rshim-user-space
tags:
  - license/unknown
  - maintainers/thillux
  - outputs/out
---

# rshim-user-space

## 📝 Description

The rshim driver provides a way to access the rshim resources on the
BlueField target from external host machine. The current version
implements device files for boot image push and virtual console access.
It also creates virtual network interface to connect to the BlueField
target and provides a way to access the internal rshim registers.


## 📋 Package Information

- **Name**: `rshim-user-space`
- **Version**: `2.4.4`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: User-space rshim driver for the BlueField SoC
- **Homepage**: [https://github.com/Mellanox/rshim-user-space](https://github.com/Mellanox/rshim-user-space)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @thillux


## 🔧 Build Information

- **Derivation Path**: `/nix/store/70pvr86lg0pysvc4irsvlgjakm0ap2vw-rshim-user-space-2.4.4.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/rs/rshim-user-space/package.nix:83`
- **Outputs**:
  - `out`:  `/nix/store/70pvr86lg0pysvc4irsvlgjakm0ap2vw-rshim-user-space-2.4.4`

## 🔗 Dependencies

- [[4f9j67x7cgs2hzjgyyzm8q6z1w2vgy41-which-2.23]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[7ys6vrd29swy0hb42rbhrc1sbsk4cq1g-autoconf-2.72]]
- [[82mw0nl5kb1zw36l4s4d0pdlfiadwlss-automake-1.18.1]]
- [[9zshxf6kk537mzc627ynbj5lgp1qff15-util-linux-2.41.1]]
- [[b6lan6ymi22sy8w981cx3x2nymcyvx7r-pciutils-3.14.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cflrzgbglppcagf2jfix9hgq25126m9z-gnugrep-3.12]]
- [[fy9wjrqf0pzd5x3rvy665v50ff747wfd-libusb-1.0.29]]
- [[ji56v9i7bdf14w53nxy71cpr8rrrvmma-fuse-2.9.9]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[lxw1zfs9v3nm19mpqbllvcl3s2hkpbjq-procps-4.0.4]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pn03b9dijjmykv1k5sfjm4h990h4k25f-make-binary-wrapper-hook]]
- [[q331wl66bksvjp5qq0b3dhbcw3fx09x2-gawk-5.3.2]]
- [[qm2zn63wsvfv5ba22xcbabxnmykb4f00-source]]
- [[r9dbjbyllw6nh79qpff5anpqwi1x8niq-pv-1.9.34]]
- [[whmvyjphw10d78zfrb04kqjlc0dy68z3-gnused-4.9]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:21:33 UTC*
