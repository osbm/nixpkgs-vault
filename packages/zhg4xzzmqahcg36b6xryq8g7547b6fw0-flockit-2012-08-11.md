---
aliases:
  - flockit
tags:
  - license/unknown
  - maintainers/basvandijk
  - outputs/out
---

# flockit

## 📝 Description

This library and tool exists solely because rsync doesn't have file locking.

It's not used like a normal library; you don't link against it, and you
don't have to patch your source code to use it. It's inserted between your
program and its libraries by use of LD_PRELOAD.

For example:

  $ env LD_PRELOAD=$(nix-build -A pkgs.flockit)/lib/libflockit.so FLOCKIT_FILE_PREFIX=test rsync SRC DEST

Besides the library a handy executable is provided which can simplify the above to:

  $ $(nix-build -A pkgs.flockit)/bin/flockit test rsync SRC DEST

Also see the following blog post:
https://www.swiftstack.com/blog/2012/08/15/old-school-monkeypatching/


## 📋 Package Information

- **Name**: `flockit`
- **Version**: `2012-08-11`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: LD_PRELOAD shim to add file locking to programs that don't do it (I'm looking at you, rsync!)
- **Homepage**: [https://github.com/smerritt/flockit](https://github.com/smerritt/flockit)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @basvandijk


## 🔧 Build Information

- **Derivation Path**: `/nix/store/zhg4xzzmqahcg36b6xryq8g7547b6fw0-flockit-2012-08-11.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/fl/flockit/package.nix:32`
- **Outputs**:
  - `out`:  `/nix/store/zhg4xzzmqahcg36b6xryq8g7547b6fw0-flockit-2012-08-11`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vx6lrbjvqid5sax9x8g4gznyinjis909-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:46:03 UTC*
