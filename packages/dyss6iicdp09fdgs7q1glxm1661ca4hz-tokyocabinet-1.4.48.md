---
aliases:
  - tokyocabinet
tags:
  - license/unknown
  - outputs/out
---

# tokyocabinet

## 📝 Description

Tokyo Cabinet is a library of routines for managing a database. The
database is a simple data file containing records, each is a pair of
a key and a value.  Every key and value is serial bytes with
variable length.  Both binary data and character string can be used
as a key and a value.  There is neither concept of data tables nor
data types.  Records are organized in hash table, B+ tree, or
fixed-length array.

Tokyo Cabinet is developed as the successor of GDBM and QDBM on the
following purposes.  They are achieved and Tokyo Cabinet replaces
conventional DBM products: improves space efficiency, improves time
efficiency, improves parallelism, improves usability, improves
robustness, supports 64-bit architecture.


## 📋 Package Information

- **Name**: `tokyocabinet`
- **Version**: `1.4.48`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tokyo Cabinet: a modern implementation of DBM
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/dyss6iicdp09fdgs7q1glxm1661ca4hz-tokyocabinet-1.4.48.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/to/tokyocabinet/package.nix:30`
- **Outputs**:
  - `out`:  `/nix/store/dyss6iicdp09fdgs7q1glxm1661ca4hz-tokyocabinet-1.4.48`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gh787a0973rc5ang8lvdv0v39x8a2lnv-tokyocabinet-1.4.48.tar.gz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[y4lfwlviqzkdrk9973a02vpl0fk4h1vy-bzip2-1.0.8]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:49:41 UTC*
