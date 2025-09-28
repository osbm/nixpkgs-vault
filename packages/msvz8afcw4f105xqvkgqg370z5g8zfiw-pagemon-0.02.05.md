---
aliases:
  - pagemon
tags:
  - license/unknown
  - outputs/out
---

# pagemon

## 📝 Description

pagemon is an ncurses based interactive memory/page monitoring tool
allowing one to browse the memory map of an active running process
on Linux.
pagemon reads the PTEs of a given process and display the soft/dirty
activity in real time. The tool identifies the type of memory mapping
a page belongs to, so one can easily scan through memory looking at
pages of memory belonging data, code, heap, stack, anonymous mappings
or even swapped-out pages.


## 📋 Package Information

- **Name**: `pagemon`
- **Version**: `0.02.05`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Interactive memory/page monitor for Linux
- **Homepage**: [https://github.com/ColinIanKing/pagemon](https://github.com/ColinIanKing/pagemon)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/msvz8afcw4f105xqvkgqg370z5g8zfiw-pagemon-0.02.05.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/pa/pagemon/package.nix:29`
- **Outputs**:
  - `out`:  `/nix/store/msvz8afcw4f105xqvkgqg370z5g8zfiw-pagemon-0.02.05`

## 🔗 Dependencies

- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[62yqyf7rpb1sj13all36bw63x4myyxd2-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:06:26 UTC*
