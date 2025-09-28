---
aliases:
  - gcdemu
tags:
  - license/unknown
  - maintainers/bendlas
  - outputs/out
---

# gcdemu

## 📝 Description

CDEmu consists of:

- a kernel module implementing a virtual drive-controller
- libmirage which is a software library for interpreting optical disc images
- a daemon which emulates the functionality of an optical drive+disc
- textmode and GTK clients for controlling the emulator
- an image analyzer to view the structure of image files

Optical media emulated by CDemu can be mounted within Linux. Automounting is also allowed.


## 📋 Package Information

- **Name**: `gcdemu`
- **Version**: `3.2.6`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Suite of tools for emulating optical drives and discs
- **Homepage**: [https://cdemu.sourceforge.io/](https://cdemu.sourceforge.io/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @bendlas


## 🔧 Build Information

- **Derivation Path**: `/nix/store/87qn9z48ph90a0xwshqavk96vx49q2xw-gcdemu-3.2.6.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/applications/emulators/cdemu/common-drv-attrs.nix:16`
- **Outputs**:
  - `out`:  `/nix/store/87qn9z48ph90a0xwshqavk96vx49q2xw-gcdemu-3.2.6`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[474kivdzi525za8vzpgr0ils1k0qf8r3-wrap-gapps-hook]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bfrhypf8s25npqqk6h8hi5qyr3apb3vr-gdk-pixbuf-2.42.12]]
- [[bj0js1wj419z0jhy5z9k7464p5423g3y-adwaita-icon-theme-48.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[f368fizl82c6krd1a5gcxp0m6m4zd474-intltool-0.51.0]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[jqqc83j9v460xa1qlp77ky52gbqg5af8-gobject-introspection-wrapped-1.84.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[mh835h1mhbqinppdi3ggz9f28b87f0vz-libnotify-0.8.6]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rlyzp1xm9ghkyf96qij1dnxki5g725px-python3.13-pygobject-3.50.0]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[xnlbcbdv1hyyl0hcj303n9rpl9afhcbf-gcdemu-3.2.6.tar.xz]]
- [[yrjjl3kfrjd9529s7f5fyyvadraznmxs-libappindicator-gtk3-12.10.1+20.10.20200706.1]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:56:12 UTC*
