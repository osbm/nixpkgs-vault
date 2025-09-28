---
aliases:
  - ktx-tools
tags:
  - license/unknown
  - maintainers/bonsairobo
  - outputs/out
---

# ktx-tools

## 📝 Description

KTX (Khronos Texture) is a lightweight container for textures for OpenGL®,
Vulkan® and other GPU APIs. KTX files contain all the parameters needed
for texture loading. A single file can contain anything from a simple
base-level 2D texture through to a cubemap array texture with mipmaps.

This software package contains:
  - libktx: a small library of functions for writing and reading KTX
    files, and instantiating OpenGL®, OpenGL ES™️ and Vulkan® textures
    from them.
  - ktx2check: a tool for validating KTX Version 2 format files.
  - ktx2ktx2: a tool for converting a KTX Version 1 file to a KTX Version
    2 file.
  - ktxinfo: a tool to display information about a KTX file in human
    readable form.
  - ktxsc: a tool to supercompress a KTX Version 2 file that contains
    uncompressed images.
  - toktx: a tool to create KTX files from PNG, Netpbm or JPEG format
    images. It supports mipmap generation, encoding to Basis Universal
    formats and Zstd supercompression.


## 📋 Package Information

- **Name**: `ktx-tools`
- **Version**: `4.4.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: KTX (Khronos Texture) Library and Tools
- **Homepage**: [https://github.com/KhronosGroup/KTX-Software](https://github.com/KhronosGroup/KTX-Software)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @bonsairobo


## 🔧 Build Information

- **Derivation Path**: `/nix/store/g6p2mjxwgn329xx304s6f0rp60jhishy-ktx-tools-4.4.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/kt/ktx-tools/package.nix:39`
- **Outputs**:
  - `out`:  `/nix/store/g6p2mjxwgn329xx304s6f0rp60jhishy-ktx-tools-4.4.0`

## 🔗 Dependencies

- [[4b4zc0cg1hj290r7v12a7s5fyx0lfzfz-doxygen-1.14.0]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[k0vc46crpzmnzacg8z3akh23sizagd2l-source]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q6r8nhgmx37s1vk3580hn9q1illlh9n2-getopt-1.1.6]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:16:06 UTC*
