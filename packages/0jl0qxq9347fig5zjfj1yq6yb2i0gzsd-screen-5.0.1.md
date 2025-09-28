---
aliases:
  - screen
tags:
  - license/unknown
  - outputs/out
---

# screen

## 📝 Description

GNU Screen is a full-screen window manager that multiplexes a physical
terminal between several processes, typically interactive shells.
Each virtual terminal provides the functions of the DEC VT100
terminal and, in addition, several control functions from the ANSI
X3.64 (ISO 6429) and ISO 2022 standards (e.g., insert/delete line
and support for multiple character sets).  There is a scrollback
history buffer for each virtual terminal and a copy-and-paste
mechanism that allows the user to move text regions between windows.
When screen is called, it creates a single window with a shell in it
(or the specified command) and then gets out of your way so that you
can use the program as you normally would.  Then, at any time, you
can create new (full-screen) windows with other programs in them
(including more shells), kill the current window, view a list of the
active windows, turn output logging on and off, copy text between
windows, view the scrollback history, switch between windows, etc.
All windows run their programs completely independent of each other.
Programs continue to run when their window is currently not visible
and even when the whole screen session is detached from the users
terminal.


## 📋 Package Information

- **Name**: `screen`
- **Version**: `5.0.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Window manager that multiplexes a physical terminal
- **Homepage**: [https://www.gnu.org/software/screen/](https://www.gnu.org/software/screen/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/0jl0qxq9347fig5zjfj1yq6yb2i0gzsd-screen-5.0.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sc/screen/package.nix:48`
- **Outputs**:
  - `out`:  `/nix/store/0jl0qxq9347fig5zjfj1yq6yb2i0gzsd-screen-5.0.1`

## 🔗 Dependencies

- [[15gr30a66fsp8rr4kx1rimfvnra7ws4d-0001-test-fix-unit-tests.patch?file_id=57558]]
- [[3kgj31l4fhkbp0s74bzl7zvrr1v6aymc-libxcrypt-4.4.38]]
- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[a5z7m6hvdvsl4xq0r7rcra11sy6v2blk-screen-5.0.1.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[jrpjbaj5dm8dnfcyvh4akyhfmq0cxbm9-linux-pam-1.7.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:03:15 UTC*
