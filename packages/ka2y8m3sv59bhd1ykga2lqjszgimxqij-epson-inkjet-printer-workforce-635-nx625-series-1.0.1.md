---
aliases:
  - epson-workforce-635-nx625-series
tags:
  - not-available
  - license/unknown
  - maintainers/jorsn
  - outputs/out
---

# epson-workforce-635-nx625-series

## 📝 Description

This software is a filter program used with Common UNIX Printing
System (CUPS) from the Linux. This can supply the high quality print
with Seiko Epson Color Ink Jet Printers.

This printer driver is supporting the following printers.

WorkForce 60
WorkForce 625
WorkForce 630
WorkForce 633
WorkForce 635
WorkForce T42WD
Epson Stylus NX625
Epson Stylus SX525WD
Epson Stylus SX620FW
Epson Stylus TX560WD
Epson Stylus Office B42WD
Epson Stylus Office BX525WD
Epson Stylus Office BX625FWD
Epson Stylus Office TX620FWD
Epson ME OFFICE 82WD
Epson ME OFFICE 85ND
Epson ME OFFICE 900WD
Epson ME OFFICE 960FWD

License: LGPL and SEIKO EPSON CORPORATION SOFTWARE LICENSE AGREEMENT

To use the driver adjust your configuration.nix file:
  services.printing = {
    enable = true;
    drivers = [ pkgs.epson-inkjet-printer-workforce-635-nx625-series ];
  };


## 📋 Package Information

- **Name**: `epson-workforce-635-nx625-series`
- **Version**: `635-nx625-series-1.0.1`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Proprietary CUPS drivers for Epson inkjet printers
- **License**: `unknown`
- **Platforms**: `x86_64-linux`, `i686-linux`
## 👥 Maintainers

- @jorsn


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ka2y8m3sv59bhd1ykga2lqjszgimxqij-epson-inkjet-printer-workforce-635-nx625-series-1.0.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ep/epson-workforce-635-nx625-series/package.nix:83`
- **Outputs**:
  - `out`:  `/nix/store/ka2y8m3sv59bhd1ykga2lqjszgimxqij-epson-inkjet-printer-workforce-635-nx625-series-1.0.1`

## 🔗 Dependencies

- [[0krsp6pqh3n7p2lmpd78dcpgjq0gc5ml-epson-inkjet-printer-workforce-635-nx625-series-1.0.1-1lsb3.2.src.rpm]]
- [[1jgyc8pm0h5lnk0imm0bs3fhshis2hr2-cups-2.4.12]]
- [[2sgql247rkyqmnad6gl3pwmq6gsy13wz-libjpeg-turbo-3.1.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[firr4sihmlq9b4kdgi2bpw3pdgygllc3-rpmextract]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/gjir2csj1bgbwg070b6rrjnrh7jplrrs-include-raster-helper.patch`
- `/nix/store/gscxfmrrjynmwcma8dbbfv928rcsw7vb-eps_raster_print-cast.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:53 UTC*
