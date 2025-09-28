---
aliases:
  - md4c
tags:
  - license/unknown
  - outputs/dev
  - outputs/lib
  - outputs/man
  - outputs/out
---

# md4c

## 📝 Description

MD4C is Markdown parser implementation in C, with the following features:

- Compliance: Generally, MD4C aims to be compliant to the latest version
  of CommonMark specification. Currently, we are fully compliant to
  CommonMark 0.30.
- Extensions: MD4C supports some commonly requested and accepted
  extensions. See below.
- Performance: MD4C is very fast.
- Compactness: MD4C parser is implemented in one source file and one
  header file. There are no dependencies other than standard C library.
- Embedding: MD4C parser is easy to reuse in other projects, its API is
  very straightforward: There is actually just one function, md_parse().
- Push model: MD4C parses the complete document and calls few callback
  functions provided by the application to inform it about a start/end of
  every block, a start/end of every span, and with any textual contents.
- Portability: MD4C builds and works on Windows and POSIX-compliant
  OSes. (It should be simple to make it run also on most other platforms,
  at least as long as the platform provides C standard library, including
  a heap memory management.)
- Encoding: MD4C by default expects UTF-8 encoding of the input
  document. But it can be compiled to recognize ASCII-only control
  characters (i.e. to disable all Unicode-specific code), or (on Windows)
  to expect UTF-16 (i.e. what is on Windows commonly called just
  "Unicode"). See more details below.
- Permissive license: MD4C is available under the MIT license.


## 📋 Package Information

- **Name**: `md4c`
- **Version**: `0.5.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Markdown parser made in C
- **Homepage**: [https://github.com/mity/md4c](https://github.com/mity/md4c)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/r6aq310a9f8ghh9lkdynjy4gscnl5x6b-md4c-0.5.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/md/md4c/package.nix:43`
- **Outputs**:
  - `dev`:  `/nix/store/r6aq310a9f8ghh9lkdynjy4gscnl5x6b-md4c-0.5.2`
  - `lib`:  `/nix/store/r6aq310a9f8ghh9lkdynjy4gscnl5x6b-md4c-0.5.2`
  - `man`:  `/nix/store/r6aq310a9f8ghh9lkdynjy4gscnl5x6b-md4c-0.5.2`
  - `out`:  `/nix/store/r6aq310a9f8ghh9lkdynjy4gscnl5x6b-md4c-0.5.2`

## 🔗 Dependencies

- [[4wshhxf69fwmpka1dmi00fc2ih229ylq-source]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/p68g5x2py9his32ma2pfxibfsnna1bkx-0001-fix-pkgconfig.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:16:18 UTC*
