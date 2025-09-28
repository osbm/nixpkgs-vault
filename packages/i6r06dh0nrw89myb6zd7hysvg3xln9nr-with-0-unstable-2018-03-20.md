---
aliases:
  - with-shell
tags:
  - license/unknown
  - outputs/out
---

# with-shell

## 📝 Description

with is a Bash script that starts an interactive shell with where every
command is prefixed using <program>.

For example:

$ with git
git> add .
git> commit -a -m "Committed"
git> push

Can also be used for compound commands.

$ with java Primes
java Primes> 1
2
java Primes> 4
7

And to repeat commands:

$ with gcc -o output input.c
gcc -o -output input.c>
<enter>
Compiling...
gcc -o -output input.c>

To execute a shell command proper prefix line with :.

git> :ls

You can also drop, add, and replace different commands.

git> +add
git add> <some file>
git add> !commit
git commit> <arguments and message>
git commit> -
git>

To exit use either :q or :exit.


## 📋 Package Information

- **Name**: `with-shell`
- **Version**: `0-unstable-2018-03-20`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Command prefixing for continuous workflow using a single tool
- **Homepage**: [https://github.com/mchav/With](https://github.com/mchav/With)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/i6r06dh0nrw89myb6zd7hysvg3xln9nr-with-0-unstable-2018-03-20.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/wi/with-shell/package.nix:30`
- **Outputs**:
  - `out`:  `/nix/store/i6r06dh0nrw89myb6zd7hysvg3xln9nr-with-0-unstable-2018-03-20`

## 🔗 Dependencies

- [[b3zqg9sdvrkngzrssghijngjpkxvqgr9-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:14:22 UTC*
