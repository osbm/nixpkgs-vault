---
aliases:
  - earlyoom
tags:
  - license/unknown
  - maintainers/oxalica
  - outputs/man
  - outputs/out
---

# earlyoom

## 📝 Description

earlyoom checks the amount of available memory and free swap up to 10
times a second (less often if there is a lot of free memory). By default
if both are below 10%, it will kill the largest process (highest
oom_score). The percentage value is configurable via command line
arguments.


## 📋 Package Information

- **Name**: `earlyoom`
- **Version**: `1.8.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Early OOM Daemon for Linux
- **Homepage**: [https://github.com/rfjakob/earlyoom](https://github.com/rfjakob/earlyoom)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @oxalica


## 🔧 Build Information

- **Derivation Path**: `/nix/store/0yc843ijr2q5jim4bh1iq0m2s7mkqsqc-earlyoom-1.8.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ea/earlyoom/package.nix:55`
- **Outputs**:
  - `man`:  `/nix/store/0yc843ijr2q5jim4bh1iq0m2s7mkqsqc-earlyoom-1.8.2`
  - `out`:  `/nix/store/0yc843ijr2q5jim4bh1iq0m2s7mkqsqc-earlyoom-1.8.2`

## 🔗 Dependencies

- [[2j7nf44qd2563337hhrxnvwwbwbwai1n-source]]
- [[5d3vy6jlsnsz9n7c6584kwjj1cfpz8bm-c5a1799a5ff4b3fd3132d50a510e8c126933cf4a.patch]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lwczx4cah43c9icg0dp0gv3j80ymhg4v-f7d6f1cc925962fbdcf57b1c2aeeabbf11e2d542.patch]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[zb5cj6gmxg0g561dg8vkmb4sb67z2b07-pandoc-cli-3.6]]

## 📁 Input Sources

- `/nix/store/6wlyv460mk48zf07x2plkn20wp0pwf2b-0000-fix-dbus-path.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:55:54 UTC*
