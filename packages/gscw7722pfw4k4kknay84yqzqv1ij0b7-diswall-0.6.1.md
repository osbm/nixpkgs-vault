---
aliases:
  - diswall
tags:
  - license/unknown
  - maintainers/Izorkin
  - outputs/out
---

# diswall

## 📝 Description

Diswall (distributed firewall) - a client of distributed firewall
working on many servers and using NATS for the transport level.
Its purpose - blocking IPs with a blink of the eye on all servers
in any infrastructure when some IP checks any of the closed ports
of anyone of these servers. Therefore, diswall provides good
protection of whole infrastructure (as anti-shodan) preventing
intruder to get any system information.


## 📋 Package Information

- **Name**: `diswall`
- **Version**: `0.6.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Distributed firewall
- **Homepage**: [https://www.diswall.stream](https://www.diswall.stream)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv6l-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv64-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `powerpc-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `i686-windows`, `x86_64-windows`, `armv5tel-linux`, `armv7a-linux`, `m68k-linux`, `mips-linux`, `mips64-linux`, `mipsel-linux`, `mips64el-linux`, `riscv32-linux`, `armv6l-netbsd`, `mipsel-netbsd`, `riscv64-netbsd`, `x86_64-redox`, `wasm32-wasi`
## 👥 Maintainers

- @Izorkin


## 🔧 Build Information

- **Derivation Path**: `/nix/store/gscw7722pfw4k4kknay84yqzqv1ij0b7-diswall-0.6.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/di/diswall/package.nix:23`
- **Outputs**:
  - `out`:  `/nix/store/gscw7722pfw4k4kknay84yqzqv1ij0b7-diswall-0.6.1`

## 🔗 Dependencies

- [[0f5ann1sgwyp31vlfqqsnr95xzv3mzhf-cargo-1.89.0]]
- [[15wvjs38ly3873cvc209n97wp8zcfy7d-diswall-0.6.1-vendor]]
- [[3bz4j2xzjl92yhiwfyhbz6gv4w1888bw-cargo-setup-hook.sh]]
- [[3ndchkhlxxw50k7nd48i9zdkhsr57mwh-cargo-install-hook.sh]]
- [[4bycw2rdgf33gmn1z26knv8grxxh06w5-rustc-wrapper-1.89.0]]
- [[4cc0y6syxyxvjx1lh8ix60vxkly149fh-auditable-cargo-1.89.0]]
- [[5nhaq79v0qz297fl7zsga7gxnpf809yb-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qi6337yh29r9ppqm262bf6vz0g13451b-cargo-build-hook.sh]]
- [[xqxbqs6qgnhvpkcai046s94jfrx8wb62-cargo-check-hook.sh]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:46:56 UTC*
