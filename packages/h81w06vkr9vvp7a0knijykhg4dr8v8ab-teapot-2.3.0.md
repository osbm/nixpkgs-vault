---
aliases:
  - teapot
tags:
  - license/unknown
  - outputs/out
---

# teapot

## 📝 Description

Teapot is a compact spreadsheet software originally written by Michael
Haardt. It features a (n)curses-based text terminal interface, and
recently also a FLTK-based GUI.

These days, it may seem pointless having yet another spreadsheet program
(and one that doesn't even know how to load Microsoft Excel files). Its
compact size (130k for the ncurses executable, 140k for the GUI
executable, 300k for the self-contained Windows EXE) and the fact that it
can run across serial lines and SSH sessions make it an interesting choice
for embedded applications and as system administration utility, even more
so since it has a batch processing mode and comes with example code for
creating graphs from data sets.

Another interesting feature is its modern approach to spread sheet theory:
It sports true three-dimensional tables and iterative expressions. And
since it breaks compatibility with the usual notions of big spreadsheet
packages, it can also throw old syntactic cruft over board which many
spreadsheets still inherit from the days of VisiCalc on ancient CP/M
systems.


## 📋 Package Information

- **Name**: `teapot`
- **Version**: `2.3.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Table Editor And Planner, Or: Teapot
- **Homepage**: [https://github.com/museoa/teapot](https://github.com/museoa/teapot)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/h81w06vkr9vvp7a0knijykhg4dr8v8ab-teapot-2.3.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/te/teapot/package.nix:50`
- **Outputs**:
  - `out`:  `/nix/store/h81w06vkr9vvp7a0knijykhg4dr8v8ab-teapot-2.3.0`

## 🔗 Dependencies

- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[k63xnz1nr4a6154qrfx3lvhmjfdmiab4-source]]
- [[kd70yhxsscpb21f13h35vfnav448gr49-libtirpc-1.3.6]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/96dxp17i41hhvszf6qdnxnamkkrdnrhs-002-remove-help.patch`
- `/nix/store/igp9vws4yqp2fyfkjdc0clc4jd8y6sy7-001-fix-warning.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:05:07 UTC*
