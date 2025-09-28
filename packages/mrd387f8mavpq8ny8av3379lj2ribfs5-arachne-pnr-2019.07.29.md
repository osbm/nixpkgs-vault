---
aliases:
  - arachne-pnr
tags:
  - license/unknown
  - maintainers/VShell
  - maintainers/thoughtpolice
  - outputs/out
---

# arachne-pnr

## 📝 Description

Arachne-pnr implements the place and route step of
the hardware compilation process for FPGAs. It
accepts as input a technology-mapped netlist in BLIF
format, as output by the Yosys [0] synthesis suite
for example. It currently targets the Lattice
Semiconductor iCE40 family of FPGAs [1]. Its output
is a textual bitstream representation for assembly by
the IceStorm [2] icepack command.


## 📋 Package Information

- **Name**: `arachne-pnr`
- **Version**: `2019.07.29`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Place and route tool for FPGAs
- **Homepage**: [https://github.com/cseed/arachne-pnr](https://github.com/cseed/arachne-pnr)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @VShell
- @thoughtpolice


## 🔧 Build Information

- **Derivation Path**: `/nix/store/mrd387f8mavpq8ny8av3379lj2ribfs5-arachne-pnr-2019.07.29.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ar/arachne-pnr/package.nix:31`
- **Outputs**:
  - `out`:  `/nix/store/mrd387f8mavpq8ny8av3379lj2ribfs5-arachne-pnr-2019.07.29`

## 🔗 Dependencies

- [[60sv6ri8jn2l995rkvddmxhsqqk5l0f2-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[wzh8cg4llzmqjxmv445wcih017a330l0-icestorm-0-unstable-2025-06-03]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:12 UTC*
