---
aliases:
  - libdrm
tags:
  - license/unknown
  - outputs/bin
  - outputs/dev
  - outputs/out
---

# libdrm

## 📝 Description

A userspace library for accessing the DRM (Direct Rendering Manager) on
Linux, BSD and other operating systems that support the ioctl interface.
The library provides wrapper functions for the ioctls to avoid exposing
the kernel interface directly, and for chipsets with drm memory manager,
support for tracking relocations and buffers.
New functionality in the kernel DRM drivers typically requires a new
libdrm, but a new libdrm will always work with an older kernel.

libdrm is a low-level library, typically used by graphics drivers such as
the Mesa drivers, the X drivers, libva and similar projects.


## 📋 Package Information

- **Name**: `libdrm`
- **Version**: `2.4.125`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Direct Rendering Manager library and headers
- **Homepage**: [https://gitlab.freedesktop.org/mesa/drm](https://gitlab.freedesktop.org/mesa/drm)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/snbfinsd48w01hi51bzzpdl7m5n1cwif-libdrm-2.4.125.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libdrm/package.nix:71`
- **Outputs**:
  - `bin`:  `/nix/store/snbfinsd48w01hi51bzzpdl7m5n1cwif-libdrm-2.4.125`
  - `dev`:  `/nix/store/snbfinsd48w01hi51bzzpdl7m5n1cwif-libdrm-2.4.125`
  - `out`:  `/nix/store/snbfinsd48w01hi51bzzpdl7m5n1cwif-libdrm-2.4.125`

## 🔗 Dependencies

- [[6vzvy3jj3nv4iv04pdx7qz4168578833-libpciaccess-0.18.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cpinbixkmqw5xh0n4jlpyi4lqk1bqzks-python3.13-docutils-0.21.2]]
- [[dirkc1gc5niy49dn25d8kgj6r6gp1iqr-valgrind-3.25.1]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[nxxwbr9r6d0lmdinjlwnxcx15sh4sdh2-libpthread-stubs-0.5]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[r53cjxg3bf90v569xaj97j946hbdi17y-libdrm-2.4.125.tar.xz]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:45:00 UTC*
