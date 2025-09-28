---
aliases:
  - llvmPackages_18.openmp
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
  - outputs/dev
  - outputs/out
---

# llvmPackages_18.openmp

## 📝 Description

The OpenMP subproject of LLVM contains the components required to build an
executable OpenMP program that are outside the compiler itself.
Contains the code for the runtime library against which code compiled by
"clang -fopenmp" must be linked before it can run and the library that
supports offload to target devices.


## 📋 Package Information

- **Name**: `llvmPackages_18.openmp`
- **Version**: `18.1.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Support for the OpenMP language
- **Homepage**: [https://openmp.llvm.org/](https://openmp.llvm.org/)
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

- **Derivation Path**: `/nix/store/b0bi6vpwwrj3prn754pb9yffszzvq03d-openmp-18.1.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/compilers/llvm/common/openmp/default.nix:96`
- **Outputs**:
  - `dev`:  `/nix/store/b0bi6vpwwrj3prn754pb9yffszzvq03d-openmp-18.1.8`
  - `out`:  `/nix/store/b0bi6vpwwrj3prn754pb9yffszzvq03d-openmp-18.1.8`

## 🔗 Dependencies

- [[1if1280743w8v34kn07ycdzdwm04096x-openmp-src-18.1.8]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[h0ndbywfqhwbq15ac48zg4g1mjr6hp81-clang-18.1.8]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rmcafjm4ks0fmbwgccin1n98ib4lnyxq-llvm-18.1.8]]
- [[rnxrff5q5w7d7rgfvlwixx8rphc2m416-python3.13-lit-18.1.8]]

## 📁 Input Sources

- `/nix/store/1gps5df7559qbq3yb02xkc7x87iknhic-fix-find-tool.patch`
- `/nix/store/d3yy6k83srpdp1zzfy85gav15bm5w5ll-run-lit-directly.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:15:09 UTC*
