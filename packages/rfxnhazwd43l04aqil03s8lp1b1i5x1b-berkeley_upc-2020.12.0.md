---
aliases:
  - bupc
tags:
  - license/unknown
  - maintainers/zimbatm
  - outputs/out
---

# bupc

## 📝 Description

Unified Parallel C (UPC) is an extension of the C programming language
designed for high performance computing on large-scale parallel
machines.The language provides a uniform programming model for both
shared and distributed memory hardware. The programmer is presented with
a single shared, partitioned address space, where variables may be
directly read and written by any processor, but each variable is
physically associated with a single processor. UPC uses a Single Program
Multiple Data (SPMD) model of computation in which the amount of
parallelism is fixed at program startup time, typically with a single
thread of execution per processor.


## 📋 Package Information

- **Name**: `bupc`
- **Version**: `2020.12.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Compiler for the Berkely Unified Parallel C language
- **Homepage**: [https://upc.lbl.gov/](https://upc.lbl.gov/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @zimbatm


## 🔧 Build Information

- **Derivation Path**: `/nix/store/rfxnhazwd43l04aqil03s8lp1b1i5x1b-berkeley_upc-2020.12.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/bu/bupc/package.nix:28`
- **Outputs**:
  - `out`:  `/nix/store/rfxnhazwd43l04aqil03s8lp1b1i5x1b-berkeley_upc-2020.12.0`

## 🔗 Dependencies

- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pk51gvyc0bz7cx3vy1xfdx2w28z4gbla-berkeley_upc-2020.12.0.tar.gz]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:49:52 UTC*
