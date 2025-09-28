---
aliases:
  - autojump
tags:
  - license/unknown
  - maintainers/yurrriq
  - outputs/out
---

# autojump

## 📝 Description

One of the most used shell commands is “cd”.  A quick survey
among my friends revealed that between 10 and 20% of all
commands they type are actually cd commands! Unfortunately,
jumping from one part of your system to another with cd
requires to enter almost the full path, which isn’t very
practical and requires a lot of keystrokes.

Autojump is a faster way to navigate your filesystem.  It
works by maintaining a database of the directories you use the
most from the command line.  The jstat command shows you the
current contents of the database.  You need to work a little
bit before the database becomes usable.  Once your database
is reasonably complete, you can “jump” to a directory by
typing "j dirspec", where dirspec is a few characters of the
directory you want to jump to.  It will jump to the most used
directory whose name matches the pattern given in dirspec.

Autojump supports tab-completion.


## 📋 Package Information

- **Name**: `autojump`
- **Version**: `22.5.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: `cd' command that learns
- **Homepage**: [https://github.com/wting/autojump](https://github.com/wting/autojump)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @yurrriq


## 🔧 Build Information

- **Derivation Path**: `/nix/store/7r6qfm1crx2hc91pyp0lfhkzcwm4sbgq-autojump-22.5.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/au/autojump/package.nix:34`
- **Outputs**:
  - `out`:  `/nix/store/7r6qfm1crx2hc91pyp0lfhkzcwm4sbgq-autojump-22.5.3`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[jr4g0iky5gyxgwdxbdny72zfa416gncf-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:43:06 UTC*
