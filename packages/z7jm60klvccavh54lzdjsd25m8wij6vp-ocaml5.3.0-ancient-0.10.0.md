---
aliases:
  - ocamlPackages.ancient
tags:
  - license/unknown
  - maintainers/momeemt
  - outputs/out
---

# ocamlPackages.ancient

## 📝 Description

This module allows you to use in-memory data structures which are
larger than available memory and so are kept in swap.  If you try this
in normal OCaml code, you'll find that the machine quickly descends
into thrashing as the garbage collector repeatedly iterates over
swapped memory structures.  This module lets you break that
limitation.  Of course the module doesn't work by magic :-) If your
program tries to access these large structures, they still need to be
swapped back in, but it is suitable for large, sparsely accessed
structures.

Secondly, this module allows you to share those structures between
processes.  In this mode, the structures are backed by a disk file,
and any process that has read/write access that disk file can map that
file in and see the structures.


## 📋 Package Information

- **Name**: `ocamlPackages.ancient`
- **Version**: `0.10.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Use data structures larger than available memory
- **Homepage**: [https://github.com/OCamlPro/ocaml-ancient](https://github.com/OCamlPro/ocaml-ancient)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`
## 👥 Maintainers

- @momeemt


## 🔧 Build Information

- **Derivation Path**: `/nix/store/z7jm60klvccavh54lzdjsd25m8wij6vp-ocaml5.3.0-ancient-0.10.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/ocaml-modules/ancient/default.nix:20`
- **Outputs**:
  - `out`:  `/nix/store/z7jm60klvccavh54lzdjsd25m8wij6vp-ocaml5.3.0-ancient-0.10.0`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[hvj99gxd587y6qpvmlvggb37jl1jkd6d-ocaml-5.3.0]]
- [[j0kcffb7689ggrvkz2kd6xmk0gdahydz-ancient-0.10.0.tbz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[v7frpbpy8hkmji5gb4ak2mr2g4d3jm1d-dune-3.20.2]]
- [[y4p2cj0lr29dsczxm3024pgp6f4mrjp0-ocaml5.3.0-findlib-1.9.8]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:32:39 UTC*
