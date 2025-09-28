---
aliases:
  - pprof
tags:
  - license/unknown
  - maintainers/hzeller
  - outputs/out
---

# pprof

## 📝 Description

pprof reads a collection of profiling samples in profile.proto format and
generates reports to visualize and help analyze the data. It can generate
both text and graphical reports (through the use of the dot visualization
package).

profile.proto is a protocol buffer that describes a set of callstacks and
symbolization information. A common usage is to represent a set of sampled
callstacks from statistical profiling. The format is described on the
proto/profile.proto file. For details on protocol buffers, see
https://developers.google.com/protocol-buffers

Profiles can be read from a local file, or over http. Multiple profiles of
the same type can be aggregated or compared.

If the profile samples contain machine addresses, pprof can symbolize them
through the use of the native binutils tools (addr2line and nm).

This is not an official Google product.


## 📋 Package Information

- **Name**: `pprof`
- **Version**: `0-unstable-2025-03-02`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tool for visualization and analysis of profiling data
- **Homepage**: [https://github.com/google/pprof](https://github.com/google/pprof)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @hzeller


## 🔧 Build Information

- **Derivation Path**: `/nix/store/n44b642rfxvxxkxz5b54k27285xzj7fd-pprof-0-unstable-2025-03-02.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/pp/pprof/package.nix:30`
- **Outputs**:
  - `out`:  `/nix/store/n44b642rfxvxxkxz5b54k27285xzj7fd-pprof-0-unstable-2025-03-02`

## 🔗 Dependencies

- [[6b5cgp72v8vd6812ysrwb3kj4ijakaq3-llvm-19.1.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[njxyfrp9j8z1810p000svdnkd3iv09ng-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[zgqs7gp7qnvaf8mqjzkb69l3fs95r4kb-pprof-0-unstable-2025-03-02-go-modules]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:27:55 UTC*
