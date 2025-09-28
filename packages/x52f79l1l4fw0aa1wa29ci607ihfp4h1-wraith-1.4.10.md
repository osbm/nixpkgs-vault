---
aliases:
  - wraith
tags:
  - license/unknown
  - maintainers/elitak
  - outputs/out
---

# wraith

## 📝 Description

Wraith is an IRC channel management bot written purely in C/C++. It has
been in development since late 2003. It is based on Eggdrop 1.6.12 but has
since evolved into something much different at its core. TCL and loadable
modules are currently not supported.

Maintainer's Notes:
Copy the binary out of the store before running it with the -C option to
configure it. See https://github.com/wraith/wraith/wiki/GettingStarted .

The binary will not run when moved onto non-NixOS systems; use patchelf
to fix its runtime dependenices.


## 📋 Package Information

- **Name**: `wraith`
- **Version**: `1.4.10`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: IRC channel management bot written purely in C/C++
- **Homepage**: [https://wraith.botpack.net/](https://wraith.botpack.net/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @elitak


## 🔧 Build Information

- **Derivation Path**: `/nix/store/x52f79l1l4fw0aa1wa29ci607ihfp4h1-wraith-1.4.10.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/wr/wraith/package.nix:35`
- **Outputs**:
  - `out`:  `/nix/store/x52f79l1l4fw0aa1wa29ci607ihfp4h1-wraith-1.4.10`

## 🔗 Dependencies

- [[03mlg2iyxmy05ybrpm7v9yajqykk76bq-wraith-v1.4.10.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qp46qaqmxcqy7009d2d6niwd3l1qbcag-openssl-1.1.1w]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/pzms8h7c9zhsa4sp4sa80f3mqkqca4cz-configure.patch`
- `/nix/store/rsln9pgs8rs66l8wm4jzmh1yzyc21ncw-dlopen.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:14:56 UTC*
