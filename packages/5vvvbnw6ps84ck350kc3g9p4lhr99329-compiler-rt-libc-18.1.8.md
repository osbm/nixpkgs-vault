---
aliases:
  - llvmPackages_18.compiler-rt
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

# llvmPackages_18.compiler-rt

## 📝 Description

The compiler-rt project provides highly tuned implementations of the
low-level code generator support routines like "__fixunsdfdi" and other
calls generated when a target doesn't have a short sequence of native
instructions to implement a core IR operation. It also provides
implementations of run-time libraries for dynamic testing tools such as
AddressSanitizer, ThreadSanitizer, MemorySanitizer, and DataFlowSanitizer.


## 📋 Package Information

- **Name**: `llvmPackages_18.compiler-rt`
- **Version**: `18.1.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Compiler runtime libraries
- **Homepage**: [https://compiler-rt.llvm.org/](https://compiler-rt.llvm.org/)
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

- **Derivation Path**: `/nix/store/5vvvbnw6ps84ck350kc3g9p4lhr99329-compiler-rt-libc-18.1.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/compilers/llvm/common/compiler-rt/default.nix:265`
- **Outputs**:
  - `dev`:  `/nix/store/5vvvbnw6ps84ck350kc3g9p4lhr99329-compiler-rt-libc-18.1.8`
  - `out`:  `/nix/store/5vvvbnw6ps84ck350kc3g9p4lhr99329-compiler-rt-libc-18.1.8`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[3kgj31l4fhkbp0s74bzl7zvrr1v6aymc-libxcrypt-4.4.38]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[b7j4cawscm1pdnysbqv19g08ksazdhyb-compiler-rt-src-18.1.8]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rmcafjm4ks0fmbwgccin1n98ib4lnyxq-llvm-18.1.8]]

## 📁 Input Sources

- `/nix/store/8mvcwn96881p7v9zgjgl6n37128ppfig-armv6-no-ldrexd-strexd.patch`
- `/nix/store/iy4wp1wspv98nl2hlqn2w7y5pghfl9jh-normalize-var.patch`
- `/nix/store/j9lspxnlbkrcskxpxg7q6nb74wnn6v2b-darwin-plistbuddy-workaround.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/qvyl9jgm1a1mlix44qbsgrd1ipwciamk-X86-support-extension.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/yqs4ahb8dx96hh2bsa5wgga9kca7lpkg-armv6-scudo-libatomic.patch`

---
*Generated on 2025-09-27 12:15:01 UTC*
