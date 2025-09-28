---
aliases:
  - python312Packages.uv
tags:
  - license/unknown
  - maintainers/bengsparks
  - maintainers/GaetanLepage
  - maintainers/Prince213
  - outputs/dist
  - outputs/out
---

# python312Packages.uv

## 📝 Description

`uv` manages project dependencies and environments, with support for lockfiles, workspaces, and more.

Due to `uv`'s (over)eager fetching of dynamically-linked Python executables,
as well as vendoring of dynamically-linked libraries within Python modules distributed via PyPI,
NixOS users can run into issues when managing Python projects.
See the Nixpkgs Reference Manual entry for `uv` for information on how to mitigate these issues:
https://nixos.org/manual/nixpkgs/unstable/#sec-uv.

For building Python projects with `uv` and Nix outside of nixpkgs, check out `uv2nix` at https://github.com/pyproject-nix/uv2nix.


## 📋 Package Information

- **Name**: `python312Packages.uv`
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

- **Derivation Path**: `/nix/store/yyvs3vwwinp5kn2hhsvmw8rbzrnk3m48-python3.12-uv-0.8.14.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/uv/uv/package.nix:71`
- **Outputs**:
  - `dist`:  `/nix/store/yyvs3vwwinp5kn2hhsvmw8rbzrnk3m48-python3.12-uv-0.8.14`
  - `out`:  `/nix/store/yyvs3vwwinp5kn2hhsvmw8rbzrnk3m48-python3.12-uv-0.8.14`

## 🔗 Dependencies

- [[5vqqskgn6nfnms12lbr00qr1qmp2q4s8-uv-0.8.14]]
- [[5vsffdi0kgla24ca4l9bv0fxzc7s2qyk-pypa-build-hook.sh]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bki4kxsbvd13sz5a2bqr2b9y7vvgpmiy-python-runtime-deps-check-hook.sh]]
- [[di2np59yg9yf560yms5ff9188a5gnlbb-python-imports-check-hook.sh]]
- [[dkqa3dj2k1vqrmlyd6hrdf8dww0f5dr9-python-remove-tests-dir-hook]]
- [[fhrpbbzpqw4bvsy4ixq1fb9k2aaslnw0-python-catch-conflicts-hook]]
- [[fz0k8m7chhichwdj1h1g54hjfh80g3nm-python3-3.12.11]]
- [[g9bcdx47nd5qfi29d66nbxbwckd5g99m-python-namespaces-hook.sh]]
- [[hlfkbns49q14g2mzr63h2pa1lxpjsgnz-source]]
- [[j45jmjf6mwz46p7f0f8hjpnzi9pz2pzv-wrap-python-hook]]
- [[kh0627w4wff8syd1iis567224170xw3l-pypa-install-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[yky4w8wk411rw7j1w9zg61n6ahh7irxb-python3.12-hatchling-1.27.0]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:12:48 UTC*
