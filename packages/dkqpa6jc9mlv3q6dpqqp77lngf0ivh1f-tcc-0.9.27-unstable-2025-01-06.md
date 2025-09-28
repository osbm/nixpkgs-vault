---
aliases:
  - tinycc
tags:
  - license/unknown
  - maintainers/joachifm
  - maintainers/onemoresuza
  - outputs/dev
  - outputs/doc
  - outputs/info
  - outputs/lib
  - outputs/man
  - outputs/out
---

# tinycc

## 📝 Description

TinyCC (aka TCC) is a small but hyper fast C compiler.  Unlike other C
compilers, it is meant to be self-sufficient: you do not need an external
assembler or linker because TCC does that for you.

TCC compiles so fast that even for big projects Makefiles may not be
necessary.

TCC not only supports ANSI C, but also most of the new ISO C99 standard
and many GNU C extensions.

TCC can also be used to make C scripts, i.e. pieces of C source that you
run as a Perl or Python script.  Compilation is so fast that your script
will be as fast as if it was an executable.

TCC can also automatically generate memory and bound checks while allowing
all C pointers operations.  TCC can do these checks even if non patched
libraries are used.

With libtcc, you can use TCC as a backend for dynamic code generation.


## 📋 Package Information

- **Name**: `tinycc`
- **Version**: `0.9.27-unstable-2025-01-06`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Small, fast, and embeddable C compiler and interpreter
- **Homepage**: [https://repo.or.cz/tinycc.git](https://repo.or.cz/tinycc.git)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @joachifm
- @onemoresuza


## 🔧 Build Information

- **Derivation Path**: `/nix/store/dkqpa6jc9mlv3q6dpqqp77lngf0ivh1f-tcc-0.9.27-unstable-2025-01-06.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ti/tinycc/package.nix:118`
- **Outputs**:
  - `dev`:  `/nix/store/dkqpa6jc9mlv3q6dpqqp77lngf0ivh1f-tcc-0.9.27-unstable-2025-01-06`
  - `doc`:  `/nix/store/dkqpa6jc9mlv3q6dpqqp77lngf0ivh1f-tcc-0.9.27-unstable-2025-01-06`
  - `info`:  `/nix/store/dkqpa6jc9mlv3q6dpqqp77lngf0ivh1f-tcc-0.9.27-unstable-2025-01-06`
  - `lib`:  `/nix/store/dkqpa6jc9mlv3q6dpqqp77lngf0ivh1f-tcc-0.9.27-unstable-2025-01-06`
  - `man`:  `/nix/store/dkqpa6jc9mlv3q6dpqqp77lngf0ivh1f-tcc-0.9.27-unstable-2025-01-06`
  - `out`:  `/nix/store/dkqpa6jc9mlv3q6dpqqp77lngf0ivh1f-tcc-0.9.27-unstable-2025-01-06`

## 🔗 Dependencies

- [[4f9j67x7cgs2hzjgyyzm8q6z1w2vgy41-which-2.23]]
- [[4z1g6ham9rppbl7w03gfv55078bs2xrv-source]]
- [[7avb9yb1m38hw5sxb707fiipkq2mqikj-copy-pkg-config-items-hook]]
- [[b4pa5k4if2jl33f1ynicjwz2nihy4z3c-texinfo-7.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[f1305aqkwkvrpxy69rxbvs54ixmlm1dq-glibc-2.40-66]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vj7pngx5v14dka796q1c3n88340l509b-libtcc.pc]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:12:02 UTC*
