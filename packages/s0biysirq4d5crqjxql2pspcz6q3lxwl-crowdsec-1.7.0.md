---
aliases:
  - crowdsec
tags:
  - license/unknown
  - maintainers/06kellyjac
  - maintainers/urandom2
  - outputs/out
---

# crowdsec

## 📝 Description

CrowdSec is a free, modern & collaborative behavior detection engine,
coupled with a global IP reputation network. It stacks on fail2ban's
philosophy but is IPV6 compatible and 60x faster (Go vs Python), uses Grok
patterns to parse logs and YAML scenario to identify behaviors. CrowdSec
is engineered for modern Cloud/Containers/VM based infrastructures (by
decoupling detection and remediation). Once detected you can remedy
threats with various bouncers (firewall block, nginx http 403, Captchas,
etc.) while the aggressive IP can be sent to CrowdSec for curation before
being shared among all users to further improve everyone's security.


## 📋 Package Information

- **Name**: `crowdsec`
- **Version**: `1.7.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Free, open-source and collaborative IPS
- **Homepage**: [https://crowdsec.net/](https://crowdsec.net/)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @06kellyjac
- @urandom2


## 🔧 Build Information

- **Derivation Path**: `/nix/store/s0biysirq4d5crqjxql2pspcz6q3lxwl-crowdsec-1.7.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/cr/crowdsec/package.nix:68`
- **Outputs**:
  - `out`:  `/nix/store/s0biysirq4d5crqjxql2pspcz6q3lxwl-crowdsec-1.7.0`

## 🔗 Dependencies

- [[2h2gvrfcy1ckrcqkyd5mdj44v1njjgln-crowdsec-1.7.0-go-modules]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[wvrshs417s8n5k4xc39ym1wlm69qzqc9-source]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:01:20 UTC*
