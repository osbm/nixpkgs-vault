---
aliases:
  - libgpiod_1
tags:
  - license/unknown
  - outputs/out
---

# libgpiod_1

## 📝 Description

Since linux 4.8 the GPIO sysfs interface is deprecated. User space should use
the character device instead. This library encapsulates the ioctl calls and
data structures behind a straightforward API.


## 📋 Package Information

- **Name**: `libgpiod_1`
- **Version**: `1.6.4`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: C library and tools for interacting with the linux GPIO character device
- **Homepage**: [https://git.kernel.org/pub/scm/libs/libgpiod/libgpiod.git/about/](https://git.kernel.org/pub/scm/libs/libgpiod/libgpiod.git/about/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/sb3js3gg8zyfwxnxcsapgbn9asli5rv2-libgpiod-1.6.4.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libgpiod_1/package.nix:51`
- **Outputs**:
  - `out`:  `/nix/store/sb3js3gg8zyfwxnxcsapgbn9asli5rv2-libgpiod-1.6.4`

## 🔗 Dependencies

- [[1fzxi5zfzvgbj9j19wl9ihk41nhmjyw3-autoconf-archive-2024.10.16]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qlbqq3yyxgp91hs0r2a2x205sprxbs45-libgpiod-1.6.4.tar.gz]]
- [[qmg0h7ddbh8r5iissdh538jgwx5xi189-kmod-31]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/wvy877jkyp2gywp3xqxp72p3a8wknl7v-0001-Drop-AC_FUNC_MALLOC-and-_REALLOC-and-check-for-them-.patch`

---
*Generated on 2025-09-27 11:46:51 UTC*
