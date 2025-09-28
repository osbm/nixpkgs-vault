---
aliases:
  - lima-additional-guestagents
tags:
  - license/unknown
  - maintainers/kachick
  - outputs/out
---

# lima-additional-guestagents

## 📝 Description

This package should only be used when your guest's architecture differs from the host's.

To enable its functionality in `limactl`, set `withAdditionalGuestAgents = true` in the `lima` package:
```nix
pkgs.lima.override {
  withAdditionalGuestAgents = true;
}
```

Typically, you won't need to directly add this package to your *.nix files.


## 📋 Package Information

- **Name**: `lima-additional-guestagents`
- **Version**: `1.2.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Lima Guest Agents for emulating non-native architectures
- **Homepage**: [https://github.com/lima-vm/lima](https://github.com/lima-vm/lima)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @kachick


## 🔧 Build Information

- **Derivation Path**: `/nix/store/pwr391p1fld4b15c1vzx49n7hh4yb75l-lima-additional-guestagents-1.2.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/lima-additional-guestagents/package.nix:72`
- **Outputs**:
  - `out`:  `/nix/store/pwr391p1fld4b15c1vzx49n7hh4yb75l-lima-additional-guestagents-1.2.1`

## 🔗 Dependencies

- [[6m3r081apg6d3zl9n72sl6phppfldgfh-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[sl3ibba3ad7ipf41rfzy6v8h4s0cgdci-findutils-4.10.0]]
- [[zl6dawqrssgjj64rmx0jbyfrywawqbqd-lima-additional-guestagents-1.2.1-go-modules]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:06:05 UTC*
