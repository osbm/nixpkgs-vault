---
aliases:
  - gprolog
tags:
  - license/unknown
  - outputs/out
---

# gprolog

## 📝 Description

GNU Prolog is a free Prolog compiler with constraint solving
over finite domains developed by Daniel Diaz.

GNU Prolog accepts Prolog+constraint programs and produces
native binaries (like gcc does from a C source).  The obtained
executable is then stand-alone.  The size of this executable can
be quite small since GNU Prolog can avoid to link the code of
most unused built-in predicates.  The performances of GNU Prolog
are very encouraging (comparable to commercial systems).

Beside the native-code compilation, GNU Prolog offers a
classical interactive interpreter (top-level) with a debugger.

The Prolog part conforms to the ISO standard for Prolog with
many extensions very useful in practice (global variables, OS
interface, sockets,...).

GNU Prolog also includes an efficient constraint solver over
Finite Domains (FD).  This opens contraint logic programming to
the user combining the power of constraint programming to the
declarativity of logic programming.


## 📋 Package Information

- **Name**: `gprolog`
- **Version**: `1.5.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GNU Prolog, a free Prolog compiler with constraint solving over finite domains
- **Homepage**: [https://www.gnu.org/software/gprolog/](https://www.gnu.org/software/gprolog/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/va736wwlhdj3cgslpqjhzx3w83gs3f6z-gprolog-1.5.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/gp/gprolog/package.nix:43`
- **Outputs**:
  - `out`:  `/nix/store/va736wwlhdj3cgslpqjhzx3w83gs3f6z-gprolog-1.5.0`

## 🔗 Dependencies

- [[3g1acbx9nsh2j4k9zbn3qy2rdznzc76j-gprolog-1.5.0.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:54:15 UTC*
