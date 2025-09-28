---
aliases:
  - python313Packages.uv
tags:
  - license/unknown
  - maintainers/bengsparks
  - maintainers/GaetanLepage
  - maintainers/Prince213
  - outputs/dist
  - outputs/out
---

# python313Packages.uv

## 📝 Description

`uv` manages project dependencies and environments, with support for lockfiles, workspaces, and more.

Due to `uv`'s (over)eager fetching of dynamically-linked Python executables,
as well as vendoring of dynamically-linked libraries within Python modules distributed via PyPI,
NixOS users can run into issues when managing Python projects.
See the Nixpkgs Reference Manual entry for `uv` for information on how to mitigate these issues:
https://nixos.org/manual/nixpkgs/unstable/#sec-uv.

For building Python projects with `uv` and Nix outside of nixpkgs, check out `uv2nix` at https://github.com/pyproject-nix/uv2nix.


## 📋 Package Information

- **Name**: `python313Packages.uv`
- **Version**: `0.8.14`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Extremely fast Python package installer and resolver, written in Rust
- **Homepage**: [https://github.com/astral-sh/uv](https://github.com/astral-sh/uv)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv6l-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv64-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `powerpc-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `i686-windows`, `x86_64-windows`, `armv5tel-linux`, `armv7a-linux`, `m68k-linux`, `mips-linux`, `mips64-linux`, `mipsel-linux`, `mips64el-linux`, `riscv32-linux`, `armv6l-netbsd`, `mipsel-netbsd`, `riscv64-netbsd`, `x86_64-redox`, `wasm32-wasi`
## 👥 Maintainers

- @bengsparks
- @GaetanLepage
- @Prince213


## 🔧 Build Information

- **Derivation Path**: `/nix/store/0ackig45ddapwb4rcrdj8ifm507gwd8x-python3.13-uv-0.8.14.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/uv/uv/package.nix:71`
- **Outputs**:
  - `dist`:  `/nix/store/0ackig45ddapwb4rcrdj8ifm507gwd8x-python3.13-uv-0.8.14`
  - `out`:  `/nix/store/0ackig45ddapwb4rcrdj8ifm507gwd8x-python3.13-uv-0.8.14`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[5vqqskgn6nfnms12lbr00qr1qmp2q4s8-uv-0.8.14]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[dnbzpphxbd6h31n44gfwbg1qf9q03wcr-pypa-build-hook.sh]]
- [[fmgak3lvqw3ff8wym1v40kgi0b5i1iza-python-runtime-deps-check-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[hgivx7dr21v7dr2p4jkrmwb7b3d08ri8-python3.13-hatchling-1.27.0]]
- [[hlfkbns49q14g2mzr63h2pa1lxpjsgnz-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:40:53 UTC*
