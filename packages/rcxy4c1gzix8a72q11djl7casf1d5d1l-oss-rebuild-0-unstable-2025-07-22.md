---
aliases:
  - oss-rebuild
tags:
  - license/unknown
  - maintainers/katexochen
  - outputs/out
---

# oss-rebuild

## 📝 Description

OSS Rebuild aims to apply reproducible build concepts at low-cost and high-scale for open-source package ecosystems.

Rebuilds are derived by analyzing the published metadata and artifacts and are evaluated against the upstream package
versions. When successful, build attestations are published for the upstream artifacts, verifying the integrity of
the upstream artifact and eliminating many possible sources of compromise.

[`oss-rebuild`](https://github.com/google/oss-rebuild?tab=readme-ov-file#usage) CLI tool provides access to OSS Rebuild
data.

[`proxy`](https://github.com/google/oss-rebuild/blob/main/cmd/proxy/README.md) is a transparent HTTP(S) proxy that
intercepts and records network activity. It's primarily used within OSS Rebuild to monitor network interactions during
the build process, helping to passively enumerate remote dependencies and to identify suspect build behavior.

[`stabilize`](https://github.com/google/oss-rebuild/blob/main/cmd/stabilize/README.md) is a command-line tool that
removes non-deterministic metadata from software packages to facilitate functional comparison of artifacts.

[`timewarp`](https://github.com/google/oss-rebuild/blob/main/cmd/timewarp/README.md) is a registry-fronting HTTP
service that filters returned content by time. This tool allows you to transparently adjust the data returned to
package manager clients to reflect the state of a registry at a given point in time (especially useful for reproducing
prior builds).


## 📋 Package Information

- **Name**: `oss-rebuild`
- **Version**: `0-unstable-2025-07-22`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Securing open-source package ecosystems by originating, validating, and augmenting build attestations
- **Homepage**: [https://github.com/google/oss-rebuild](https://github.com/google/oss-rebuild)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @katexochen


## 🔧 Build Information

- **Derivation Path**: `/nix/store/rcxy4c1gzix8a72q11djl7casf1d5d1l-oss-rebuild-0-unstable-2025-07-22.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/os/oss-rebuild/package.nix:34`
- **Outputs**:
  - `out`:  `/nix/store/rcxy4c1gzix8a72q11djl7casf1d5d1l-oss-rebuild-0-unstable-2025-07-22`

## 🔗 Dependencies

- [[9shhwi8jgbi88891rd3zkn41p96yvwdv-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[m3kib8kn2sb5rhy7ggxwrzq2vsgq9kgf-oss-rebuild-0-unstable-2025-07-22-go-modules]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:03:53 UTC*
