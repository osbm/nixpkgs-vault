---
aliases:
  - slang
tags:
  - license/unknown
  - outputs/dev
  - outputs/doc
  - outputs/man
  - outputs/out
---

# slang

## 📝 Description

S-Lang is an interpreted language that was designed from the start to be
easily embedded into a program to provide it with a powerful extension
language. Examples of programs that use S-Lang as an extension language
include the jed text editor and the slrn newsreader. Although S-Lang does
not exist as a separate application, it is distributed with a quite
capable program called slsh ("slang-shell") that embeds the interpreter
and allows one to execute S-Lang scripts, or simply experiment with S-Lang
at an interactive prompt. Many of the the examples in this document are
presented in the context of one of the above applications.

S-Lang is also a programmer's library that permits a programmer to develop
sophisticated platform-independent software. In addition to providing the
S-Lang interpreter, the library provides facilities for screen management,
keymaps, low-level terminal I/O, etc. However, this document is concerned
only with the extension language and does not address these other features
of the S-Lang library. For information about the other components of the
library, the reader is referred to the S-Lang Library C Programmer's
Guide.


## 📋 Package Information

- **Name**: `slang`
- **Version**: `2.3.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Small, embeddable multi-platform programming library
- **Homepage**: [http://www.jedsoft.org/slang/](http://www.jedsoft.org/slang/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/6cbg6035am87v5123gnc2bkk2b4iya9m-slang-2.3.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sl/slang/package.nix:82`
- **Outputs**:
  - `dev`:  `/nix/store/6cbg6035am87v5123gnc2bkk2b4iya9m-slang-2.3.3`
  - `doc`:  `/nix/store/6cbg6035am87v5123gnc2bkk2b4iya9m-slang-2.3.3`
  - `man`:  `/nix/store/6cbg6035am87v5123gnc2bkk2b4iya9m-slang-2.3.3`
  - `out`:  `/nix/store/6cbg6035am87v5123gnc2bkk2b4iya9m-slang-2.3.3`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[jp1s66saixfsks8my9fc0n5xf2irnz1l-slang-2.3.3.tar.bz2]]
- [[mzg1vkyzabv01ja719b3zj9hzwkzhyk2-libpng-apng-1.6.49]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pp99kqhfn7z3a58pjkv4kiyrs62k0bj4-readline-8.3p1]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:11:56 UTC*
