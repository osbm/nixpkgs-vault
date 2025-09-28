---
aliases:
  - passt
tags:
  - license/unknown
  - maintainers/8aed
  - outputs/debug
  - outputs/out
---

# passt

## 📝 Description

passt implements a translation layer between a Layer-2 network interface
and native Layer-4 sockets (TCP, UDP, ICMP/ICMPv6 echo) on a host.
It doesn't require any capabilities or privileges, and it can be used as
a simple replacement for Slirp.

pasta (same binary as passt, different command) offers equivalent
functionality, for network namespaces: traffic is forwarded using a tap
interface inside the namespace, without the need to create further
interfaces on the host, hence not requiring any capabilities or
privileges.


## 📋 Package Information

- **Name**: `passt`
- **Version**: `2025_09_11.6cbcccc`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Plug A Simple Socket Transport
- **Homepage**: [https://passt.top/passt/about/](https://passt.top/passt/about/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @8aed


## 🔧 Build Information

- **Derivation Path**: `/nix/store/0fns0dm0vg51mkyaf61hj1wf4r3pkyk5-passt-2025_09_11.6cbcccc.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/pa/passt/package.nix:47`
- **Outputs**:
  - `debug`:  `/nix/store/0fns0dm0vg51mkyaf61hj1wf4r3pkyk5-passt-2025_09_11.6cbcccc`
  - `out`:  `/nix/store/0fns0dm0vg51mkyaf61hj1wf4r3pkyk5-passt-2025_09_11.6cbcccc`

## 🔗 Dependencies

- [[9cf2m1rr0kbbda01mh3xc6rqaqay41q4-getconf-glibc-2.40-66]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdnaan616jkr3li04lm8bnq82y6apbm7-passt-2025_09_11.6cbcccc.tar.gz]]
- [[jdrn7ca68hbxmxlqldqhf4440r7ff7f1-exec]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/r989dk196nl9frhnfsa1lb7knhbyjxw6-separate-debug-info.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:08:20 UTC*
