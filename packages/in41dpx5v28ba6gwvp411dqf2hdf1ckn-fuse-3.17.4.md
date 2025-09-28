---
aliases:
  - fuse3
tags:
  - license/unknown
  - maintainers/oxalica
  - outputs/bin
  - outputs/dev
  - outputs/man
  - outputs/out
  - outputs/udev
---

# fuse3

## 📝 Description

FUSE (Filesystem in Userspace) is an interface for userspace programs to
export a filesystem to the Linux kernel. The FUSE project consists of two
components: The fuse kernel module (maintained in the regular kernel
repositories) and the libfuse userspace library (this package). libfuse
provides the reference implementation for communicating with the FUSE
kernel module.


## 📋 Package Information

- **Name**: `fuse3`
- **Version**: `3.17.4`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Library that allows filesystems to be implemented in user space
- **Homepage**: [https://github.com/libfuse/libfuse](https://github.com/libfuse/libfuse)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @oxalica


## 🔧 Build Information

- **Derivation Path**: `/nix/store/in41dpx5v28ba6gwvp411dqf2hdf1ckn-fuse-3.17.4.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/fuse/common.nix:127`
- **Outputs**:
  - `bin`:  `/nix/store/in41dpx5v28ba6gwvp411dqf2hdf1ckn-fuse-3.17.4`
  - `dev`:  `/nix/store/in41dpx5v28ba6gwvp411dqf2hdf1ckn-fuse-3.17.4`
  - `man`:  `/nix/store/in41dpx5v28ba6gwvp411dqf2hdf1ckn-fuse-3.17.4`
  - `out`:  `/nix/store/in41dpx5v28ba6gwvp411dqf2hdf1ckn-fuse-3.17.4`
  - `udev`:  `/nix/store/in41dpx5v28ba6gwvp411dqf2hdf1ckn-fuse-3.17.4`

## 🔗 Dependencies

- [[02nvbmkaqzxp5jbnl7i1rcsj85r5cl5p-udev-check-hook]]
- [[3z6dcp2i69nn7h8kwl6snf651i7ds14v-util-linux-minimal-2.41.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[sglp8dq778z99lw7bag1la6zdn6r0ihp-source]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]

## 📁 Input Sources

- `/nix/store/arhwafyygxcl2jc2xc6n6ws34rs67v5p-fuse3-install.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/qhq3yqyw4nr9bxdrg9ilax7dk9329p2j-fuse3-Do-not-set-FUSERMOUNT_DIR.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:39 UTC*
