---
aliases:
  - postgresql18Packages.pg_similarity
tags:
  - license/unknown
  - maintainers/danbst
  - outputs/out
---

# postgresql18Packages.pg_similarity

## 📝 Description

pg_similarity is an extension to support similarity queries on PostgreSQL. The implementation
is tightly integrated in the RDBMS in the sense that it defines operators so instead of the traditional
operators (= and <>) you can use ~~~ and ~!~ (any of these operators represents a similarity function).


## 📋 Package Information

- **Name**: `postgresql18Packages.pg_similarity`
- **Version**: `2021-01-12`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Extension to support similarity queries on PostgreSQL
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @danbst


## 🔧 Build Information

- **Derivation Path**: `/nix/store/281xp2rvfqa7k71989nh4y0wh40aaghz-pg_similarity-pg_similarity_1_0-unstable-2021-01-12.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/servers/sql/postgresql/ext/pg_similarity.nix:33`
- **Outputs**:
  - `out`:  `/nix/store/281xp2rvfqa7k71989nh4y0wh40aaghz-pg_similarity-pg_similarity_1_0-unstable-2021-01-12`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cx340rjf2mq1xhjqx09p26chaf1jzvw4-stdenv-linux]]
- [[fypssbwvqcix7nf3k8nd89x4c8b8j3sf-pg16.patch]]
- [[rz1w9vbb531fidl2zs20sksqqg6rqzqf-postgresql-18rc1]]
- [[w17jvrdf886sybywkhm2cqi6416scf7l-source]]
- [[zg379n8hpijy0w9bdajbvdqlxjhw1sbg-pg_config]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:26:15 UTC*
