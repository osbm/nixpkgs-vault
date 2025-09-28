---
aliases:
  - fpart
tags:
  - license/unknown
  - maintainers/bjornfor
  - outputs/out
---

# fpart

## 📝 Description

Fpart is a tool that helps you sort file trees and pack them into bags
(called "partitions").

It splits a list of directories and file trees into a certain number of
partitions, trying to produce partitions with the same size and number of
files. It can also produce partitions with a given number of files or a
limited size.

Once generated, partitions are either printed as file lists to stdout
(default) or to files. Those lists can then be used by third party programs.

Fpart also includes a live mode, which allows it to crawl very large
filesystems and produce partitions in live. Hooks are available to act on
those partitions (e.g. immediately start a transfer using rsync(1))
without having to wait for the filesystem traversal job to be finished.
Used this way, fpart can be seen as a powerful data migration tool.


## 📋 Package Information

- **Name**: `fpart`
- **Version**: `1.7.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Split file trees into bags (called "partitions")
- **Homepage**: [http://contribs.martymac.org/](http://contribs.martymac.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @bjornfor


## 🔧 Build Information

- **Derivation Path**: `/nix/store/hllp7d1z4sr2f08s9xdg2np8l1v40kh8-fpart-1.7.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/fp/fpart/package.nix:29`
- **Outputs**:
  - `out`:  `/nix/store/hllp7d1z4sr2f08s9xdg2np8l1v40kh8-fpart-1.7.0`

## 🔗 Dependencies

- [[8lz1k676fc5kj8xv0dghnjxim6baf8n4-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:49:17 UTC*
