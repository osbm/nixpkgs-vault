---
aliases:
  - cortex-tools
tags:
  - license/unknown
  - maintainers/videl
  - outputs/out
---

# cortex-tools

## 📝 Description

Tools used for interacting with Cortex, a horizontally scalable, highly available, multi-tenant, long term Prometheus server:

- benchtool: A powerful YAML driven tool for benchmarking Cortex write and query API.
- cortextool: Interacts with user-facing Cortex APIs and backend storage components.
- logtool: Tool which parses Cortex query-frontend logs and formats them for easy analysis.
- e2ealerting: Tool that helps measure how long an alert takes from scrape of sample to Alertmanager notification delivery.


## 📋 Package Information

- **Name**: `cortex-tools`
- **Version**: `0.11.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tools used for interacting with Cortex, a Prometheus-compatible server
- **Homepage**: [https://github.com/grafana/cortex-tools](https://github.com/grafana/cortex-tools)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`, `x86_64-darwin`, `aarch64-darwin`
## 👥 Maintainers

- @videl


## 🔧 Build Information

- **Derivation Path**: `/nix/store/38jw7qcgdwcswx2l4967npnm1kyi7i9q-cortex-tools-0.11.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/co/cortex-tools/package.nix:64`
- **Outputs**:
  - `out`:  `/nix/store/38jw7qcgdwcswx2l4967npnm1kyi7i9q-cortex-tools-0.11.3`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lzvy25g887aypn07ah8igv72z7b9jb88-version-check-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[rwmhrl51ln46gvv4dhwqpvifx5f47wm4-source]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:57:52 UTC*
