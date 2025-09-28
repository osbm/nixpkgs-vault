---
aliases:
  - rocmPackages.llvm.openmp
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

# rocmPackages.llvm.openmp

## 📝 Description

The OpenMP subproject of LLVM contains the components required to build an
executable OpenMP program that are outside the compiler itself.
Contains the code for the runtime library against which code compiled by
"clang -fopenmp" must be linked before it can run and the library that
supports offload to target devices.


## 📋 Package Information

- **Name**: `rocmPackages.llvm.openmp`
- **Version**: `18.0.0-4182046534deb851753f0d962146e5176f648893`
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

- **Derivation Path**: `/nix/store/adq9zwz07l4f55hi50m44g5m8q60mhhl-openmp-18.0.0-4182046534deb851753f0d962146e5176f648893.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/compilers/llvm/common/openmp/default.nix:96`
- **Outputs**:
  - `dev`:  `/nix/store/adq9zwz07l4f55hi50m44g5m8q60mhhl-openmp-18.0.0-4182046534deb851753f0d962146e5176f648893`
  - `out`:  `/nix/store/adq9zwz07l4f55hi50m44g5m8q60mhhl-openmp-18.0.0-4182046534deb851753f0d962146e5176f648893`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[3h2pqwsp2izzlynp9gjar39hm70nnz89-libxml2-2.14.5]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7]]
- [[b7g7w8fpp6xqbq6z76rdyr1g5jww7f81-libffi-3.5.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gy9bk0wfd8f2mzzwj5rqbp00adqbl7ph-remove-references-to]]
- [[h7k994216vsr0lyvshx7apag1v95zkcb-source]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[phzlg0jzbv19x03jsrlg4l2yqixrrpsr-openmp-src-18.0.0-4182046534deb851753f0d962146e5176f648893]]
- [[piyxwj2cy8j2kvm0lr21hg1yqj91z6ix-rocm-device-libs-6.3.1]]
- [[rnxrff5q5w7d7rgfvlwixx8rphc2m416-python3.13-lit-18.1.8]]
- [[sigvq6pl6g3hdj8jc150q6zvg23r4nkh-rocm-runtime-6.3.3]]
- [[wryf1gsr7glsfkkprpgyyxrrw2b7j7q3-rocmcxx]]
- [[yivxpadvwqiylk61jn38vipdavm9n4xz-rocm-llvm-merge]]
- [[ynaam7inrdr9jkw6vwv7h9rr9y9l2bv4-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/1gps5df7559qbq3yb02xkc7x87iknhic-fix-find-tool.patch`
- `/nix/store/d3yy6k83srpdp1zzfy85gav15bm5w5ll-run-lit-directly.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:22:52 UTC*
