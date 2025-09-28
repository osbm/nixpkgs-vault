---
aliases:
  - epson-inkjet-printer-workforce-840-series
tags:
  - not-available
  - license/unknown
  - maintainers/heichro
  - outputs/out
---

# epson-inkjet-printer-workforce-840-series

## 📝 Description

This software is a filter program used with the Common UNIX Printing
System (CUPS) under Linux. It supplies high quality printing with
Seiko Epson Color Ink Jet Printers.

This printer driver is supporting the following printers.

Epson Stylus Office BX925
Epson WorkForce 840

To use the driver adjust your configuration.nix file:
```nix
{
  services.printing = {
    enable = true;
    drivers = [ pkgs.epson-inkjet-printer-workforce-840-series ];
  };
}
```


## 📋 Package Information

- **Name**: `epson-inkjet-printer-workforce-840-series`
- **Version**: `840-series-1.0.0`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Proprietary CUPS drivers for Epson inkjet printers
- **License**: `unknown`
- **Platforms**: `x86_64-linux`
## 👥 Maintainers

- @heichro


## 🔧 Build Information

- **Derivation Path**: `/nix/store/2lifqm2hv9l2raxhczhh4jrcqai4lc4w-epson-inkjet-printer-workforce-840-series-1.0.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ep/epson-inkjet-printer-workforce-840-series/package.nix:102`
- **Outputs**:
  - `out`:  `/nix/store/2lifqm2hv9l2raxhczhh4jrcqai4lc4w-epson-inkjet-printer-workforce-840-series-1.0.0`

## 🔗 Dependencies

- [[1jgyc8pm0h5lnk0imm0bs3fhshis2hr2-cups-2.4.12]]
- [[2sgql247rkyqmnad6gl3pwmq6gsy13wz-libjpeg-turbo-3.1.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dy1bsaklgrbdi7i0721nq7k1989ziqsg-epson-inkjet-printer-workforce-840-series-1.0.0-1lsb3.2.src.rpm]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[firr4sihmlq9b4kdgi2bpw3pdgygllc3-rpmextract]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/g13f1ri719ajb9cppg054y515cg6xn9d-include-raster-helper.patch`
- `/nix/store/gscxfmrrjynmwcma8dbbfv928rcsw7vb-eps_raster_print-cast.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:51 UTC*
