---
aliases:
  - alpnpass
tags:
  - license/unknown
  - maintainers/raboof
  - outputs/out
---

# alpnpass

## 📝 Description

This tool will listen on a given port, strip SSL encryption,
forward traffic through a plain TCP proxy,
then encrypt the returning traffic again
and send it to the target of your choice.

Unlike most SSL stripping solutions this tool will negotiate ALPN and
preserve the negotiated protocol all the way to the target.


## 📋 Package Information

- **Name**: `alpnpass`
- **Version**: `0.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Inspect the plaintext payload inside of proxied TLS connections
- **Homepage**: [https://github.com/VerSprite/alpnpass](https://github.com/VerSprite/alpnpass)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @raboof


## 🔧 Build Information

- **Derivation Path**: `/nix/store/sh4jc11hxk9hn7m4vmj5k0y7hjb92zy9-alpnpass-0.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/al/alpnpass/package.nix:21`
- **Outputs**:
  - `out`:  `/nix/store/sh4jc11hxk9hn7m4vmj5k0y7hjb92zy9-alpnpass-0.1`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[wprki8zip83kd3x79f63ias0aa7x5by7-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:54:33 UTC*
