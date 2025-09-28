---
aliases:
  - nat-traverse
tags:
  - license/unknown
  - maintainers/iblech
  - outputs/out
---

# nat-traverse

## 📝 Description

nat-traverse establishes direct connections between nodes which are
behind NAT gateways, i.e. hosts which do not have public IP addresses.
This is done using an UDP NAT traversal technique. Additionally, it's
possible to setup a small VPN by using pppd on top of nat-traverse.

nat-traverse does not need an external server on the Internet, and it
isn't necessary to reconfigure the involved NAT gateways, either.
nat-traverse works out-of-the-box.


## 📋 Package Information

- **Name**: `nat-traverse`
- **Version**: `0.7`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: NAT gateway traversal utility
- **Homepage**: [https://www.speicherleck.de/iblech/nat-traverse/](https://www.speicherleck.de/iblech/nat-traverse/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @iblech


## 🔧 Build Information

- **Derivation Path**: `/nix/store/pppbxjh3ikk6g8ngpsdbmvkbbz1g8czy-nat-traverse-0.7.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/na/nat-traverse/package.nix:26`
- **Outputs**:
  - `out`:  `/nix/store/pppbxjh3ikk6g8ngpsdbmvkbbz1g8czy-nat-traverse-0.7`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[c1rc7395imlfxb6ch4bq3ykhly4k9iy8-nat-traverse-0.7.tar.bz2]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:15:25 UTC*
