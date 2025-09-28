---
aliases:
  - spice-autorandr
tags:
  - license/unknown
  - maintainers/dmytrokyrychuk
  - outputs/out
---

# spice-autorandr

## 📝 Description

Some desktop environments update the display resolution automatically,
this package is only useful when running without a DE or with a DE that
does not update display resolution automatically.

This package relies on `spice-vdagent` running an updating the xrandr modes. Enable
`spice-vdagent` by adding `services.spice-autorandr.enable = true` to your `configuration.nix`.


## 📋 Package Information

- **Name**: `spice-autorandr`
- **Version**: `0.0.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Automatically adjust the client window resolution in Linux KVM guests using the SPICE driver
- **Homepage**: [https://github.com/seife/spice-autorandr](https://github.com/seife/spice-autorandr)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @dmytrokyrychuk


## 🔧 Build Information

- **Derivation Path**: `/nix/store/x5ma02n5nm8xbnx9zdxmic7c1p0jadp9-spice-autorandr-0.0.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sp/spice-autorandr/package.nix:41`
- **Outputs**:
  - `out`:  `/nix/store/x5ma02n5nm8xbnx9zdxmic7c1p0jadp9-spice-autorandr-0.0.2`

## 🔗 Dependencies

- [[7xdaqs6syz77x48wil5a847cvlr61mnv-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[nncd4f9vl1alqwmiff6a138ppbsgbp5l-libx11-1.8.12]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rvsgycjzldbgg1l9f6bxrdncx02va128-libxrandr-1.5.4]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:15:00 UTC*
