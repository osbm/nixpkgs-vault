---
aliases:
  - bfg-repo-cleaner
tags:
  - license/unknown
  - maintainers/changlinli
  - outputs/out
---

# bfg-repo-cleaner

## 📝 Description

The BFG is a simpler, faster alternative to git-filter-branch for
cleansing bad data out of your Git repository history, in particular removing
crazy big files and removing passwords, credentials, and other private data.

The git-filter-branch command is enormously powerful and can do things
that the BFG can't - but the BFG is much better for the tasks above, because
it's faster (10-720x), simpler (dedicated to just removing things), and
beautiful (can use Scala instead of bash to script customizations).


## 📋 Package Information

- **Name**: `bfg-repo-cleaner`
- **Version**: `1.15.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Removes large or troublesome blobs in a git repository like git-filter-branch does, but faster
- **Homepage**: [https://rtyley.github.io/bfg-repo-cleaner/](https://rtyley.github.io/bfg-repo-cleaner/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @changlinli


## 🔧 Build Information

- **Derivation Path**: `/nix/store/lirqh8dnqchrg664sjral9p7fhigky2v-bfg-repo-cleaner-1.15.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/bf/bfg-repo-cleaner/package.nix:43`
- **Outputs**:
  - `out`:  `/nix/store/lirqh8dnqchrg664sjral9p7fhigky2v-bfg-repo-cleaner-1.15.0`

## 🔗 Dependencies

- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[47vzy8p7cx5qiqqqncylhwwlm4hjvkf2-openjdk-21.0.8+9]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i7gkkhy6lyg6ld0i7kdf5hhpi78yxpw4-bfg-1.15.0.jar]]
- [[lzvy25g887aypn07ah8igv72z7b9jb88-version-check-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:49:43 UTC*
