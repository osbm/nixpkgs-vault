---
aliases:
  - lwan
tags:
  - license/unknown
  - maintainers/leenaars
  - outputs/out
---

# lwan

## 📝 Description

A lightweight and speedy web server with a low memory
      footprint (~500KiB for 10k idle connections), with minimal system calls and
      memory allocation.  Lwan contains a hand-crafted HTTP request parser. Files are
      served using the most efficient way according to their size: no copies between
      kernel and userland for files larger than 16KiB.  Smaller files are sent using
      vectored I/O of memory-mapped buffers. Header overhead is considered before
      compressing small files.  Features include: mustache templating engine and IPv6
      support.
    

## 📋 Package Information

- **Name**: `lwan`
- **Version**: `0.5`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Lightweight high-performance multi-threaded web server
- **Homepage**: [https://lwan.ws/](https://lwan.ws/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @leenaars


## 🔧 Build Information

- **Derivation Path**: `/nix/store/3kbpj0njkvjb7yadf4b3yg97p1h5sd0k-lwan-0.5.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/lw/lwan/package.nix:44`
- **Outputs**:
  - `out`:  `/nix/store/3kbpj0njkvjb7yadf4b3yg97p1h5sd0k-lwan-0.5`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[1n3vsnc9ycra1m0n6vqn9n4yjqwq823b-9b94ff5eecec1e925103b25a43dacc226a634878.patch]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[crq7bldbl87mgicd4zx2k097hwsb7pcf-jemalloc-5.3.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[zm53ms8whbjzxzn31m0wcfliaixfrgbj-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:06:14 UTC*
