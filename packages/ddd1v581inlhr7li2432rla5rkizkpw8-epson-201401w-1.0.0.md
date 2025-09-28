---
aliases:
  - epson-201401w
tags:
  - not-available
  - license/unknown
  - maintainers/Lunarequest
  - outputs/out
---

# epson-201401w

## 📝 Description

This software is a filter program used with the Common UNIX Printing
System (CUPS) under Linux. It supplies high quality printing with
Seiko Epson Color Ink Jet Printers.

To use the driver adjust your configuration.nix file:
  services.printing = {
    enable = true;
    drivers = [ pkgs.epson-201401w ];
  };


## 📋 Package Information

- **Name**: `epson-201401w`
- **Version**: `201401w-1.0.0`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Epson printer driver (L456, L455, L366, L365, L362, L360, L312, L310, L222, L220, L132, L130)
- **Homepage**: [https://www.openprinting.org/driver/epson-201401w](https://www.openprinting.org/driver/epson-201401w)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @Lunarequest


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ddd1v581inlhr7li2432rla5rkizkpw8-epson-201401w-1.0.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ep/epson-201401w/package.nix:66`
- **Outputs**:
  - `out`:  `/nix/store/ddd1v581inlhr7li2432rla5rkizkpw8-epson-201401w-1.0.0`

## 🔗 Dependencies

- [[1jgyc8pm0h5lnk0imm0bs3fhshis2hr2-cups-2.4.12]]
- [[2sgql247rkyqmnad6gl3pwmq6gsy13wz-libjpeg-turbo-3.1.1]]
- [[a8lks340bd5pdbnh7cwcq6fmyhrdxsai-file-5.45]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[firr4sihmlq9b4kdgi2bpw3pdgygllc3-rpmextract]]
- [[k9h7cql7s39aza9s5p47c9if17ygyjyl-epson-inkjet-printer-201401w-1.0.0-1lsb3.2.src.rpm]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:46 UTC*
