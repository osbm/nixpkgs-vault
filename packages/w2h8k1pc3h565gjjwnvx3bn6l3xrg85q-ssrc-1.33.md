---
aliases:
  - ssrc
tags:
  - license/unknown
  - maintainers/leenaars
  - outputs/out
---

# ssrc

## 📝 Description

This program converts sampling rates of PCM wav files. This
program also has a function to apply dither to its output and
extend perceived dynamic range.

Sampling rates of 44.1kHz and 48kHz are popularly used, but the
ratio between these two frequencies is 147:160, which are not
small numbers. As a result, sampling rate conversion without
degradation of sound quality requires filter with very large
order, and it is difficult to have both quality and speed. This
program quickly converts between these sampling frequencies
without audible degradation.


## 📋 Package Information

- **Name**: `ssrc`
- **Version**: `1.33`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: High quality audio sampling rate converter
- **Homepage**: [https://shibatch.sourceforge.net/](https://shibatch.sourceforge.net/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @leenaars


## 🔧 Build Information

- **Derivation Path**: `/nix/store/w2h8k1pc3h565gjjwnvx3bn6l3xrg85q-ssrc-1.33.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ss/ssrc/package.nix:24`
- **Outputs**:
  - `out`:  `/nix/store/w2h8k1pc3h565gjjwnvx3bn6l3xrg85q-ssrc-1.33`

## 🔗 Dependencies

- [[ac4a3yyl2i9jnzfg3nm2iwyw88z7f5ml-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:51:58 UTC*
