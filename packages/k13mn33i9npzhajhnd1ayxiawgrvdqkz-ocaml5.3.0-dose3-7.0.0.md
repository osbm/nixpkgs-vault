---
aliases:
  - ocamlPackages.dose3
tags:
  - license/unknown
  - outputs/out
---

# ocamlPackages.dose3

## 📝 Description

The dose suite provides libraries for handling package meta-data, and various tools for analyzing package relationships in a large package repository.
* dose-builddebcheck checks, given a collection of source package stanzas and a collection of binary package stanzas of Debian packages, whether the build-dependencies of each source package can be satisfied by the binary packages.
* dose-distcheck checks for every package of a distribution whether it is possible to satisfy its dependencies and conflicts within this distribution.
* ceve, a general metadata parser supporting different input formats (Debian, rpm, and others) and different output formats.
* dose-outdated, a Debian-specific tool for finding packages that are not installable with respect to a package repository, and that can only be made installable again by fixing the package itself.
* dose-challenged, a Debian-specific tool for checking which packages will certainly become uninstallable when some existing package is upgraded to a newer version.
* dose-deb-coinstall, a Debian-specific tool for checking whether a set of packages can be installed all together.


## 📋 Package Information

- **Name**: `ocamlPackages.dose3`
- **Version**: `7.0.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Dose library (part of Mancoosi tools)
- **Homepage**: [https://www.mancoosi.org/software/](https://www.mancoosi.org/software/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/k13mn33i9npzhajhnd1ayxiawgrvdqkz-ocaml5.3.0-dose3-7.0.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/ocaml-modules/dose3/default.nix:49`
- **Outputs**:
  - `out`:  `/nix/store/k13mn33i9npzhajhnd1ayxiawgrvdqkz-ocaml5.3.0-dose3-7.0.0`

## 🔗 Dependencies

- [[6l4yldd2ids0ml6r14jf936hsg0bg7ka-ocaml5.3.0-base64-3.5.1]]
- [[7n9csc170zcqrsnf39mgkh2yq8s13lbd-ocaml5.3.0-stdlib-shims-0.3.0]]
- [[8wxqryixd3lg2b4k9grj1j7rsww4k917-source]]
- [[apbdckgdvy1fmhlmq0zqisi76ld55k6m-ocaml5.3.0-re-1.12.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[f2rp017pmmjxa1m2nja7kp6yqzzi1p5h-ocaml5.3.0-parmap-1.2.5]]
- [[fh56gnpzvq2dwfqkj0fy4i33k837afi3-ocaml5.3.0-cudf-0.10]]
- [[gxa8w9bfclgr5nzq5cckrp4m470sh85q-ocaml5.3.0-extlib-1.8.0]]
- [[hvj99gxd587y6qpvmlvggb37jl1jkd6d-ocaml-5.3.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[v7frpbpy8hkmji5gb4ak2mr2g4d3jm1d-dune-3.20.2]]
- [[y0q4bnn3nmpj5xrz6wlw2cqn1v7sbypb-ocaml5.3.0-ocamlgraph-2.2.0]]
- [[y4p2cj0lr29dsczxm3024pgp6f4mrjp0-ocaml5.3.0-findlib-1.9.8]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:41:08 UTC*
