---
aliases:
  - cdemu-daemon
tags:
  - license/unknown
  - maintainers/bendlas
  - outputs/out
---

# cdemu-daemon

## 📝 Description

CDEmu consists of:

- a kernel module implementing a virtual drive-controller
- libmirage which is a software library for interpreting optical disc images
- a daemon which emulates the functionality of an optical drive+disc
- textmode and GTK clients for controlling the emulator
- an image analyzer to view the structure of image files

Optical media emulated by CDemu can be mounted within Linux. Automounting is also allowed.


## 📋 Package Information

- **Name**: `cdemu-daemon`
- **Version**: `3.2.7`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Suite of tools for emulating optical drives and discs
- **Homepage**: [https://cdemu.sourceforge.io/about/daemon/](https://cdemu.sourceforge.io/about/daemon/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @bendlas


## 🔧 Build Information

- **Derivation Path**: `/nix/store/km1qrk5qy2s7dkjwnscs8ggmlh2iprg0-cdemu-daemon-3.2.7.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/applications/emulators/cdemu/daemon.nix:50`
- **Outputs**:
  - `out`:  `/nix/store/km1qrk5qy2s7dkjwnscs8ggmlh2iprg0-cdemu-daemon-3.2.7`

## 🔗 Dependencies

- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[f368fizl82c6krd1a5gcxp0m6m4zd474-intltool-0.51.0]]
- [[gl10agdl6pf6rsyissrixv6sgpl39p4c-libao-1.2.2]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qj1mb50rpw1z9yd7l060x3a2k3r913l0-cdemu-daemon-3.2.7.tar.xz]]
- [[xfq3fnyh60vwlxw4y9vjaq2af8kndv3p-libmirage-3.2.10]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:57:36 UTC*
