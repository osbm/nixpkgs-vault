---
aliases:
  - epson-201106w
tags:
  - not-available
  - license/unknown
  - maintainers/nphilou
  - outputs/out
---

# epson-201106w

## 📝 Description

This software is a filter program used with the Common UNIX Printing
System (CUPS) under Linux. It supplies high quality printing with
Seiko Epson Color Ink Jet Printers.
List of printers supported by this package:
  Epson BX535WD Series
  Epson BX630FW Series
  Epson BX635FWD Series
  Epson ME940FW Series
  Epson NX530 Series
  Epson SX535WD Series
  Epson WorkForce 545 Series
  Epson WorkForce 645 Series
To use the driver adjust your configuration.nix file:
  services.printing = {
    enable = true;
    drivers = [ pkgs.epson-201106w ];
  };


## 📋 Package Information

- **Name**: `epson-201106w`
- **Version**: `201106w-1.0.1`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Epson printer driver (BX535WD, BX630FW, BX635FWD, ME940FW, NX530, NX635, NX635, SX535WD, WorkForce 545, WorkForce 645
- **Homepage**: [https://www.openprinting.org/driver/epson-201106w](https://www.openprinting.org/driver/epson-201106w)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @nphilou


## 🔧 Build Information

- **Derivation Path**: `/nix/store/h112azbpj69n38cankcybmywxya71r1d-epson-201106w-1.0.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ep/epson-201106w/package.nix:69`
- **Outputs**:
  - `out`:  `/nix/store/h112azbpj69n38cankcybmywxya71r1d-epson-201106w-1.0.1`

## 🔗 Dependencies

- [[1jgyc8pm0h5lnk0imm0bs3fhshis2hr2-cups-2.4.12]]
- [[2sgql247rkyqmnad6gl3pwmq6gsy13wz-libjpeg-turbo-3.1.1]]
- [[a8lks340bd5pdbnh7cwcq6fmyhrdxsai-file-5.45]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[firr4sihmlq9b4kdgi2bpw3pdgygllc3-rpmextract]]
- [[gjg3r4hnwm2cl22clrhp9ps19123mw8l-epson-inkjet-printer-201106w-1.0.1-1lsb3.2.src.rpm]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:45 UTC*
