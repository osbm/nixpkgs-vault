---
aliases:
  - ocamlPackages.easy-format
tags:
  - license/unknown
  - maintainers/vbgl
  - outputs/out
---

# ocamlPackages.easy-format

## 📝 Description

This module offers a high-level and functional interface to the Format module of
the OCaml standard library. It is a pretty-printing facility, i.e. it takes as
input some code represented as a tree and formats this code into the most
visually satisfying result, breaking and indenting lines of code where
appropriate.

Input data must be first modelled and converted into a tree using 3 kinds of
nodes:

* atoms
* lists
* labelled nodes

Atoms represent any text that is guaranteed to be printed as-is. Lists can model
any sequence of items such as arrays of data or lists of definitions that are
labelled with something like "int main", "let x =" or "x:".


## 📋 Package Information

- **Name**: `ocamlPackages.easy-format`
- **Version**: `1.3.4`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: High-level and functional interface to the Format module of the OCaml standard library
- **Homepage**: [https://github.com/ocaml-community/easy-format](https://github.com/ocaml-community/easy-format)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`
## 👥 Maintainers

- @vbgl


## 🔧 Build Information

- **Derivation Path**: `/nix/store/kf9dn2yvgwr7qp882pzcp219hnbpg6kz-ocaml5.3.0-easy-format-1.3.4.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/ocaml-modules/easy-format/default.nix:34`
- **Outputs**:
  - `out`:  `/nix/store/kf9dn2yvgwr7qp882pzcp219hnbpg6kz-ocaml5.3.0-easy-format-1.3.4`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[hvj99gxd587y6qpvmlvggb37jl1jkd6d-ocaml-5.3.0]]
- [[jvca0wbn0pqk0x06k99zi6hjv6xd4dk3-easy-format-1.3.4.tbz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[v7frpbpy8hkmji5gb4ak2mr2g4d3jm1d-dune-3.20.2]]
- [[y4p2cj0lr29dsczxm3024pgp6f4mrjp0-ocaml5.3.0-findlib-1.9.8]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:41:19 UTC*
