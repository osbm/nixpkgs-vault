---
aliases:
  - headscale
tags:
  - license/unknown
  - maintainers/kradalby
  - maintainers/Misterio77
  - outputs/out
---

# headscale

## 📝 Description

Tailscale is a modern VPN built on top of Wireguard. It works like an
overlay network between the computers of your networks - using all kinds
of NAT traversal sorcery.

Everything in Tailscale is Open Source, except the GUI clients for
proprietary OS (Windows and macOS/iOS), and the
'coordination/control server'.

The control server works as an exchange point of Wireguard public keys for
the nodes in the Tailscale network. It also assigns the IP addresses of
the clients, creates the boundaries between each user, enables sharing
machines between users, and exposes the advertised routes of your nodes.

Headscale implements this coordination server.


## 📋 Package Information

- **Name**: `headscale`
- **Version**: `0.26.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Open source, self-hosted implementation of the Tailscale control server
- **Homepage**: [https://github.com/juanfont/headscale](https://github.com/juanfont/headscale)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @kradalby
- @Misterio77


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ann73d3v0g498jaqdari9rpmbb866pr9-headscale-0.26.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/servers/headscale/default.nix:57`
- **Outputs**:
  - `out`:  `/nix/store/ann73d3v0g498jaqdari9rpmbb866pr9-headscale-0.26.1`

## 🔗 Dependencies

- [[0ihzm6m1z1842bwzpm4g2957vxyr7d6m-postgresql-17.6]]
- [[5qk0bnq374kh3a4m2cnn70zarc8qp5hb-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dfaq0sryvfw931fdf7f2cayf9wqyxig1-libredirect-0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[y8am3sx90vqdp6yshfb8k8gd05097d68-headscale-0.26.1-go-modules]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:10:38 UTC*
