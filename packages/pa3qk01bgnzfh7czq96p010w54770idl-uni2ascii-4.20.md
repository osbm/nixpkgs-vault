---
aliases:
  - uni2ascii
tags:
  - license/unknown
  - outputs/out
---

# uni2ascii

## 📝 Description

This package provides conversion in both directions between UTF-8
Unicode and more than thirty 7-bit ASCII equivalents, including
RFC 2396 URI format and RFC 2045 Quoted Printable format, the
representations used in HTML, SGML, XML, OOXML, the Unicode
standard, Rich Text Format, POSIX portable charmaps, POSIX locale
specifications, and Apache log files, and the escapes used for
including Unicode in Ada, C, Common Lisp, Java, Pascal, Perl,
Postscript, Python, Scheme, and Tcl.

Such ASCII equivalents are useful when including Unicode text in
program source, when debugging, and when entering text into web
programs that can handle the Unicode character set but are not
8-bit safe. For example, MovableType, the blog software, truncates
posts as soon as it encounters a byte with the high bit
set. However, if Unicode is entered in the form of HTML numeric
character entities, Movable Type will not garble the post.

It also provides ways of converting non-ASCII characters to
similar ASCII characters, e.g. by stripping diacritics.


## 📋 Package Information

- **Name**: `uni2ascii`
- **Version**: `4.20`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Converts between UTF-8 and many 7-bit ASCII equivalents and back
- **Homepage**: [http://billposer.org/Software/uni2ascii.html](http://billposer.org/Software/uni2ascii.html)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/pa3qk01bgnzfh7czq96p010w54770idl-uni2ascii-4.20.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/un/uni2ascii/package.nix:26`
- **Outputs**:
  - `out`:  `/nix/store/pa3qk01bgnzfh7czq96p010w54770idl-uni2ascii-4.20`

## 🔗 Dependencies

- [[8hjjq2960dimihlvi93ax3s0l9lyn9gl-uni2ascii-4.20.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fwbcwh46kvpba3293m1grknywqsc6awv-uni2ascii-4.20.patch]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:18:54 UTC*
