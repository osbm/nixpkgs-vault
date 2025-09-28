---
aliases:
  - landrun
tags:
  - license/unknown
  - maintainers/FliegendeWurst
  - outputs/out
---

# landrun

## 📝 Description

Landrun is designed to make it practical to sandbox any command with fine-grained filesystem
and network access controls, without root/containers/SELinux/AppArmor.

It's lightweight, auditable, and wraps Landlock v5 features.

Linux 5.13+ is required for file access restrictions, Linux 6.7+ for TCP restrictions.


## 📋 Package Information

- **Name**: `landrun`
- **Version**: `0.1.15`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Lightweight, secure sandbox for running Linux processes using Landlock LSM
- **Homepage**: [https://github.com/Zouuup/landrun](https://github.com/Zouuup/landrun)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @FliegendeWurst


## 🔧 Build Information

- **Derivation Path**: `/nix/store/v9ylp84hv7xqiq5ma9q9d9b4nsys8ay1-landrun-0.1.15.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/la/landrun/package.nix:94`
- **Outputs**:
  - `out`:  `/nix/store/v9ylp84hv7xqiq5ma9q9d9b4nsys8ay1-landrun-0.1.15`

## 🔗 Dependencies

- [[4f9j67x7cgs2hzjgyyzm8q6z1w2vgy41-which-2.23]]
- [[an9ahk4rhjm2hwxgbmsrjr45dmfjg1fr-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lzvy25g887aypn07ah8igv72z7b9jb88-version-check-hook]]
- [[n26pksss3yyq8h779y7aq23c42rgicjs-landrun-0.1.15-go-modules]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:12:32 UTC*
