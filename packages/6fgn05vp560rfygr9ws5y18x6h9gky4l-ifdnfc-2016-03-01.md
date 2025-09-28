---
aliases:
  - ifdnfc
tags:
  - license/unknown
  - maintainers/makefu
  - outputs/out
---

# ifdnfc

## 📝 Description

libnfc Interface Plugin to be used in <code>services.pcscd.plugins</code>.
It provides support for all readers which are not supported by ccid but by libnfc.

For activating your reader you need to run
<code>ifdnfc-activate yes<code> with this package in your
<code>environment.systemPackages</code>

To use your reader you may need to blacklist your reader kernel modules:
<code>boot.blacklistedKernelModules = [ "pn533" "pn533_usb" "nfc" ];</code>

Supports the pn533 smart-card reader chip which is for example used in
the SCM SCL3711.


## 📋 Package Information

- **Name**: `ifdnfc`
- **Version**: `2016-03-01`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: PC/SC IFD Handler based on libnfc
- **Homepage**: [https://github.com/nfc-tools/ifdnfc](https://github.com/nfc-tools/ifdnfc)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @makefu


## 🔧 Build Information

- **Derivation Path**: `/nix/store/6fgn05vp560rfygr9ws5y18x6h9gky4l-ifdnfc-2016-03-01.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/if/ifdnfc/package.nix:37`
- **Outputs**:
  - `out`:  `/nix/store/6fgn05vp560rfygr9ws5y18x6h9gky4l-ifdnfc-2016-03-01`

## 🔗 Dependencies

- [[2xbcv72w9pjfk8nwr8sdrlp9kx6cy6wl-source]]
- [[8l273mkw0dy8x0x2acay678dcx3cjb52-libnfc-1.8.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[r48wqvwdssqgvdmiak53raw5a193spbm-pcsclite-2.3.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:08:56 UTC*
