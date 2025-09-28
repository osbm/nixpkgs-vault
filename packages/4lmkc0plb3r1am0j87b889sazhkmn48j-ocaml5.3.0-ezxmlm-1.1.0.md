---
aliases:
  - ocamlPackages.ezxmlm
tags:
  - license/unknown
  - maintainers/carlosdagos
  - outputs/out
---

# ocamlPackages.ezxmlm

## 📝 Description

An "easy" interface on top of the xmlm library. This version provides
more convenient (but far less flexible) input and output functions
that go to and from [string] values. This avoids the need to write signal
code, which is useful for quick scripts that manipulate XML.

More advanced users should go straight to the Xmlm library and use it
directly, rather than be saddled with the Ezxmlm interface. Since the
types in this library are more specific than Xmlm, it should interoperate
just fine with it if you decide to switch over.


## 📋 Package Information

- **Name**: `ocamlPackages.ezxmlm`
- **Version**: `1.1.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Combinators to use with xmlm for parsing and selection
- **Homepage**: [https://github.com/mirage/ezxmlm/](https://github.com/mirage/ezxmlm/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`
## 👥 Maintainers

- @carlosdagos


## 🔧 Build Information

- **Derivation Path**: `/nix/store/4lmkc0plb3r1am0j87b889sazhkmn48j-ocaml5.3.0-ezxmlm-1.1.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/ocaml-modules/ezxmlm/default.nix:22`
- **Outputs**:
  - `out`:  `/nix/store/4lmkc0plb3r1am0j87b889sazhkmn48j-ocaml5.3.0-ezxmlm-1.1.0`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[c9cyhzxfrxdv5pvmxf84y2rqzz0vw71j-ezxmlm-v1.1.0.tbz]]
- [[hvj99gxd587y6qpvmlvggb37jl1jkd6d-ocaml-5.3.0]]
- [[ib05zpfprvqs9q6ir6sy4cpvm7g76x96-ocaml5.3.0-xmlm-1.4.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[v7frpbpy8hkmji5gb4ak2mr2g4d3jm1d-dune-3.20.2]]
- [[y4p2cj0lr29dsczxm3024pgp6f4mrjp0-ocaml5.3.0-findlib-1.9.8]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:41:32 UTC*
