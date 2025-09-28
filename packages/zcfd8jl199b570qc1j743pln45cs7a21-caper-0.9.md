---
aliases:
  - caper
tags:
  - license/unknown
  - maintainers/spaghetus
  - outputs/out
---

# caper

## 📝 Description

Caper is a tool for understanding and processing "pcap expressions" (also known as *tcpdump filters*) which are used for network packet analysis.
Caper can be used for:
* Expanding out pcap expressions "in full" to understand their implicit features.
* Reasoning about whether two expressions accept the same set of packets, or how their accepted packets differ.
* Converting pcap expressions into BPF programs.
* Converting between pcap expressions and English.

More info can be found in the Caper paper (https://www.nik.network/caper/pcap_semantics.pdf).


## 📋 Package Information

- **Name**: `caper`
- **Version**: `0.9`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tool for understanding and processing pcap (packet capture) expressions
- **Homepage**: [https://gitlab.com/niksu/caper](https://gitlab.com/niksu/caper)
- **License**: `unknown`
## 👥 Maintainers

- @spaghetus


## 🔧 Build Information

- **Derivation Path**: `/nix/store/zcfd8jl199b570qc1j743pln45cs7a21-caper-0.9.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ca/caper/package.nix:48`
- **Outputs**:
  - `out`:  `/nix/store/zcfd8jl199b570qc1j743pln45cs7a21-caper-0.9`

## 🔗 Dependencies

- [[bc3xjf3jghq6mrl4kqs96db9zmfmwxbl-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[hvj99gxd587y6qpvmlvggb37jl1jkd6d-ocaml-5.3.0]]
- [[kc7x047h7wli7z26dfi9zvmfb9v8mbyg-ocaml5.3.0-menhir-20250903]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[ra0s4s8yqgg2mz68yk0kkpplrvmg61w8-ocaml5.3.0-angstrom-0.16.1]]
- [[sp2vq01660i7gmsgddk4x9di14gwny4m-gnum4-1.4.20]]
- [[y4p2cj0lr29dsczxm3024pgp6f4mrjp0-ocaml5.3.0-findlib-1.9.8]]
- [[yfyxdiq0rxyr5hqgpwpizsfgd09hbhmg-ocaml5.3.0-ocamlbuild-0.16.1]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:52 UTC*
