---
aliases:
  - gperf
tags:
  - license/unknown
  - outputs/out
---

# gperf

## 📝 Description

GNU gperf is a perfect hash function generator.  For a given
list of strings, it produces a hash function and hash table, in
form of C or C++ code, for looking up a value depending on the
input string.  The hash function is perfect, which means that
the hash table has no collisions, and the hash table lookup
needs a single string comparison only.

GNU gperf is highly customizable.  There are options for
generating C or C++ code, for emitting switch statements or
nested ifs instead of a hash table, and for tuning the algorithm
employed by gperf.


## 📋 Package Information

- **Name**: `gperf`
- **Version**: `3.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Perfect hash function generator
- **Homepage**: [https://www.gnu.org/software/gperf/](https://www.gnu.org/software/gperf/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/agnkcpgsw63ima1rywjanh2pqz1zpl18-gperf-3.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/gp/gperf/package.nix:19`
- **Outputs**:
  - `out`:  `/nix/store/agnkcpgsw63ima1rywjanh2pqz1zpl18-gperf-3.3`

## 🔗 Dependencies

- [[0jnglswxfkgfarh8i9ki81f77y11jcpb-gperf-3.3.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:53:50 UTC*
