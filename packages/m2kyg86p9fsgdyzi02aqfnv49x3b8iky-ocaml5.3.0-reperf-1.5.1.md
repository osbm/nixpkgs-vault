---
aliases:
  - ocamlPackages.reperf
tags:
  - license/unknown
  - outputs/out
---

# ocamlPackages.reperf

## 📝 Description

Inspired by the core_bench tools from Janestreet.

reperf helps with:
* Timing: time spent in a code block
* Call count: frequency of code-path calls
* Allocations: code-block impact to garbage collector

Supports benchmarks, which are test cases that exercise performance scenarios.
Outputs a JSON performance report, and compare it with previous iterations - and fail if a regression is detected.


## 📋 Package Information

- **Name**: `ocamlPackages.reperf`
- **Version**: `1.5.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Native Reason + JSOO cross-platform performance benchmarking tools
- **Homepage**: [https://github.com/bryphe/reperf](https://github.com/bryphe/reperf)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/m2kyg86p9fsgdyzi02aqfnv49x3b8iky-ocaml5.3.0-reperf-1.5.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/ocaml-modules/reperf/default.nix:31`
- **Outputs**:
  - `out`:  `/nix/store/m2kyg86p9fsgdyzi02aqfnv49x3b8iky-ocaml5.3.0-reperf-1.5.1`

## 🔗 Dependencies

- [[4mcfb6h1dlixn3hbaf55vw44hs98z6ah-ocaml5.3.0-printbox-text-0.12]]
- [[67jyxmd13pbrnssvxzxpjm1229s98n5s-ocaml5.3.0-reason-3.17.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[ghk90r4xkiwkaxi9pwzqq1r582k4hm9i-source]]
- [[hvj99gxd587y6qpvmlvggb37jl1jkd6d-ocaml-5.3.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[v7frpbpy8hkmji5gb4ak2mr2g4d3jm1d-dune-3.20.2]]
- [[y4p2cj0lr29dsczxm3024pgp6f4mrjp0-ocaml5.3.0-findlib-1.9.8]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:47:33 UTC*
