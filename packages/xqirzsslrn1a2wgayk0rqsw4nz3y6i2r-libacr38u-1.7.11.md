---
aliases:
  - libacr38u
tags:
  - license/unknown
  - maintainers/berce
  - outputs/out
---

# libacr38u

## 📝 Description

A PC/SC IFD handler implementation for the ACS ACR38U
smartcard readers. This driver is for the non-CCID version only.

This package is needed to communicate with the ACR38U smartcard readers through
the PC/SC Lite resource manager (pcscd).

It can be enabled in /etc/nixos/configuration.nix by adding:
  services.pcscd.enable = true;
  services.pcscd.plugins = [ libacr38u ];

The package is based on the debian package libacr38u.


## 📋 Package Information

- **Name**: `libacr38u`
- **Version**: `1.7.11`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: ACR38U smartcard reader driver for pcsclite
- **Homepage**: [https://www.acs.com.hk](https://www.acs.com.hk)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @berce


## 🔧 Build Information

- **Derivation Path**: `/nix/store/xqirzsslrn1a2wgayk0rqsw4nz3y6i2r-libacr38u-1.7.11.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libacr38u/package.nix:36`
- **Outputs**:
  - `out`:  `/nix/store/xqirzsslrn1a2wgayk0rqsw4nz3y6i2r-libacr38u-1.7.11`

## 🔗 Dependencies

- [[8mkm9ynshs1vv64asmcm1x2bs3f34m5v-acr38_1.7.11.orig.tar.bz2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[n1094mb1mfbgz7c6z04f06smgidni26i-libusb-compat-0.1.8]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[r48wqvwdssqgvdmiak53raw5a193spbm-pcsclite-2.3.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:13:08 UTC*
