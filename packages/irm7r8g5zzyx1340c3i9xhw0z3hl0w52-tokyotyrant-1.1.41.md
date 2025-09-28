---
aliases:
  - tokyotyrant
tags:
  - license/unknown
  - outputs/out
---

# tokyotyrant

## 📝 Description

Tokyo Tyrant is a package of network interface to the DBM called
Tokyo Cabinet.  Though the DBM has high performance, you might
bother in case that multiple processes share the same database, or
remote processes access the database.  Thus, Tokyo Tyrant is
provided for concurrent and remote connections to Tokyo Cabinet.  It
is composed of the server process managing a database and its access
library for client applications.

Tokyo Tyrant is written in the C language, and provided as API of C,
Perl, and Ruby.  Tokyo Tyrant is available on platforms which have
API conforming to C99 and POSIX.  Tokyo Tyrant is a free software
licensed under the GNU Lesser General Public License.


## 📋 Package Information

- **Name**: `tokyotyrant`
- **Version**: `1.1.41`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Network interface of the Tokyo Cabinet DBM
- **Homepage**: [https://fallabs.com/tokyotyrant/](https://fallabs.com/tokyotyrant/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `powerpc64-linux`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/irm7r8g5zzyx1340c3i9xhw0z3hl0w52-tokyotyrant-1.1.41.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/to/tokyotyrant/package.nix:24`
- **Outputs**:
  - `out`:  `/nix/store/irm7r8g5zzyx1340c3i9xhw0z3hl0w52-tokyotyrant-1.1.41`

## 🔗 Dependencies

- [[ba9v4gz0jfqwyhbrwh382q8iqzdrxb3f-tokyotyrant-1.1.41.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dyss6iicdp09fdgs7q1glxm1661ca4hz-tokyocabinet-1.4.48]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:49:45 UTC*
