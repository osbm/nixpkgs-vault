---
aliases:
  - readline
tags:
  - license/unknown
  - maintainers/dtzWill
  - outputs/dev
  - outputs/doc
  - outputs/info
  - outputs/man
  - outputs/out
---

# readline

## 📝 Description

The GNU Readline library provides a set of functions for use by
applications that allow users to edit command lines as they are
typed in.  Both Emacs and vi editing modes are available.  The
Readline library includes additional functions to maintain a
list of previously-entered command lines, to recall and perhaps
reedit those lines, and perform csh-like history expansion on
previous commands.

The history facilities are also placed into a separate library,
the History library, as part of the build process.  The History
library may be used without Readline in applications which
desire its capabilities.


## 📋 Package Information

- **Name**: `readline`
- **Version**: `8.3p1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Library for interactive line editing
- **Homepage**: [https://savannah.gnu.org/projects/readline/](https://savannah.gnu.org/projects/readline/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @dtzWill


## 🔧 Build Information

- **Derivation Path**: `/nix/store/pp99kqhfn7z3a58pjkv4kiyrs62k0bj4-readline-8.3p1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/libraries/readline/8.3.nix:96`
- **Outputs**:
  - `dev`:  `/nix/store/pp99kqhfn7z3a58pjkv4kiyrs62k0bj4-readline-8.3p1`
  - `doc`:  `/nix/store/pp99kqhfn7z3a58pjkv4kiyrs62k0bj4-readline-8.3p1`
  - `info`:  `/nix/store/pp99kqhfn7z3a58pjkv4kiyrs62k0bj4-readline-8.3p1`
  - `man`:  `/nix/store/pp99kqhfn7z3a58pjkv4kiyrs62k0bj4-readline-8.3p1`
  - `out`:  `/nix/store/pp99kqhfn7z3a58pjkv4kiyrs62k0bj4-readline-8.3p1`

## 🔗 Dependencies

- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[9jksv05mli1p9s4r0i9hgs7sqfaaplzx-readline-8.3.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dvsx401g269xykpkhilj1wvg5x1207g7-readline83-001]]
- [[hix6rm0f4rx0hsdp31vaky4zvr67v6r6-update-autotools-gnu-config-scripts-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/0v7w62jca8nw6w31zs4y2805jj670f6p-no-arch_only-8.2.patch`
- `/nix/store/bw6aa38615ww5karcn8kslsf5hxgz412-link-against-ncurses.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:15:34 UTC*
