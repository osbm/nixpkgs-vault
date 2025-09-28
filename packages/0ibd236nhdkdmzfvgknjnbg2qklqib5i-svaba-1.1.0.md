---
aliases:
  - svaba
tags:
  - license/unknown
  - maintainers/scalavision
  - outputs/out
---

# svaba

## 📝 Description

SvABA is a method for detecting structural variants in sequencing data
using genome-wide local assembly. Under the hood, SvABA uses a custom
implementation of SGA (String Graph Assembler) by Jared Simpson,
and BWA-MEM by Heng Li. Contigs are assembled for every 25kb window
(with some small overlap) for every region in the genome.
The default is to use only clipped, discordant, unmapped and indel reads,
although this can be customized to any set of reads at the command line using VariantBam rules.
These contigs are then immediately aligned to the reference with BWA-MEM and parsed to identify variants.
Sequencing reads are then realigned to the contigs with BWA-MEM, and variants are scored by their read support.


## 📋 Package Information

- **Name**: `svaba`
- **Version**: `1.1.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Structural variant and INDEL caller for DNA sequencing data, using genome-wide local assembly
- **Homepage**: [https://github.com/walaj/svaba](https://github.com/walaj/svaba)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @scalavision


## 🔧 Build Information

- **Derivation Path**: `/nix/store/0ibd236nhdkdmzfvgknjnbg2qklqib5i-svaba-1.1.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sv/svaba/package.nix:49`
- **Outputs**:
  - `out`:  `/nix/store/0ibd236nhdkdmzfvgknjnbg2qklqib5i-svaba-1.1.0`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gy08i4sww306fkvp1wraykc6pch0w8z5-source]]
- [[iw7i7rklrzsglv5l2p8am46y9xa92s8r-xz-5.8.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[y4lfwlviqzkdrk9973a02vpl0fk4h1vy-bzip2-1.0.8]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:58:08 UTC*
