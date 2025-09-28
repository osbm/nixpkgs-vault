---
aliases:
  - lld_20
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
  - outputs/lib
  - outputs/out
---

# lld_20

## 📝 Description

LLD is a linker from the LLVM project that is a drop-in replacement for
system linkers and runs much faster than them. It also provides features
that are useful for toolchain developers.
The linker supports ELF (Unix), PE/COFF (Windows), Mach-O (macOS), and
WebAssembly in descending order of completeness. Internally, LLD consists
of several different linkers.


## 📋 Package Information

- **Name**: `lld_20`
- **Version**: `20.1.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: LLVM linker (unwrapped)
- **Homepage**: [https://lld.llvm.org/](https://lld.llvm.org/)
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

- **Derivation Path**: `/nix/store/5hfg8nw9n1fkz5hmnpfzjdwhpz93cibc-lld-20.1.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/compilers/llvm/common/lld/default.nix:80`
- **Outputs**:
  - `dev`:  `/nix/store/5hfg8nw9n1fkz5hmnpfzjdwhpz93cibc-lld-20.1.8`
  - `lib`:  `/nix/store/5hfg8nw9n1fkz5hmnpfzjdwhpz93cibc-lld-20.1.8`
  - `out`:  `/nix/store/5hfg8nw9n1fkz5hmnpfzjdwhpz93cibc-lld-20.1.8`

## 🔗 Dependencies

- [[3h2pqwsp2izzlynp9gjar39hm70nnz89-libxml2-2.14.5]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[b8ss0hfixqq8kf58969818yl2lrra4pq-lld-src-20.1.8]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[k0m6xbclli4ryzvyj58fg2i5i1yaxzyr-llvm-20.1.8]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[r9wm4y656lkk8lk4g0fb7mzr8ym2z6jr-llvm-tblgen-20.1.8]]

## 📁 Input Sources

- `/nix/store/cydfsqlg2j3hvnmprcai0sanmjx272fa-gnu-install-dirs.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:14:27 UTC*
