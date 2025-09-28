---
aliases:
  - mcelog
tags:
  - license/unknown
  - outputs/out
---

# mcelog

## 📝 Description

The mcelog daemon accounts memory and some other errors in various ways
on modern x86 Linux systems. The daemon can be queried and/or execute
triggers when configurable error thresholds are exceeded. This is used to
implement a range of automatic predictive failure analysis algorithms,
including bad page offlining and automatic cache error handling. All
errors are logged to /var/log/mcelog or syslog or the journal.


## 📋 Package Information

- **Name**: `mcelog`
- **Version**: `206`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Log x86 machine checks: memory, IO, and CPU hardware errors
- **Homepage**: [http://mcelog.org/](http://mcelog.org/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/wydzxyl1hpakah9k1cqqab2yz4lvjh1m-mcelog-206.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/mcelog/default.nix:48`
- **Outputs**:
  - `out`:  `/nix/store/wydzxyl1hpakah9k1cqqab2yz4lvjh1m-mcelog-206`

## 🔗 Dependencies

- [[3z6dcp2i69nn7h8kwl6snf651i7ds14v-util-linux-minimal-2.41.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pn74jlqd5hg9rca73j9vwj7i1hypvmwx-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:15:51 UTC*
