---
aliases:
  - ocamlPackages.bigstringaf
tags:
  - license/unknown
  - maintainers/vbgl
  - outputs/out
---

# ocamlPackages.bigstringaf

## 📝 Description

Bigstring intrinsics and fast blits based on memcpy/memmove

The OCaml compiler has a bunch of intrinsics for Bigstrings, but they're not
widely-known, sometimes misused, and so programs that use Bigstrings are slower
than they have to be. And even if a library got that part right and exposed the
intrinsics properly, the compiler doesn't have any fast blits between
Bigstrings and other string-like types.

So here they are. Go crazy.


## 📋 Package Information

- **Name**: `ocamlPackages.bigstringaf`
- **Version**: `0.10.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Bigstring intrinsics and fast blits based on memcpy/memmove
- **Homepage**: [https://github.com/inhabitedtype/bigstringaf](https://github.com/inhabitedtype/bigstringaf)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`
## 👥 Maintainers

- @vbgl


## 🔧 Build Information

- **Derivation Path**: `/nix/store/b6a7lrff5ynkbyl5yjnvd7ll9iv87s0f-ocaml5.3.0-bigstringaf-0.10.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/ocaml-modules/bigstringaf/default.nix:30`
- **Outputs**:
  - `out`:  `/nix/store/b6a7lrff5ynkbyl5yjnvd7ll9iv87s0f-ocaml5.3.0-bigstringaf-0.10.0`

## 🔗 Dependencies

- [[6vm43r3rqag7hwkk66p0rafza8kir20i-ocaml5.3.0-dune-configurator-3.20.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[hvj99gxd587y6qpvmlvggb37jl1jkd6d-ocaml-5.3.0]]
- [[kfppfax6mj5x2x32wzl5vpg2zwxl1f8k-source]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[naf4287am6ya73nh5s3h9155rjswvgj1-ocaml5.3.0-alcotest-1.9.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[v7frpbpy8hkmji5gb4ak2mr2g4d3jm1d-dune-3.20.2]]
- [[y4p2cj0lr29dsczxm3024pgp6f4mrjp0-ocaml5.3.0-findlib-1.9.8]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:33:08 UTC*
