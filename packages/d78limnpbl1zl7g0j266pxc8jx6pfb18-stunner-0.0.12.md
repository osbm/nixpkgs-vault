---
aliases:
  - stunner
tags:
  - license/unknown
  - maintainers/06kellyjac
  - outputs/out
---

# stunner

## 📝 Description

Stunner is a small Go CLI tool that sends STUN Binding Requests to
multiple Tailscale DERP servers (or any STUN servers you specify) and
reports the resulting NAT classification. This helps you determine
whether you're behind a Full Cone, Symmetric NAT, Restricted, or
otherwise, by analyzing how multiple STUN servers perceive your external
IP/port mapping.


## 📋 Package Information

- **Name**: `stunner`
- **Version**: `0.0.12`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Detect your NAT quickly and easily, and that's the bottom line
- **Homepage**: [https://github.com/jaxxstorm/stunner](https://github.com/jaxxstorm/stunner)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @06kellyjac


## 🔧 Build Information

- **Derivation Path**: `/nix/store/d78limnpbl1zl7g0j266pxc8jx6pfb18-stunner-0.0.12.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/st/stunner/package.nix:28`
- **Outputs**:
  - `out`:  `/nix/store/d78limnpbl1zl7g0j266pxc8jx6pfb18-stunner-0.0.12`

## 🔗 Dependencies

- [[31n3yxg8i9mmlz5fqhh7s43cncqazjvl-stunner-0.0.12-go-modules]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[mlciss8ipzglc0hg6fvhiqlqjpp4gsaw-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:55:22 UTC*
