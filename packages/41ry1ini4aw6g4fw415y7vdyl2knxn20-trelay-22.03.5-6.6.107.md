---
aliases:
  - linuxKernel.packages.linux_6_6.trelay
tags:
  - license/unknown
  - maintainers/CutestNekoAqua
  - outputs/out
---

# linuxKernel.packages.linux_6_6.trelay

## 📝 Description

A kernel module that relays ethernet packets between two devices (similar to a bridge),
but without any MAC address checks.

This makes it possible to bridge client mode or ad-hoc mode wifi devices to ethernet VLANs,
assuming the remote end uses the same source MAC address as the device that packets are
supposed to exit from.


## 📋 Package Information

- **Name**: `linuxKernel.packages.linux_6_6.trelay`
- **Version**: `22.03.5-6.6.107`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: For relaying IP packets between two devices to build a IP bridge between them
- **Homepage**: [https://github.com/openwrt/openwrt/tree/main/package/kernel/trelay](https://github.com/openwrt/openwrt/tree/main/package/kernel/trelay)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @CutestNekoAqua


## 🔧 Build Information

- **Derivation Path**: `/nix/store/41ry1ini4aw6g4fw415y7vdyl2knxn20-trelay-22.03.5-6.6.107.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/trelay/default.nix:41`
- **Outputs**:
  - `out`:  `/nix/store/41ry1ini4aw6g4fw415y7vdyl2knxn20-trelay-22.03.5-6.6.107`

## 🔗 Dependencies

- [[0i6l8h1ds9dkr1ivc77hzsdl51mfahm0-pahole-1.30]]
- [[5njf380kc22sqy9cgj1kldyrhn3s9zif-uname]]
- [[6r5cldhv0mdkwwia0zdchk4aar0azvrd-gcc-14.3.0]]
- [[8qvzhry004aybdbrb9y8c387ah9k0mps-binutils-2.44]]
- [[96vv66p4biczw55qf9jhwqn7awwn861h-elfutils-0.193]]
- [[ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i9kj1nhzkg91xsq8ny4z4hipl0b42kad-gcc-wrapper-14.3.0]]
- [[iirc0g0mb5h1plq8b495q5s5dp9ni6py-linux-6.6.107]]
- [[kvysay8plzjaxgvj64sxz0b4d9xc25n0-binutils-wrapper-2.44]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lq59fpmf2qlrgpwmcdznm725w2x7lmbp-openwrt]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qmg0h7ddbh8r5iissdh538jgwx5xi189-kmod-31]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/mwnmx2b0jlhdlgdikd2cikr8zzh6dj1b-Makefile`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:08:22 UTC*
