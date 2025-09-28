---
aliases:
  - libGL
tags:
  - license/unknown
  - outputs/dev
  - outputs/out
---

# libGL

## 📝 Description

libglvnd is a vendor-neutral dispatch layer for arbitrating OpenGL API
calls between multiple vendors. It allows multiple drivers from different
vendors to coexist on the same filesystem, and determines which vendor to
dispatch each API call to at runtime.
Both GLX and EGL are supported, in any combination with OpenGL and OpenGL ES.


## 📋 Package Information

- **Name**: `libGL`
- **Version**: `1.7.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GL Vendor-Neutral Dispatch library
- **Homepage**: [https://gitlab.freedesktop.org/glvnd/libglvnd/](https://gitlab.freedesktop.org/glvnd/libglvnd/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/761d6f8hhrvq2qrbqc6ygxr3x34img28-libglvnd-1.7.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libglvnd/package.nix:94`
- **Outputs**:
  - `dev`:  `/nix/store/761d6f8hhrvq2qrbqc6ygxr3x34img28-libglvnd-1.7.0`
  - `out`:  `/nix/store/761d6f8hhrvq2qrbqc6ygxr3x34img28-libglvnd-1.7.0`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[3aflm58fw2kw8nkcnns7h4lgmrdf5hp8-xorgproto-2024.1]]
- [[6aspsnqcm466pmidqqnd0j1f3nb3i688-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[d32ziqbqrsp0bsjxdlsli5993sc2prm3-large-file.patch]]
- [[d99f4z55b6p4hx1wfl4r6d6i0zi5bh7m-libxext-1.3.6]]
- [[fcmb190sh4glwkjmww12ibdakqdqs4j6-add-driver-runpath]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[nncd4f9vl1alqwmiff6a138ppbsgbp5l-libx11-1.8.12]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:13:02 UTC*
