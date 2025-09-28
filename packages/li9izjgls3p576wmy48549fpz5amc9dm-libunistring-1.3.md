---
aliases:
  - libunistring
tags:
  - license/unknown
  - outputs/dev
  - outputs/doc
  - outputs/info
  - outputs/out
---

# libunistring

## 📝 Description

This library provides functions for manipulating Unicode strings
and for manipulating C strings according to the Unicode
standard.

GNU libunistring is for you if your application involves
non-trivial text processing, such as upper/lower case
conversions, line breaking, operations on words, or more
advanced analysis of text.  Text provided by the user can, in
general, contain characters of all kinds of scripts.  The text
processing functions provided by this library handle all scripts
and all languages.

libunistring is for you if your application already uses the ISO
C / POSIX <ctype.h>, <wctype.h> functions and the text it
operates on is provided by the user and can be in any language.

libunistring is also for you if your application uses Unicode
strings as internal in-memory representation.


## 📋 Package Information

- **Name**: `libunistring`
- **Version**: `1.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Unicode string library
- **Homepage**: [https://www.gnu.org/software/libunistring/](https://www.gnu.org/software/libunistring/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/li9izjgls3p576wmy48549fpz5amc9dm-libunistring-1.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/libraries/libunistring/default.nix:66`
- **Outputs**:
  - `dev`:  `/nix/store/li9izjgls3p576wmy48549fpz5amc9dm-libunistring-1.3`
  - `doc`:  `/nix/store/li9izjgls3p576wmy48549fpz5amc9dm-libunistring-1.3`
  - `info`:  `/nix/store/li9izjgls3p576wmy48549fpz5amc9dm-libunistring-1.3`
  - `out`:  `/nix/store/li9izjgls3p576wmy48549fpz5amc9dm-libunistring-1.3`

## 🔗 Dependencies

- [[05q48dcd4lgk4vh7wyk330gr2fr082i2-bootstrap-tools]]
- [[0lgvgcgg46k0844c37r68nd8bm97bz8b-bootstrap-stage0-glibc-iconv-bootstrapFiles]]
- [[4g9df6a0v0g5c2j5x23vv0i89aw2pd7l-bootstrap-stage2-stdenv-linux]]
- [[hvzm72bhbifyaj31z6xkz8pqlvv502pm-nuke-references]]
- [[rnpc4cjz42m8axyq6sa883i2h8dy6887-libunistring-1.3.tar.gz]]
- [[x004rwa259m1x0inl9g0gn9rkw4x84rv-update-autotools-gnu-config-scripts-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:03:14 UTC*
