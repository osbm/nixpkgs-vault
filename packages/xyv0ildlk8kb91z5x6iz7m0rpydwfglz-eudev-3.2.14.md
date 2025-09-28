---
aliases:
  - eudev
tags:
  - license/unknown
  - maintainers/7c6f434c
  - outputs/out
---

# eudev

## 📝 Description

eudev is a standalone dynamic and persistent device naming support (aka
userspace devfs) daemon that runs independently from the init
system. eudev strives to remain init system and linux distribution
neutral. It is currently used as the devfs manager for more than a dozen
different linux distributions.

This git repo is a fork of systemd repository with the aim of isolating
udev from any particular flavor of system initialization. In this case,
the isolation is from systemd.

This is a project started by Gentoo developers and testing was initially
being done mostly on OpenRC. We welcome contribution from others using a
variety of system initializations to ensure eudev remains system
initialization and distribution neutral. On 2021-08-20 Gentoo decided to
abandon eudev and a new project was established on 2021-09-14 by Alpine,
Devuan and Gentoo contributors.


## 📋 Package Information

- **Name**: `eudev`
- **Version**: `3.2.14`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Fork of udev with the aim of isolating it from init
- **Homepage**: [https://github.com/eudev-project/eudev](https://github.com/eudev-project/eudev)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @7c6f434c


## 🔧 Build Information

- **Derivation Path**: `/nix/store/xyv0ildlk8kb91z5x6iz7m0rpydwfglz-eudev-3.2.14.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/eu/eudev/package.nix:67`
- **Outputs**:
  - `out`:  `/nix/store/xyv0ildlk8kb91z5x6iz7m0rpydwfglz-eudev-3.2.14`

## 🔗 Dependencies

- [[3z6dcp2i69nn7h8kwl6snf651i7ds14v-util-linux-minimal-2.41.1]]
- [[agnkcpgsw63ima1rywjanh2pqz1zpl18-gperf-3.3]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[gk8r02qyri924h5lxfyrxnypfkz8l29m-source]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qmg0h7ddbh8r5iissdh538jgwx5xi189-kmod-31]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:54:27 UTC*
