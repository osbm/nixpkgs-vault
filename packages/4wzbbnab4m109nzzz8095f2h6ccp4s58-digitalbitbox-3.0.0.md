---
aliases:
  - digitalbitbox
tags:
  - license/unknown
  - maintainers/vidbina
  - outputs/out
---

# digitalbitbox

## 📝 Description

Digital Bitbox provides dbb-app, a GUI tool, and dbb-cli, a CLI tool, to manage Digital Bitbox devices.

This package will only install the dbb-app and dbb-cli, however; in order for these applications to identify and access Digital Bitbox devices, one may want to enable the digitalbitbox hardware module by adding

    hardware.digitalbitbox.enable = true;

to the configuration which is equivalent to adding this package to the udev.packages list.


The easiest way to use the digitalbitbox package in NixOS is by adding

    programs.digitalbitbox.enable = true;

to the configuration which installs the package and enables the hardware module.


## 📋 Package Information

- **Name**: `digitalbitbox`
- **Version**: `3.0.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: QT based application for the Digital Bitbox hardware wallet
- **Homepage**: [https://digitalbitbox.com/](https://digitalbitbox.com/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @vidbina


## 🔧 Build Information

- **Derivation Path**: `/nix/store/4wzbbnab4m109nzzz8095f2h6ccp4s58-digitalbitbox-3.0.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/applications/misc/digitalbitbox/default.nix:134`
- **Outputs**:
  - `out`:  `/nix/store/4wzbbnab4m109nzzz8095f2h6ccp4s58-digitalbitbox-3.0.0`

## 🔗 Dependencies

- [[02nvbmkaqzxp5jbnl7i1rcsj85r5cl5p-udev-check-hook]]
- [[0dyaxjhz2kj25fissh5yj32khwz8crrz-qtbase-5.15.17]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[3zc6j1j1qgis43ig9m9gl11iqf058s76-systemd-minimal-libs-257.8]]
- [[4dhrk0y3h7f7qgs499ma30zl4y704ij6-qttools-5.15.17]]
- [[5rwg0dlg4lq9809ajkv47f38agvgvjbn-qrencode-4.1.1]]
- [[6k5v3k5j9m986s15g5l619rsgnc07i2z-source]]
- [[83rwnisjn55y5bkxvp0z7wgp1cha3kx0-52-hid-digitalbox.rules]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[fy9wjrqf0pzd5x3rvy665v50ff747wfd-libusb-1.0.29]]
- [[g1smgp5dhq2ii8np7vm7n5znki3ak1b1-curl-8.14.1]]
- [[gnxpxzfajq6f469akx81ws3c8b3c0v43-libevent-2.1.12]]
- [[kfa7nxsgpl83w2drqsgy524482xabr30-51-hid-digitalbox.rules]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[r2db2qh3wxwmqd0615pzcixjcirgvj12-wrap-qt5-apps-hook]]
- [[sv8lxxb30bqw2b360ni6rsp89mg2dvbp-libtool-2.5.4]]
- [[x1xya2lazfrix7szh16rl2699hsmpgqb-qtwebsockets-5.15.17]]
- [[xpy9pxxcdadsj0vnvqnkfq5sd77r04jg-qtmultimedia-5.15.17]]
- [[yyw6nzfcdckb36blm5mf5b5mss1m9asq-git-2.51.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:45:28 UTC*
