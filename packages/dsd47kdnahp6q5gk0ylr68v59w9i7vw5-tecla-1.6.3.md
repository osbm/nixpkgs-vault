---
aliases:
  - tecla
tags:
  - license/unknown
  - outputs/man
  - outputs/out
---

# tecla

## 📝 Description

The tecla library provides UNIX and LINUX programs with interactive
command line editing facilities, similar to those of the UNIX tcsh
shell. In addition to simple command-line editing, it supports recall of
previously entered command lines, TAB completion of file names or other
tokens, and in-line wild-card expansion of filenames. The internal
functions which perform file-name completion and wild-card expansion are
also available externally for optional use by programs.

In addition, the library includes a path-searching module. This allows an
application to provide completion and lookup of files located in UNIX
style paths. Although not built into the line editor by default, it can
easily be called from custom tab-completion callback functions. This was
originally conceived for completing the names of executables and
providing a way to look up their locations in the user's PATH environment
variable, but it can easily be asked to look up and complete other types
of files in any list of directories.

Note that special care has been taken to allow the use of this library in
threaded programs. The option to enable this is discussed in the
Makefile, and specific discussions of thread safety are presented in the
included man pages.


## 📋 Package Information

- **Name**: `tecla`
- **Version**: `1.6.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Command-line editing library
- **Homepage**: [https://www.astro.caltech.edu/~mcs/tecla/](https://www.astro.caltech.edu/~mcs/tecla/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/dsd47kdnahp6q5gk0ylr68v59w9i7vw5-tecla-1.6.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/te/tecla/package.nix:32`
- **Outputs**:
  - `man`:  `/nix/store/dsd47kdnahp6q5gk0ylr68v59w9i7vw5-tecla-1.6.3`
  - `out`:  `/nix/store/dsd47kdnahp6q5gk0ylr68v59w9i7vw5-tecla-1.6.3`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[hybmphrp67l0f3zs1rxhlgy16j8dp47n-libtecla-1.6.3.tar.gz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:05:13 UTC*
