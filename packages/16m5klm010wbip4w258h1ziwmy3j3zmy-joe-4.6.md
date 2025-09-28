---
aliases:
  - joe
tags:
  - license/unknown
  - outputs/out
---

# joe

## 📝 Description

JOE (Joe's Own Editor) is a full featured terminal-based screen editor
which is distributed under the GNU General Public License (GPL). JOE has
been around since 1988 and comes standard with many Linux distributions.

JOE is being maintained by its original author Joseph Allen, plus all of
the people who send bug reports, feature suggestions and patches to the
project web site. JOE is hosted by SourceForge.net and its source code is
controlled under Mercurial.

JOE is a blending of MicroPro's venerable microcomputer word processor
WordStar and Richard Stallman's famous LISP based text editor GNU-EMACS
(but it does not use code from either program): most of the basic editing
keys are the same as in WordStar as is the overall feel of the editor. JOE
also has some of the key bindings and many of the powerful features of
EMACS.

JOE is written in C and its only dependency is libc. This makes JOE very
easy to build (just "configure" and "make install"), making it feasible to
include on small systems and recovery disks. The compiled binary is about
300K in x86. Note that JOE can use either the termcap or terminfo terminal
capabilities databases (or a built-in termcap entry for ANSI
terminals). The choice is controlled by a "configure" option. If terminfo
is used, a library is required to access the database (on some systems
this library is ncurses, but JOE does not use curses to control the
terminal - it has its own code for this).


## 📋 Package Information

- **Name**: `joe`
- **Version**: `4.6`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Full featured terminal-based screen editor
- **Homepage**: [https://joe-editor.sourceforge.io](https://joe-editor.sourceforge.io)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/16m5klm010wbip4w258h1ziwmy3j3zmy-joe-4.6.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/jo/joe/package.nix:19`
- **Outputs**:
  - `out`:  `/nix/store/16m5klm010wbip4w258h1ziwmy3j3zmy-joe-4.6`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vak65vkzigg78h0bg50llr1ix2b7nn6c-joe-4.6.tar.gz]]

## 📁 Input Sources

- `/nix/store/ajc6c3w790mvg8p8hdhiibwc9hk3dnxv-macos-fix.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:10:25 UTC*
