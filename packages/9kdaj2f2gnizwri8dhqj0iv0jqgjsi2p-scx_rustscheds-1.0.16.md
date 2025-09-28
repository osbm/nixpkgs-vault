---
aliases:
  - scx.rustscheds
tags:
  - license/unknown
  - maintainers/johnrtitor
  - maintainers/Gliczy
  - outputs/out
---

# scx.rustscheds

## 📝 Description

This includes Rust based schedulers such as
scx_rustland, scx_bpfland, scx_lavd, scx_layered, scx_rlfifo.

::: {.note}
Sched-ext schedulers are only available on kernels version 6.12 or later.
It is recommended to use the latest kernel for the best compatibility.
:::


## 📋 Package Information

- **Name**: `scx.rustscheds`
- **Version**: `1.0.16`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Sched-ext Rust userspace schedulers
- **Homepage**: [https://github.com/sched-ext/scx](https://github.com/sched-ext/scx)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv6l-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv64-linux`, `s390x-linux`, `x86_64-linux`, `armv5tel-linux`, `armv7a-linux`, `m68k-linux`, `mips-linux`, `mips64-linux`, `mipsel-linux`, `mips64el-linux`, `riscv32-linux`
## 👥 Maintainers

- @johnrtitor
- @Gliczy


## 🔧 Build Information

- **Derivation Path**: `/nix/store/9kdaj2f2gnizwri8dhqj0iv0jqgjsi2p-scx_rustscheds-1.0.16.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/scx/scx_rustscheds.nix:57`
- **Outputs**:
  - `out`:  `/nix/store/9kdaj2f2gnizwri8dhqj0iv0jqgjsi2p-scx_rustscheds-1.0.16`

## 🔗 Dependencies

- [[0f5ann1sgwyp31vlfqqsnr95xzv3mzhf-cargo-1.89.0]]
- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[3bz4j2xzjl92yhiwfyhbz6gv4w1888bw-cargo-setup-hook.sh]]
- [[3ndchkhlxxw50k7nd48i9zdkhsr57mwh-cargo-install-hook.sh]]
- [[41s84g5y48afa0w1df9rjz6sny3k464r-protobuf-32.0]]
- [[4bycw2rdgf33gmn1z26knv8grxxh06w5-rustc-wrapper-1.89.0]]
- [[4cc0y6syxyxvjx1lh8ix60vxkly149fh-auditable-cargo-1.89.0]]
- [[5h6ng7076xwc5ckiy5m6bqhnh6r7ylqr-clang-wrapper-19.1.7]]
- [[5lcir7392b586pfmky4kxsprxa2yjq1v-scx_rustscheds-1.0.16-vendor]]
- [[96vv66p4biczw55qf9jhwqn7awwn861h-elfutils-0.193]]
- [[aj35hmramjk714nr632xb68wadb8xlh1-rust-bindgen-hook]]
- [[ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bl90a4zlrxx2krkq5l341j8flcv80a1v-source]]
- [[jvk6w0wmh9f50wh0xr7mb7faz9ipbmzv-libseccomp-2.6.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qi6337yh29r9ppqm262bf6vz0g13451b-cargo-build-hook.sh]]
- [[xqxbqs6qgnhvpkcai046s94jfrx8wb62-cargo-check-hook.sh]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:03:46 UTC*
