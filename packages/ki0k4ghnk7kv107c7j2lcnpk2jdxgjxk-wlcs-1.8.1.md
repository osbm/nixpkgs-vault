---
aliases:
  - wlcs
tags:
  - license/unknown
  - maintainers/OPNA2608
  - outputs/out
---

# wlcs

## 📝 Description

wlcs aspires to be a protocol-conformance-verifying test suite usable by Wayland
compositor implementors.

It is growing out of porting the existing Weston test suite to be run in Mir's
test suite, but it is designed to be usable by any compositor.

wlcs relies on compositors providing an integration module, providing wlcs with
API hooks to start a compositor, connect a client, move a window, and so on.
This makes both writing and debugging tests easier - the tests are (generally)
in the same address space as the compositor, so there is a consistent global
clock available, it's easier to poke around in compositor internals, and
standard debugging tools can follow control flow from the test client to the
compositor and back again.


## 📋 Package Information

- **Name**: `wlcs`
- **Version**: `1.8.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Wayland Conformance Test Suite
- **Homepage**: [https://github.com/MirServer/wlcs](https://github.com/MirServer/wlcs)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @OPNA2608


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ki0k4ghnk7kv107c7j2lcnpk2jdxgjxk-wlcs-1.8.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/wl/wlcs/package.nix:52`
- **Outputs**:
  - `out`:  `/nix/store/ki0k4ghnk7kv107c7j2lcnpk2jdxgjxk-wlcs-1.8.1`

## 🔗 Dependencies

- [[02l2mwk9x35ww8hq6m836yrcy0ma7js8-wayland-1.24.0]]
- [[6gws6n92iv1sxvqqin5n019pwksx4z8w-gtest-1.17.0]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i3ph2z8ayfgsqlrj9y2gwiyv3fmj6w10-boost-1.87.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rbjsvyngabldcxkvh1bqis3jaiy29x2j-wayland-scanner-1.24.0]]
- [[wjcgngrgq4gxvnwvczdy93wc187fdy93-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:14:52 UTC*
