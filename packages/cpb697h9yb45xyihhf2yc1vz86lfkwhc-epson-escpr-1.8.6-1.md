---
aliases:
  - epson-escpr
tags:
  - license/unknown
  - outputs/out
---

# epson-escpr

## 📝 Description

Epson Inkjet Printer Driver (ESC/P-R) for Linux and the
corresponding PPD files. The list of supported printers
can be found at http://www.openprinting.org/driver/epson-escpr/ .

To use the driver adjust your configuration.nix file:
  services.printing = {
    enable = true;
    drivers = [ pkgs.epson-escpr ];
  };

To setup a wireless printer, enable Avahi which provides
printer's hostname to CUPS and nss-mdns to make this
hostname resolvable:
  services.avahi = {
    enable = true;
    nssmdns4 = true;
  };

## 📋 Package Information

- **Name**: `epson-escpr`
- **Version**: `1.8.6-1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: ESC/P-R Driver (generic driver)
- **Homepage**: [http://download.ebz.epson.net/dsc/search/01/search/](http://download.ebz.epson.net/dsc/search/01/search/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/cpb697h9yb45xyihhf2yc1vz86lfkwhc-epson-escpr-1.8.6-1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ep/epson-escpr/package.nix:56`
- **Outputs**:
  - `out`:  `/nix/store/cpb697h9yb45xyihhf2yc1vz86lfkwhc-epson-escpr-1.8.6-1`

## 🔗 Dependencies

- [[1jgyc8pm0h5lnk0imm0bs3fhshis2hr2-cups-2.4.12]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cwl2gmzg2rgp027dd0j4894b0r3ckbk7-epson-inkjet-printer-escpr-1.8-missing-include.patch]]
- [[ia4rsbinzj016ycqm8pjmzz5vnydnp50-epson-inkjet-printer-escpr-1.8.6-1.tar.gz]]
- [[ixx9yxbr5m9dpfmppai52mgw663v388i-dos2unix-7.5.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rjyws93c0jmgas9vpcybl8ypndw73rqd-1.8.6-warnings.patch]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/x5gfirhz3sl53qf12cx38hp7ymxykjp6-cups-filter-ppd-dirs.patch`

---
*Generated on 2025-09-27 11:52:49 UTC*
