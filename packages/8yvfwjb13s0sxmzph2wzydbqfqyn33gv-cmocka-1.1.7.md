---
aliases:
  - cmocka
tags:
  - license/unknown
  - maintainers/kragniz
  - maintainers/rasendubi
  - outputs/out
---

# cmocka

## 📝 Description

There are a variety of C unit testing frameworks available however
many of them are fairly complex and require the latest compiler
technology.  Some development requires the use of old compilers which
makes it difficult to use some unit testing frameworks. In addition
many unit testing frameworks assume the code being tested is an
application or module that is targeted to the same platform that will
ultimately execute the test.  Because of this assumption many
frameworks require the inclusion of standard C library headers in the
code module being tested which may collide with the custom or
incomplete implementation of the C library utilized by the code under
test.

Cmocka only requires a test application is linked with the standard C
library which minimizes conflicts with standard C library headers.
Also, CMocka tries to avoid the use of some of the newer features of
C compilers.

This results in CMocka being a relatively small library that can be
used to test a variety of exotic code. If a developer wishes to
simply test an application with the latest compiler then other unit
testing frameworks may be preferable.

This is the successor of Google's Cmockery.


## 📋 Package Information

- **Name**: `cmocka`
- **Version**: `1.1.7`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Lightweight library to simplify and generalize unit tests for C
- **Homepage**: [https://cmocka.org/](https://cmocka.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @kragniz
- @rasendubi


## 🔧 Build Information

- **Derivation Path**: `/nix/store/8yvfwjb13s0sxmzph2wzydbqfqyn33gv-cmocka-1.1.7.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/cm/cmocka/package.nix:31`
- **Outputs**:
  - `out`:  `/nix/store/8yvfwjb13s0sxmzph2wzydbqfqyn33gv-cmocka-1.1.7`

## 🔗 Dependencies

- [[8wflw29rpkjvklyjc692j3gz8rn1qnm6-cmocka-1.1.7.tar.xz]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/y82v4gjkax335rnipz83qlswb9ig8x4m-uintptr_t.patch`

---
*Generated on 2025-09-27 11:50:48 UTC*
