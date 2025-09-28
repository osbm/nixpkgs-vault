---
aliases:
  - seaview
tags:
  - license/unknown
  - maintainers/iimog
  - outputs/out
---

# seaview

## 📝 Description

SeaView is a multiplatform, graphical user interface for multiple sequence alignment and molecular phylogeny.
  - SeaView reads and writes various file formats (NEXUS, MSF, CLUSTAL, FASTA, PHYLIP, MASE, Newick) of DNA and protein sequences and of phylogenetic trees.
  - SeaView drives programs muscle or Clustal Omega for multiple sequence alignment, and also allows to use any external alignment algorithm able to read and write FASTA-formatted files.
  - Seaview drives the Gblocks program to select blocks of evolutionarily conserved sites.
  - SeaView computes phylogenetic trees by
    + parsimony, using PHYLIP's dnapars/protpars algorithm,
    + distance, with NJ or BioNJ algorithms on a variety of evolutionary distances,
    + maximum likelihood, driving program PhyML 3.1.
  - Seaview can use the Transfer Bootstrap Expectation method to compute the bootstrap support of PhyML and distance trees.
  - SeaView prints and draws phylogenetic trees on screen, SVG, PDF or PostScript files.
  - SeaView allows to download sequences from EMBL/GenBank/UniProt using the Internet.

Seaview is published in:

    Gouy M., Guindon S. & Gascuel O. (2010) SeaView version 4 : a multiplatform graphical user interface for sequence alignment and phylogenetic tree building. Molecular Biology and Evolution 27(2):221-224.


## 📋 Package Information

- **Name**: `seaview`
- **Version**: `5.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GUI for molecular phylogeny
- **Homepage**: [https://doua.prabi.fr/software/seaview](https://doua.prabi.fr/software/seaview)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @iimog


## 🔧 Build Information

- **Derivation Path**: `/nix/store/jdyr8grl7sjs79glv22xj56bq6iypcv1-seaview-5.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/se/seaview/package.nix:28`
- **Outputs**:
  - `out`:  `/nix/store/jdyr8grl7sjs79glv22xj56bq6iypcv1-seaview-5.1`

## 🔗 Dependencies

- [[2sgql247rkyqmnad6gl3pwmq6gsy13wz-libjpeg-turbo-3.1.1]]
- [[321qil4pzf94jqms95y6cvgfh279kncx-fltk-1.3.8]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i1jal4y3iy6sm4d3g20lwkq53ynay4zj-seaview_5.1.tar.gz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:04:32 UTC*
