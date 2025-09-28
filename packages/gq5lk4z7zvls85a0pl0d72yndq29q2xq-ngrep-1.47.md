---
aliases:
  - ngrep
tags:
  - license/unknown
  - maintainers/bjornfor
  - outputs/out
---

# ngrep

## 📝 Description

ngrep strives to provide most of GNU grep's common features, applying
them to the network layer. ngrep is a pcap-aware tool that will allow you
to specify extended regular or hexadecimal expressions to match against
data payloads of packets. It currently recognizes IPv4/6, TCP, UDP,
ICMPv4/6, IGMP and Raw across Ethernet, PPP, SLIP, FDDI, Token Ring and
null interfaces, and understands BPF filter logic in the same fashion as
more common packet sniffing tools, such as tcpdump and snoop.


## 📋 Package Information

- **Name**: `ngrep`
- **Version**: `1.47`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Network packet analyzer
- **Homepage**: [https://github.com/jpr5/ngrep/](https://github.com/jpr5/ngrep/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`
## 👥 Maintainers

- @bjornfor


## 🔧 Build Information

- **Derivation Path**: `/nix/store/gq5lk4z7zvls85a0pl0d72yndq29q2xq-ngrep-1.47.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ng/ngrep/package.nix:47`
- **Outputs**:
  - `out`:  `/nix/store/gq5lk4z7zvls85a0pl0d72yndq29q2xq-ngrep-1.47`

## 🔗 Dependencies

- [[14xsz7vrr67cba8nhgdgadr420fmn1cp-source]]
- [[3zvhnvb5q37g1nsr1b4an0syv2qwi0wz-pcre-8.45]]
- [[7395sqanx3w55cy8k3y50f8i69ik8wci-libpcap-1.10.5]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[wkiw68kc2akgx8pifx1cwag1hkmnb638-11.patch]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:21:13 UTC*
