---
aliases:
  - ycmd
tags:
  - license/unknown
  - maintainers/rasendubi
  - maintainers/LnL7
  - maintainers/melnary
  - maintainers/S0AndS0
  - outputs/out
---

# ycmd

## 📝 Description

Note if YouCompleteMe Vim plugin complains with;

> ImportError: Python version mismatch: module was compiled for Python 3.13, but the interpreter version is incompatible: 3.10.18

...  then set something similar to following in `programs.vim.extraConfig`;

    let g:ycm_server_python_interpreter = "/nix/store/829wb290i87wngxlh404klwxql5v18p4-python3-3.13.7/bin/python3.13"


## 📋 Package Information

- **Name**: `ycmd`
- **Version**: `0-unstable-2025-06-16`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Code-completion and comprehension server
- **Homepage**: [https://github.com/ycm-core/ycmd](https://github.com/ycm-core/ycmd)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @rasendubi
- @LnL7
- @melnary
- @S0AndS0


## 🔧 Build Information

- **Derivation Path**: `/nix/store/m4l3qgf6yy9hvxfyn236w4rsjlwgqac3-ycmd-0-unstable-2025-06-16.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/yc/ycmd/package.nix:125`
- **Outputs**:
  - `out`:  `/nix/store/m4l3qgf6yy9hvxfyn236w4rsjlwgqac3-ycmd-0-unstable-2025-06-16`

## 🔗 Dependencies

- [[024jr1qcqk0m9gp6290q01y0xz6hy9zp-source]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[6b5cgp72v8vd6812ysrwb3kj4ijakaq3-llvm-19.1.7]]
- [[77fx3zgcfw9vhnkr9qhjrmh2krq307i7-clang-19.1.7]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[d3csq1x0prv52q7mlah8bqzw1pc85vdl-python3.13-jedi-0.19.2]]
- [[d8830xs53w6yjw5lmq1nyjbw15kdhaf1-python3.13-jedi-language-server-0.45.1]]
- [[hxyly4ds7g5wpxgl03nh6crfbzmn1sgi-godef-1.1.2]]
- [[i3ph2z8ayfgsqlrj9y2gwiyv3fmj6w10-boost-1.87.0]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[jkbyhrqbsm1r867x1g7nybnlwp2kix0a-typescript-5.9.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pn3n48g8f57zys8y6ihgq8ny0q5gbsn2-python3.13-legacy-cgi-2.6.3]]
- [[rvpjjfiiw4v9rmv7sm33brd6wyznny0a-gopls-0.20.0]]
- [[v2y8xr2c3sd1vsw5ax78xhxs8k93wa92-abseil-cpp-20250127.1]]
- [[wh4vsg3idkzi7vy4059xfxsjjsaj49l2-rust-analyzer-2025-08-25]]
- [[y3lnzs7gck52p15xxnabvy3cpp1pssvd-python3.13-pybind11-2.13.6]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:11:16 UTC*
