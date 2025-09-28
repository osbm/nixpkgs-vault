---
aliases:
  - deheader
tags:
  - license/unknown
  - maintainers/KAction
  - outputs/man
  - outputs/out
---

# deheader

## 📝 Description

This tool takes a list of C or C++ sourcefiles and generates a report
on which #includes can be omitted from them -- the test, for each foo.c
or foo.cc or foo.cpp, is simply whether 'rm foo.o; make foo.o' returns a
zero status. Optionally, with the -r option, the unneeded headers are removed.
The tool also reports on headers required for strict portability.


## 📋 Package Information

- **Name**: `deheader`
- **Version**: `1.11`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tool to find and optionally remove unneeded includes in C or C++ source files
- **Homepage**: [http://catb.org/~esr/deheader](http://catb.org/~esr/deheader)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @KAction


## 🔧 Build Information

- **Derivation Path**: `/nix/store/99a9pb0733a6ad35ly7vy9bn722p3i19-deheader-1.11.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/de/deheader/package.nix:61`
- **Outputs**:
  - `man`:  `/nix/store/99a9pb0733a6ad35ly7vy9bn722p3i19-deheader-1.11`
  - `out`:  `/nix/store/99a9pb0733a6ad35ly7vy9bn722p3i19-deheader-1.11`

## 🔗 Dependencies

- [[04sxd1ncbv87d14flich8a6g06jbyw6c-docbook-xsl-nons-1.79.2]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[8laqbfxggzzw0rbk8gipcpdjx482va0z-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]
- [[zplsmx347bxzf7lb50gzykw5fsqfd5yj-xmlto-0.0.29]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:41:54 UTC*
