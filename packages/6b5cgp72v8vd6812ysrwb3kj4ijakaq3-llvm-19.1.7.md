---
aliases:
  - libllvm
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
  - outputs/python
---

# libllvm

## 📝 Description

The LLVM Project is a collection of modular and reusable compiler and
toolchain technologies. Despite its name, LLVM has little to do with
traditional virtual machines. The name "LLVM" itself is not an acronym; it
is the full name of the project.
LLVM began as a research project at the University of Illinois, with the
goal of providing a modern, SSA-based compilation strategy capable of
supporting both static and dynamic compilation of arbitrary programming
languages. Since then, LLVM has grown to be an umbrella project consisting
of a number of subprojects, many of which are being used in production by
a wide variety of commercial and open source projects as well as being
widely used in academic research. Code in the LLVM project is licensed
under the "Apache 2.0 License with LLVM exceptions".


## 📋 Package Information

- **Name**: `libllvm`
- **Version**: `19.1.7`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Collection of modular and reusable compiler and toolchain technologies
- **Homepage**: [https://llvm.org/](https://llvm.org/)
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

- **Derivation Path**: `/nix/store/6b5cgp72v8vd6812ysrwb3kj4ijakaq3-llvm-19.1.7.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/compilers/llvm/common/llvm/default.nix:607`
- **Outputs**:
  - `dev`:  `/nix/store/6b5cgp72v8vd6812ysrwb3kj4ijakaq3-llvm-19.1.7`
  - `lib`:  `/nix/store/6b5cgp72v8vd6812ysrwb3kj4ijakaq3-llvm-19.1.7`
  - `out`:  `/nix/store/6b5cgp72v8vd6812ysrwb3kj4ijakaq3-llvm-19.1.7`
  - `python`:  `/nix/store/6b5cgp72v8vd6812ysrwb3kj4ijakaq3-llvm-19.1.7`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[3h2pqwsp2izzlynp9gjar39hm70nnz89-libxml2-2.14.5]]
- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[4f9j67x7cgs2hzjgyyzm8q6z1w2vgy41-which-2.23]]
- [[8d6v6zq8wrny4lch6rkyxjm7r3fc8izj-llvm-tblgen-19.1.7]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[b7g7w8fpp6xqbq6z76rdyr1g5jww7f81-libffi-3.5.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[c47qn40m6jz39d7b5x2jpjkirjz9dr9q-libbfd-plugin-api-header]]
- [[gqy7zxffiivh5zqchkgm58bj65pdh6gz-python3-3.13.7-env]]
- [[h11sg2mwhgj51zhzpii11c9sbllcras2-llvm-src-19.1.7]]
- [[hix6rm0f4rx0hsdp31vaky4zvr67v6r6-update-autotools-gnu-config-scripts-hook]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rwhhygxk2g4s5464b3klgbjv0g2q9rqd-libpfm-4.13.0]]

## 📁 Input Sources

- `/nix/store/0yxfdnfxbzczjxhgdpac81jnas194wfj-gnu-install-dirs.patch`
- `/nix/store/gr73nf6sca9nyzl88x58y3qxrav04yhd-polly-lit-cfg-add-libs-to-dylib-path.patch`
- `/nix/store/jh2pda7psaasq85b2rrigmkjdbl8d0a1-llvm-lit-cfg-add-libs-to-dylib-path.patch`
- `/nix/store/jqg6d73zcfi5qz70qvnr4raxr336mb1c-lit-shell-script-runner-set-dyld-library-path.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/x868j4ih7wqiivf6wr9m4g424jav0hpq-gnu-install-dirs-polly.patch`

---
*Generated on 2025-09-27 11:48:23 UTC*
