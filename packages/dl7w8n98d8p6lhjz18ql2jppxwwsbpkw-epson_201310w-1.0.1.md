---
aliases:
  - epson_201310w
tags:
  - not-available
  - license/unknown
  - maintainers/nukdokplex
  - outputs/out
---

# epson_201310w

## 📝 Description

This software is a filter program used with the Common UNIX Printing
System (CUPS) under Linux. It supplies high quality printing with
Seiko Epson L120 series printers.

To use the driver adjust your configuration.nix file:
  services.printing = {
    enable = true;
    drivers = [ pkgs.epson_201310w ];
  };


## 📋 Package Information

- **Name**: `epson_201310w`
- **Version**: `1.0.1`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Epson printer driver for L120 series inkjet printers
- **Homepage**: [https://www.epson.eu/en_EU/support/sc/epson-l120/s/s1346](https://www.epson.eu/en_EU/support/sc/epson-l120/s/s1346)
- **License**: `unknown`
- **Platforms**: `x86_64-linux`
## 👥 Maintainers

- @nukdokplex


## 🔧 Build Information

- **Derivation Path**: `/nix/store/dl7w8n98d8p6lhjz18ql2jppxwwsbpkw-epson_201310w-1.0.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ep/epson_201310w/package.nix:54`
- **Outputs**:
  - `out`:  `/nix/store/dl7w8n98d8p6lhjz18ql2jppxwwsbpkw-epson_201310w-1.0.1`

## 🔗 Dependencies

- [[1jgyc8pm0h5lnk0imm0bs3fhshis2hr2-cups-2.4.12]]
- [[2sgql247rkyqmnad6gl3pwmq6gsy13wz-libjpeg-turbo-3.1.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cahgnvdmbmvpmiwjgmrs7l96z0n6bw36-epson-inkjet-printer-201310w-1.0.1-1.src.rpm]]
- [[firr4sihmlq9b4kdgi2bpw3pdgygllc3-rpmextract]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:55 UTC*
