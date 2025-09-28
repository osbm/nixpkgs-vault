---
aliases:
  - cups-pdf-to-pdf
tags:
  - license/unknown
  - maintainers/Yarny0
  - outputs/out
---

# cups-pdf-to-pdf

## 📝 Description

cups-pdf is a CUPS backend that generates a PDF file for each print job and puts this file
into a folder on the local machine such that the print job's owner can access the file.

https://www.cups-pdf.de/

cups-pdf-to-pdf is a fork of cups-pdf which tries hard to preserve the original text of the print job by avoiding rasterization.

Note that in order to use this package, you have to make sure that the cups-pdf program is called with root privileges.


## 📋 Package Information

- **Name**: `cups-pdf-to-pdf`
- **Version**: `0-unstable-2021-12-22`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: CUPS backend that turns print jobs into searchable PDF files
- **Homepage**: [https://github.com/alexivkin/CUPS-PDF-to-PDF](https://github.com/alexivkin/CUPS-PDF-to-PDF)
- **License**: `unknown`
## 👥 Maintainers

- @Yarny0


## 🔧 Build Information

- **Derivation Path**: `/nix/store/1a37ncfr5s34rygr9lr5dzlhvglwbbhw-cups-pdf-to-pdf-0-unstable-2021-12-22.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/cu/cups-pdf-to-pdf/package.nix:49`
- **Outputs**:
  - `out`:  `/nix/store/1a37ncfr5s34rygr9lr5dzlhvglwbbhw-cups-pdf-to-pdf-0-unstable-2021-12-22`

## 🔗 Dependencies

- [[1jgyc8pm0h5lnk0imm0bs3fhshis2hr2-cups-2.4.12]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[bacmlk82pk3zfsrp0skk10cww8lyl3n0-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:01:48 UTC*
