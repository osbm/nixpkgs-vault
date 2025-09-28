---
aliases:
  - fuse
tags:
  - license/unknown
  - maintainers/oxalica
  - outputs/bin
  - outputs/dev
  - outputs/man
  - outputs/out
---

# fuse

## 📝 Description

FUSE (Filesystem in Userspace) is an interface for userspace programs to
export a filesystem to the Linux kernel. The FUSE project consists of two
components: The fuse kernel module (maintained in the regular kernel
repositories) and the libfuse userspace library (this package). libfuse
provides the reference implementation for communicating with the FUSE
kernel module.


## 📋 Package Information

- **Name**: `fuse`
- **Version**: `2.9.9`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Library that allows filesystems to be implemented in user space
- **Homepage**: [https://github.com/libfuse/libfuse](https://github.com/libfuse/libfuse)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @oxalica


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ji56v9i7bdf14w53nxy71cpr8rrrvmma-fuse-2.9.9.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/fuse/common.nix:127`
- **Outputs**:
  - `bin`:  `/nix/store/ji56v9i7bdf14w53nxy71cpr8rrrvmma-fuse-2.9.9`
  - `dev`:  `/nix/store/ji56v9i7bdf14w53nxy71cpr8rrrvmma-fuse-2.9.9`
  - `man`:  `/nix/store/ji56v9i7bdf14w53nxy71cpr8rrrvmma-fuse-2.9.9`
  - `out`:  `/nix/store/ji56v9i7bdf14w53nxy71cpr8rrrvmma-fuse-2.9.9`

## 🔗 Dependencies

- [[1kk7ncn0524y0k7zdh0w9ryikg89c4wy-fuse-2.9.9-closefrom-glibc-2-34.patch?id=8a970396fca7aca2d5a761b8e7a8242f1eef14c9]]
- [[3z6dcp2i69nn7h8kwl6snf651i7ds14v-util-linux-minimal-2.41.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[m0h8vm7wnxqmzy77yph902p607lx7np5-gettext-0.25.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vqwzd06jj6d8az4087z8170hify77lgb-source]]
- [[xi3qqmwckbj10sva5y329l7x5ydk8k62-shadow-4.18.0]]

## 📁 Input Sources

- `/nix/store/0d0x34svkix4cvjmvhbz2b0f1hbcbcw3-fuse2-gettext-0.25.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/q20d6d6lkd6b58r5ncg5398cn8vr7nqr-fuse2-Do-not-set-FUSERMOUNT_DIR.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:33 UTC*
