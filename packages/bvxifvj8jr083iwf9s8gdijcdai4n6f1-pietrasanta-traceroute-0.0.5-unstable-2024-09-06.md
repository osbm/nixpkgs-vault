---
aliases:
  - pietrasanta-traceroute
tags:
  - license/unknown
  - maintainers/nicoonoclaste
  - outputs/out
---

# pietrasanta-traceroute

## 📝 Description

An enhanced version of Dmitry Butskoy's traceroute, developed by Catchpoint.
- Support for "TCP InSession": opens a TCP connection with the destination and sends TCP probes with
  increasing TTL values, to prevent false packet loss introduced by firewalls, and ensure packets
  follow a single flow, akin to a normal TCP session.
- Similar QUIC-based traceroute.
- Enhanced ToS (DSCP/ECN) field report.


## 📋 Package Information

- **Name**: `pietrasanta-traceroute`
- **Version**: `0.0.5-unstable-2024-09-06`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: ECN-aware version of traceroute
- **Homepage**: [https://github.com/catchpoint/Networking.traceroute/](https://github.com/catchpoint/Networking.traceroute/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @nicoonoclaste


## 🔧 Build Information

- **Derivation Path**: `/nix/store/bvxifvj8jr083iwf9s8gdijcdai4n6f1-pietrasanta-traceroute-0.0.5-unstable-2024-09-06.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/pi/pietrasanta-traceroute/package.nix:25`
- **Outputs**:
  - `out`:  `/nix/store/bvxifvj8jr083iwf9s8gdijcdai4n6f1-pietrasanta-traceroute-0.0.5-unstable-2024-09-06`

## 🔗 Dependencies

- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[kls4cj1cxfc30wk9nn4mjmhxv0yh1xvk-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:13:08 UTC*
