---
aliases:
  - libnfnetlink
tags:
  - license/unknown
  - outputs/out
---

# libnfnetlink

## 📝 Description

libnfnetlink is the low-level library for netfilter related kernel/userspace communication.
It provides a generic messaging infrastructure for in-kernel netfilter subsystems
(such as nfnetlink_log, nfnetlink_queue, nfnetlink_conntrack) and their respective users
and/or management tools in userspace.

This library is not meant as a public API for application developers.
It is only used by other netfilter.org projects, like the aforementioned ones.


## 📋 Package Information

- **Name**: `libnfnetlink`
- **Version**: `1.0.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Low-level library for netfilter related kernel/userspace communication
- **Homepage**: [https://www.netfilter.org/projects/libnfnetlink/index.html](https://www.netfilter.org/projects/libnfnetlink/index.html)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/4ikqf2l4p1q7n6qypj454k476ql2h631-libnfnetlink-1.0.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libnfnetlink/package.nix:17`
- **Outputs**:
  - `out`:  `/nix/store/4ikqf2l4p1q7n6qypj454k476ql2h631-libnfnetlink-1.0.2`

## 🔗 Dependencies

- [[9y23njln5v31c3njki46144nbg09xsil-libnfnetlink-1.0.2.tar.bz2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:49:22 UTC*
