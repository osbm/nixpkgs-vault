---
aliases:
  - acsccid
tags:
  - license/unknown
  - outputs/out
---

# acsccid

## 📝 Description

acsccid is a PC/SC driver for Linux/Mac OS X and it supports ACS CCID smart card
readers. This library provides a PC/SC IFD handler implementation and
communicates with the readers through the PC/SC Lite resource manager (pcscd).

acsccid is based on ccid. See CCID free software driver for more
information:
https://ccid.apdu.fr/

It can be enabled in /etc/nixos/configuration.nix by adding:
  services.pcscd.enable = true;
  services.pcscd.plugins = [ pkgs.acsccid ];


## 📋 Package Information

- **Name**: `acsccid`
- **Version**: `1.1.12`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: PC/SC driver for Linux/Mac OS X and it supports ACS CCID smart card readers
- **Homepage**: [http://acsccid.sourceforge.net](http://acsccid.sourceforge.net)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/w3czmdagv20nk3i3ngd9wgjisvv1yyby-acsccid-1.1.12.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ac/acsccid/package.nix:60`
- **Outputs**:
  - `out`:  `/nix/store/w3czmdagv20nk3i3ngd9wgjisvv1yyby-acsccid-1.1.12`

## 🔗 Dependencies

- [[1fzxi5zfzvgbj9j19wl9ihk41nhmjyw3-autoconf-archive-2024.10.16]]
- [[7ys6vrd29swy0hb42rbhrc1sbsk4cq1g-autoconf-2.72]]
- [[82mw0nl5kb1zw36l4s4d0pdlfiadwlss-automake-1.18.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dxga515sbr7fhnkypnm27wnarrmzr65z-acsccid-1.1.12.tar.bz2]]
- [[fy9wjrqf0pzd5x3rvy665v50ff747wfd-libusb-1.0.29]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[m0h8vm7wnxqmzy77yph902p607lx7np5-gettext-0.25.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[r48wqvwdssqgvdmiak53raw5a193spbm-pcsclite-2.3.0]]
- [[sv8lxxb30bqw2b360ni6rsp89mg2dvbp-libtool-2.5.4]]
- [[wy61x67y125m36dp7l7xhzqbi30mxg1d-flex-2.6.4]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:43:41 UTC*
