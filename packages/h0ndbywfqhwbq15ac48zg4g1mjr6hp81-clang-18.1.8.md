---
aliases:
  - llvmPackages_18.clang-unwrapped
tags:
  - license/unknown
  - maintainers/dtzWill
  - maintainers/emilazy
  - maintainers/Ericson2314
  - maintainers/lovek323
  - maintainers/alyssais
  - maintainers/RossComputerGuy
  - maintainers/rrbutani
  - maintainers/sternenseemann
  - outputs/debug
  - outputs/dev
  - outputs/lib
  - outputs/out
  - outputs/python
---

# llvmPackages_18.clang-unwrapped

## 📝 Description

The Clang project provides a language front-end and tooling
infrastructure for languages in the C language family (C, C++, Objective
C/C++, OpenCL, CUDA, and RenderScript) for the LLVM project.
It aims to deliver amazingly fast compiles, extremely useful error and
warning messages and to provide a platform for building great source
level tools. The Clang Static Analyzer and clang-tidy are tools that
automatically find bugs in your code, and are great examples of the sort
of tools that can be built using the Clang frontend as a library to
parse C/C++ code.


## 📋 Package Information

- **Name**: `llvmPackages_18.clang-unwrapped`
- **Version**: `18.1.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: C language family frontend for LLVM
- **Homepage**: [https://clang.llvm.org/](https://clang.llvm.org/)
- **License**: `unknown`
- **Platforms**: `aarch64-darwin`, `aarch64-freebsd`, `aarch64-genode`, `aarch64-linux`, `aarch64-netbsd`, `aarch64_be-none`, `aarch64-none`, `aarch64-windows`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `arm-none`, `armv6l-none`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `mipsel-netbsd`, `mips-none`, `mips64-none`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `powerpc-netbsd`, `powerpc-none`, `powerpcle-none`, `s390x-linux`, `s390x-none`, `wasm64-wasi`, `wasm32-wasi`, `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `i686-linux`, `x86_64-linux`, `i686-netbsd`, `x86_64-netbsd`, `i686-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `x86_64-windows`, `i686-windows`, `riscv32-linux`, `riscv64-linux`, `riscv32-netbsd`, `riscv64-netbsd`, `riscv32-none`, `riscv64-none`, `m68k-linux`, `m68k-netbsd`, `m68k-none`, `loongarch64-linux`
## 👥 Maintainers

- @dtzWill
- @emilazy
- @Ericson2314
- @lovek323
- @alyssais
- @RossComputerGuy
- @rrbutani
- @sternenseemann


## 🔧 Build Information

- **Derivation Path**: `/nix/store/h0ndbywfqhwbq15ac48zg4g1mjr6hp81-clang-18.1.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/compilers/llvm/common/clang/default.nix:217`
- **Outputs**:
  - `debug`:  `/nix/store/h0ndbywfqhwbq15ac48zg4g1mjr6hp81-clang-18.1.8`
  - `dev`:  `/nix/store/h0ndbywfqhwbq15ac48zg4g1mjr6hp81-clang-18.1.8`
  - `lib`:  `/nix/store/h0ndbywfqhwbq15ac48zg4g1mjr6hp81-clang-18.1.8`
  - `out`:  `/nix/store/h0ndbywfqhwbq15ac48zg4g1mjr6hp81-clang-18.1.8`
  - `python`:  `/nix/store/h0ndbywfqhwbq15ac48zg4g1mjr6hp81-clang-18.1.8`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[3h2pqwsp2izzlynp9gjar39hm70nnz89-libxml2-2.14.5]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[9w8if2g5vklksgsd8fxi6ghc8gqybhg7-llvm-tblgen-18.1.8]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[hirz8vsi85jng38vs8x5qdswd25nkd0f-tweak-tryCaptureVariable-for-unevaluated-lambdas.patch]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[l5zwb8dcj71fay65smjb8wb5lx9x2ynq-clang-src-18.1.8]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qlg2bdav0qi2lybdk6c40np65miri85r-clang-at-least-16-LLVMgold-path.patch]]
- [[rmcafjm4ks0fmbwgccin1n98ib4lnyxq-llvm-18.1.8]]

## 📁 Input Sources

- `/nix/store/4qh1l55wx654v0ls51dg1wdi5xy93w9b-purity.patch`
- `/nix/store/fk8qk07cl9m7wkjb0xc0hphbh3vrxfqh-gnu-install-dirs.patch`
- `/nix/store/km4bcg37mmvc1ns2h5lvbirhzmzrchjh-clang-unsupported-option.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/r989dk196nl9frhnfsa1lb7knhbyjxw6-separate-debug-info.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:14:56 UTC*
