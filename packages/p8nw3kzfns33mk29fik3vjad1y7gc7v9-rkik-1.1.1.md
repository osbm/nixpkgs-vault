---
aliases:
  - rkik
tags:
  - license/unknown
  - maintainers/yzhou216
  - outputs/out
---

# rkik

## 📝 Description

Most systems rely on a daemon (like chronyd or ntpd) to
synchronize time. But what if you just want to inspect the
current offset between your system clock and one or more NTP
servers — without root, without sync, and without installing
anything heavyweight?

RKIK is a Rust-based CLI tool designed for stateless and passive
NTP inspection, just as dig or ping are for DNS and ICMP.


## 📋 Package Information

- **Name**: `rkik`
- **Version**: `1.1.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Command-line tool for querying NTP servers and comparing clock offsets
- **Homepage**: [https://github.com/aguacero7/rkik](https://github.com/aguacero7/rkik)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv6l-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv64-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `powerpc-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `i686-windows`, `x86_64-windows`, `armv5tel-linux`, `armv7a-linux`, `m68k-linux`, `mips-linux`, `mips64-linux`, `mipsel-linux`, `mips64el-linux`, `riscv32-linux`, `armv6l-netbsd`, `mipsel-netbsd`, `riscv64-netbsd`, `x86_64-redox`, `wasm32-wasi`
## 👥 Maintainers

- @yzhou216


## 🔧 Build Information

- **Derivation Path**: `/nix/store/p8nw3kzfns33mk29fik3vjad1y7gc7v9-rkik-1.1.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/rk/rkik/package.nix:24`
- **Outputs**:
  - `out`:  `/nix/store/p8nw3kzfns33mk29fik3vjad1y7gc7v9-rkik-1.1.1`

## 🔗 Dependencies

- [[0f5ann1sgwyp31vlfqqsnr95xzv3mzhf-cargo-1.89.0]]
- [[3bz4j2xzjl92yhiwfyhbz6gv4w1888bw-cargo-setup-hook.sh]]
- [[3ndchkhlxxw50k7nd48i9zdkhsr57mwh-cargo-install-hook.sh]]
- [[4bycw2rdgf33gmn1z26knv8grxxh06w5-rustc-wrapper-1.89.0]]
- [[4cc0y6syxyxvjx1lh8ix60vxkly149fh-auditable-cargo-1.89.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[nnwlrwshi9h9jbi1sjqrm2ni9s4z5313-rkik-1.1.1-vendor]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qi6337yh29r9ppqm262bf6vz0g13451b-cargo-build-hook.sh]]
- [[w14xl1bvc9bjzwlrmz096qbhk5xabd2d-source]]
- [[xqxbqs6qgnhvpkcai046s94jfrx8wb62-cargo-check-hook.sh]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:21:22 UTC*
