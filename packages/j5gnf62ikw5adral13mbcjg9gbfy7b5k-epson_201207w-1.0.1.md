---
aliases:
  - epson_201207w
tags:
  - not-available
  - license/unknown
  - maintainers/romildo
  - outputs/out
---

# epson_201207w

## 📝 Description

This software is a filter program used with the Common UNIX Printing
System (CUPS) under Linux. It supplies high quality printing with
Seiko Epson Color Ink Jet Printers.

List of printers supported by this package:
   Epson L110 Series
   Epson L210 Series
   Epson L300 Series
   Epson L350 Series
   Epson L355 Series
   Epson L550 Series
   Epson L555 Series

To use the driver adjust your configuration.nix file:
  services.printing = {
    enable = true;
    drivers = [ pkgs.epson_201207w ];
  };


## 📋 Package Information

- **Name**: `epson_201207w`
- **Version**: `1.0.1`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Epson printer driver (L110, L210, L300, L350, L355, L550, L555)
- **Homepage**: [https://www.openprinting.org/driver/epson-201207w](https://www.openprinting.org/driver/epson-201207w)
- **License**: `unknown`
- **Platforms**: `x86_64-linux`
## 👥 Maintainers

- @romildo


## 🔧 Build Information

- **Derivation Path**: `/nix/store/j5gnf62ikw5adral13mbcjg9gbfy7b5k-epson_201207w-1.0.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ep/epson_201207w/package.nix:68`
- **Outputs**:
  - `out`:  `/nix/store/j5gnf62ikw5adral13mbcjg9gbfy7b5k-epson_201207w-1.0.1`

## 🔗 Dependencies

- [[1jgyc8pm0h5lnk0imm0bs3fhshis2hr2-cups-2.4.12]]
- [[2sgql247rkyqmnad6gl3pwmq6gsy13wz-libjpeg-turbo-3.1.1]]
- [[a8lks340bd5pdbnh7cwcq6fmyhrdxsai-file-5.45]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[firr4sihmlq9b4kdgi2bpw3pdgygllc3-rpmextract]]
- [[nqjz7kf1siwwp3clz5zfspcdw94js2k4-epson-inkjet-printer-201207w-1.0.1-1.src.rpm]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:54 UTC*
