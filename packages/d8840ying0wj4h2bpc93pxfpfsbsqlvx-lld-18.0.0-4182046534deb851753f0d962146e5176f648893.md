---
aliases:
  - rocmPackages.llvm.lld
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

# rocmPackages.llvm.lld

## 📝 Description

LLD is a linker from the LLVM project that is a drop-in replacement for
system linkers and runs much faster than them. It also provides features
that are useful for toolchain developers.
The linker supports ELF (Unix), PE/COFF (Windows), Mach-O (macOS), and
WebAssembly in descending order of completeness. Internally, LLD consists
of several different linkers.


## 📋 Package Information

- **Name**: `rocmPackages.llvm.lld`
- **Version**: `18.0.0-4182046534deb851753f0d962146e5176f648893`
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

- **Derivation Path**: `/nix/store/d8840ying0wj4h2bpc93pxfpfsbsqlvx-lld-18.0.0-4182046534deb851753f0d962146e5176f648893.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/compilers/llvm/common/lld/default.nix:80`
- **Outputs**:
  - `dev`:  `/nix/store/d8840ying0wj4h2bpc93pxfpfsbsqlvx-lld-18.0.0-4182046534deb851753f0d962146e5176f648893`
  - `lib`:  `/nix/store/d8840ying0wj4h2bpc93pxfpfsbsqlvx-lld-18.0.0-4182046534deb851753f0d962146e5176f648893`
  - `out`:  `/nix/store/d8840ying0wj4h2bpc93pxfpfsbsqlvx-lld-18.0.0-4182046534deb851753f0d962146e5176f648893`

## 🔗 Dependencies

- [[0r8f6lywmdn501bmx9na9p216bx1i32j-empty-directory]]
- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[3h2pqwsp2izzlynp9gjar39hm70nnz89-libxml2-2.14.5]]
- [[6r5cldhv0mdkwwia0zdchk4aar0azvrd-gcc-14.3.0]]
- [[7rmhanqkrs6v54a41g6swrl5sn9fycp1-lld-18.1.8]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[ag9ibra8wa54hqwv9r4xi5dl6djn3fjg-llvm-18.0.0-4182046534deb851753f0d962146e5176f648893]]
- [[ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gy9bk0wfd8f2mzzwj5rqbp00adqbl7ph-remove-references-to]]
- [[kl62ks9jw7g1fwjfd213nqkp70r426yw-stdenv-linux]]
- [[kvysay8plzjaxgvj64sxz0b4d9xc25n0-binutils-wrapper-2.44]]
- [[s1x3ahhj9f54q3as17g5rad14nqyj4w9-lld-src-18.0.0-4182046534deb851753f0d962146e5176f648893]]

## 📁 Input Sources

- `/nix/store/cydfsqlg2j3hvnmprcai0sanmjx272fa-gnu-install-dirs.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:22:51 UTC*
