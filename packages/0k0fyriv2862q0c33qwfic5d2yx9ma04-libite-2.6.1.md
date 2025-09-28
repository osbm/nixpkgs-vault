---
aliases:
  - libite
tags:
  - license/unknown
  - maintainers/fpletz
  - outputs/out
---

# libite

## 📝 Description

Libite is a lightweight library of frog DNA. It can be used to fill
the gaps in any dinosaur project. It holds useful functions and macros
developed by both Finit and the OpenBSD project. Most notably the
string functions: strlcpy(3), strlcat(3) and the highly useful *BSD
sys/queue.h and sys/tree.h API's.

Libite is the frog DNA missing in GNU libc. However, -lite does not
aim to become another GLIB! One noticeable gap in GLIBC is the missing
_SAFE macros in the BSD sys/queue.h API — highly recommended when
traversing lists to delete/free nodes.


## 📋 Package Information

- **Name**: `libite`
- **Version**: `2.6.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Lightweight library of frog DNA
- **Homepage**: [https://github.com/troglobit/libite](https://github.com/troglobit/libite)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`
## 👥 Maintainers

- @fpletz


## 🔧 Build Information

- **Derivation Path**: `/nix/store/0k0fyriv2862q0c33qwfic5d2yx9ma04-libite-2.6.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libite/package.nix:28`
- **Outputs**:
  - `out`:  `/nix/store/0k0fyriv2862q0c33qwfic5d2yx9ma04-libite-2.6.1`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[fwnwvlgxkx4493py8m9qlxk1z8wiqlzx-libconfuse-3.3]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[lws5dg13g0sybi5c4psm3dqqrgpdgliv-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:47:53 UTC*
