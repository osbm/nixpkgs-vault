---
aliases:
  - postgresql17Packages.apache_datasketches
tags:
  - license/unknown
  - maintainers/mmusnjak
  - outputs/out
---

# postgresql17Packages.apache_datasketches

## 📝 Description

apache_datasketches is an extension to support approximate algorithms on PostgreSQL. The implementation
is based on the Apache Datasketches CPP library, and provides support for HyperLogLog,
Compressed Probabilistic Counting, KLL, Frequent strings, and Theta sketches.


## 📋 Package Information

- **Name**: `postgresql17Packages.apache_datasketches`
- **Version**: `1.7.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: PostgreSQL extension providing approximate algorithms for distinct item counts, quantile estimation and frequent items detection
- **Homepage**: [https://datasketches.apache.org/](https://datasketches.apache.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @mmusnjak


## 🔧 Build Information

- **Derivation Path**: `/nix/store/6mhzwixvsblss6jay5dl09gacx7kf3a8-apache_datasketches-1.7.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/servers/sql/postgresql/ext/apache_datasketches.nix:60`
- **Outputs**:
  - `out`:  `/nix/store/6mhzwixvsblss6jay5dl09gacx7kf3a8-apache_datasketches-1.7.0`

## 🔗 Dependencies

- [[0ihzm6m1z1842bwzpm4g2957vxyr7d6m-postgresql-17.6]]
- [[azrshra2jw0nwwa1aqwywljqzirdvr9m-datasketches-cpp]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cx340rjf2mq1xhjqx09p26chaf1jzvw4-stdenv-linux]]
- [[ig8ig14ah33fyqm4zwhnyhlppvqwx0xb-datasketches-postgresql]]
- [[qn9argmfkx5j3gzmkzsp6zmiyxp93arc-boost-1.86.0]]
- [[y00m4yblm4fyn9dqza148d72s67ad6ak-pg_config]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:24:41 UTC*
