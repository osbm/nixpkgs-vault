---
aliases:
  - stdoutisatty
tags:
  - license/unknown
  - maintainers/bryango
  - outputs/out
---

# stdoutisatty

## 📝 Description

`stdoutisatty command` makes `command` think their stdout is a terminal,
even if it is actually being piped into another program (e.g. `less`).
This is most useful for preserving user-friendly, colored outputs.

For example, `stdoutisatty ls --color=auto | less` will always show
colored output, despite being piped into a pager.


## 📋 Package Information

- **Name**: `stdoutisatty`
- **Version**: `1.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Make programs think their stdout is a tty / terminal
- **Homepage**: [https://github.com/lilydjwg/stdoutisatty](https://github.com/lilydjwg/stdoutisatty)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @bryango


## 🔧 Build Information

- **Derivation Path**: `/nix/store/gj4cnsa51b83x2ip436m3cmfhx4jgn02-stdoutisatty-1.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/st/stdoutisatty/package.nix:54`
- **Outputs**:
  - `out`:  `/nix/store/gj4cnsa51b83x2ip436m3cmfhx4jgn02-stdoutisatty-1.0`

## 🔗 Dependencies

- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i2205py79fz8xi071s52vqsvxjc4xmvl-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pn03b9dijjmykv1k5sfjm4h990h4k25f-make-binary-wrapper-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:53:07 UTC*
