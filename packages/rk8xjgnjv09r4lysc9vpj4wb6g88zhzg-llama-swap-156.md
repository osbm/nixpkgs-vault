---
aliases:
  - llama-swap
tags:
  - license/unknown
  - maintainers/06kellyjac
  - maintainers/podium868909
  - outputs/out
---

# llama-swap

## 📝 Description

llama-swap is a light weight, transparent proxy server that provides
automatic model swapping to llama.cpp's server.

When a request is made to an OpenAI compatible endpoint, llama-swap will
extract the `model` value and load the appropriate server configuration to
serve it. If the wrong upstream server is running, it will be replaced
with the correct one. This is where the "swap" part comes in. The upstream
server is automatically swapped to the correct one to serve the request.

In the most basic configuration llama-swap handles one model at a time.
For more advanced use cases, the `groups` feature allows multiple models
to be loaded at the same time. You have complete control over how your
system resources are used.


## 📋 Package Information

- **Name**: `llama-swap`
- **Version**: `156`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Model swapping for llama.cpp (or any local OpenAPI compatible server)
- **Homepage**: [https://github.com/mostlygeek/llama-swap](https://github.com/mostlygeek/llama-swap)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @06kellyjac
- @podium868909


## 🔧 Build Information

- **Derivation Path**: `/nix/store/rk8xjgnjv09r4lysc9vpj4wb6g88zhzg-llama-swap-156.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ll/llama-swap/package.nix:97`
- **Outputs**:
  - `out`:  `/nix/store/rk8xjgnjv09r4lysc9vpj4wb6g88zhzg-llama-swap-156`

## 🔗 Dependencies

- [[4vplisw2ycwjnnnfrjkza3mqnp4vcz4f-llama-swap-ui-156]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[kz6l9whfpar7jcbx3q1arjfymlv45bf8-source]]
- [[lzvy25g887aypn07ah8igv72z7b9jb88-version-check-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[rjqk0lcrkrs8innflwn0n8ybkms11mbi-llama-swap-156-go-modules]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:14:25 UTC*
