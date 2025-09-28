---
aliases:
  - wireguard-tools
tags:
  - license/unknown
  - maintainers/zx2c4
  - maintainers/globin
  - maintainers/Ma27
  - outputs/man
  - outputs/out
---

# wireguard-tools

## 📝 Description

Supplies the main userspace tooling for using and configuring WireGuard tunnels, including the wg(8) and wg-quick(8) utilities.
- wg : the configuration utility for getting and setting the configuration of WireGuard tunnel interfaces. The interfaces
  themselves can be added and removed using ip-link(8) and their IP addresses and routing tables can be set using ip-address(8)
  and ip-route(8). The wg utility provides a series of sub-commands for changing WireGuard-specific aspects of WireGuard interfaces.
- wg-quick : an extremely simple script for easily bringing up a WireGuard interface, suitable for a few common use cases.


## 📋 Package Information

- **Name**: `wireguard-tools`
- **Version**: `1.0.20250521`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tools for the WireGuard secure network tunnel
- **Homepage**: [https://www.wireguard.com/](https://www.wireguard.com/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @zx2c4
- @globin
- @Ma27


## 🔧 Build Information

- **Derivation Path**: `/nix/store/w0mwn5zgkmapp439bhn1501ikkw4jbyw-wireguard-tools-1.0.20250521.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/wi/wireguard-tools/package.nix:79`
- **Outputs**:
  - `man`:  `/nix/store/w0mwn5zgkmapp439bhn1501ikkw4jbyw-wireguard-tools-1.0.20250521`
  - `out`:  `/nix/store/w0mwn5zgkmapp439bhn1501ikkw4jbyw-wireguard-tools-1.0.20250521`

## 🔗 Dependencies

- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[9qnjgd5vx73f8ibl1fpjhzvkyfawrwfj-iptables-1.8.11]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bwbcgqycvsqyc194ay5m53hqjqy84lmd-source]]
- [[gbfh32nmdybsdp0qalm22zagn5c2x9z2-openresolv-3.16.5]]
- [[lxw1zfs9v3nm19mpqbllvcl3s2hkpbjq-procps-4.0.4]]
- [[mc983csj0fvcg5gf5gwhvmi4a9v3jajq-iproute2-6.16.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[v28sdl3535sxb6a71z5faqdzbns9pv0h-bash-interactive-5.3p3]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:18:05 UTC*
