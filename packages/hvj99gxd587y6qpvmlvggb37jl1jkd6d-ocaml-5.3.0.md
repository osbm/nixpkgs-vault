---
aliases:
  - ocaml
tags:
  - license/unknown
  - outputs/out
---

# ocaml

## 📝 Description

OCaml is a general purpose programming language with an emphasis on expressiveness and safety. Developed for more than 20 years at Inria by a group of leading researchers, it has an advanced type system that helps catch your mistakes without getting in your way. It's used in environments where a single mistake can cost millions and speed matters, is supported by an active community, and has a rich set of libraries and development tools. It's widely used in teaching for its power and simplicity.

Strengths:
* A powerful type system, equipped with parametric polymorphism and type inference. For instance, the type of a collection can be parameterized by the type of its elements. This allows defining some operations over a collection independently of the type of its elements: sorting an array is one example. Furthermore, type inference allows defining such operations without having to explicitly provide the type of their parameters and result.
* User-definable algebraic data types and pattern-matching. New algebraic data types can be defined as combinations of records and sums. Functions that operate over such data structures can then be defined by pattern matching, a generalized form of the well-known switch statement, which offers a clean and elegant way of simultaneously examining and naming data.
* Automatic memory management, thanks to a fast, unobtrusive, incremental garbage collector.
* Separate compilation of standalone applications. Portable bytecode compilers allow creating stand-alone applications out of Caml Light or OCaml programs. A foreign function interface allows OCaml code to interoperate with C code when necessary. Interactive use of OCaml is also supported via a “read-evaluate-print” loop.

In addition, OCaml features:
* A sophisticated module system, which allows organizing modules hierarchically and parameterizing a module over a number of other modules.
* An expressive object-oriented layer, featuring multiple inheritance, parametric and virtual classes.
* Efficient native code compilers. In addition to its bytecode compiler, OCaml offers a compiler that produces efficient machine code for many architectures.

Learn more at: https://ocaml.org/learn/description.html


## 📋 Package Information

- **Name**: `ocaml`
- **Version**: `5.3.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: OCaml is an industrial-strength programming language supporting functional, imperative and object-oriented styles
- **Homepage**: [https://ocaml.org/](https://ocaml.org/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/hvj99gxd587y6qpvmlvggb37jl1jkd6d-ocaml-5.3.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/compilers/ocaml/generic.nix:200`
- **Outputs**:
  - `out`:  `/nix/store/hvj99gxd587y6qpvmlvggb37jl1jkd6d-ocaml-5.3.0`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bvzxhvj0xbmncj0bfv7bhm7337brxn4y-ocaml-5.3.0.tar.xz]]
- [[kvysay8plzjaxgvj64sxz0b4d9xc25n0-binutils-wrapper-2.44]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/0rawfy9g1y4c2h4s60sjm6m80cri92n3-Makefile.nixpkgs`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:32:30 UTC*
