---
aliases:
  - mobsql
tags:
  - license/unknown
  - maintainers/McSinyx
  - outputs/out
---

# mobsql

## 📝 Description

Mobsql is a Go library and command-line application
which facilitates loading one or multiple Mobility Database
source GTFS feed archives into a SQLite database.
Its internal SQLite schema mirrors GTFS's spec but adds a feed_id field
to each table (thus allowing multiple feeds to be loaded
to the database simulatenously).


## 📋 Package Information

- **Name**: `mobsql`
- **Version**: `0.9.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GTFS to SQLite import utility
- **Homepage**: [https://git.sr.ht/~mil/mobsql](https://git.sr.ht/~mil/mobsql)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @McSinyx


## 🔧 Build Information

- **Derivation Path**: `/nix/store/laf74hwv6w6ang9qnm5mfym27bi8zaw8-mobsql-0.9.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/mo/mobsql/package.nix:36`
- **Outputs**:
  - `out`:  `/nix/store/laf74hwv6w6ang9qnm5mfym27bi8zaw8-mobsql-0.9.0`

## 🔗 Dependencies

- [[1hpaq9ya01lvl13m4h9vsiz79wymjlw0-mobsql-0.9.0-go-modules]]
- [[6f2psfx7f4xqqwq4cr5gs6mz7m3p9x3m-sqlite-3.50.2]]
- [[av7vii8mg0yqq331z648za1q6jh293wn-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:22:05 UTC*
