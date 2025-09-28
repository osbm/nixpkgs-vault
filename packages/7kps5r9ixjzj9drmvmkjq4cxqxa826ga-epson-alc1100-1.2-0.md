---
aliases:
  - epson-alc1100
tags:
  - not-available
  - license/unknown
  - maintainers/emanueleperuffo
  - outputs/out
---

# epson-alc1100

## 📝 Description

This package provides a print filter for printing to EPSON AL-C1100
printers on Linux systems.

To use the driver adjust your configuration.nix file:
  services.printing = {
    enable = true;
    drivers = [ pkgs.epson-alc1100 ];
  };


## 📋 Package Information

- **Name**: `epson-alc1100`
- **Version**: `1.2-0`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Epson AcuLaser C1100 Driver
- **Homepage**: [http://download.ebz.epson.net/dsc/search/01/search/](http://download.ebz.epson.net/dsc/search/01/search/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @emanueleperuffo


## 🔧 Build Information

- **Derivation Path**: `/nix/store/7kps5r9ixjzj9drmvmkjq4cxqxa826ga-epson-alc1100-1.2-0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ep/epson-alc1100/package.nix:81`
- **Outputs**:
  - `out`:  `/nix/store/7kps5r9ixjzj9drmvmkjq4cxqxa826ga-epson-alc1100-1.2-0`

## 🔗 Dependencies

- [[1jgyc8pm0h5lnk0imm0bs3fhshis2hr2-cups-2.4.12]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[3qp106mw8bp96nbllglgnjzvkmbrrh47-ghostscript-with-X-10.05.1]]
- [[8a12cmpc0mkh7hhzicvv3xv52sd4263m-dpkg-1.22.21]]
- [[996i0hrf86i56qqprjydags7zrp7qq6g-glibc-2.40-66]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qkahzrv1gclcl2b2ssysizzqs76cxraq-libstdc++5_3.3.6-17ubuntu1_i386.deb]]
- [[rfxn7v2b7p34w5jwk32i5psn0m6xlc9n-psutils-17]]
- [[v28sdl3535sxb6a71z5faqdzbns9pv0h-bash-interactive-5.3p3]]
- [[z56xyklfv0fj3y1ykrxmdhdpzzybcbr3-Epson-ALC1100-filter-1.2.tar.gz]]

## 📁 Input Sources

- `/nix/store/bg0k1rl1f57bfniqjchl7jq2dlj3mf13-cups-data-dir.patch`
- `/nix/store/i2gz9ffsqm181srfdgzl7x2wzyzjvpch-ppd.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:48 UTC*
