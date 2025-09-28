---
aliases:
  - snowcat
tags:
  - license/unknown
  - maintainers/06kellyjac
  - outputs/out
---

# snowcat

## 📝 Description

Snowcat gathers and analyzes the configuration of an Istio cluster and
audits it for potential violations of security best practices.

There are two main modes of operation for Snowcat. With no positional
argument, Snowcat will assume it is running inside of a cluster enabled
with Istio, and begin to enumerate the required data. Optionally, you can
point snowcat at a directory containing Kubernets YAML files.


## 📋 Package Information

- **Name**: `snowcat`
- **Version**: `0.1.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tool to audit the istio service mesh
- **Homepage**: [https://github.com/praetorian-inc/snowcat](https://github.com/praetorian-inc/snowcat)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @06kellyjac


## 🔧 Build Information

- **Derivation Path**: `/nix/store/4xwk9qw06rqrqwpfhg12qa71f5zy4lji-snowcat-0.1.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sn/snowcat/package.nix:27`
- **Outputs**:
  - `out`:  `/nix/store/4xwk9qw06rqrqwpfhg12qa71f5zy4lji-snowcat-0.1.3`

## 🔗 Dependencies

- [[4xgfdh1zfk70887m1a8j3fgwgvzh2m05-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[n4y89dnwc8g44r3l8mj52lm2ni0qiv28-snowcat-0.1.3-go-modules]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:14:49 UTC*
