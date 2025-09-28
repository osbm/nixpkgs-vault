---
aliases:
  - idutils
tags:
  - license/unknown
  - maintainers/gfrascadorio
  - outputs/out
---

# idutils

## 📝 Description

An "ID database" is a binary file containing a list of file
names, a list of tokens, and a sparse matrix indicating which
tokens appear in which files.

With this database and some tools to query it, many
text-searching tasks become simpler and faster.  For example,
you can list all files that reference a particular `\#include'
file throughout a huge source hierarchy, search for all the
memos containing references to a project, or automatically
invoke an editor on all files containing references to some
function or variable.  Anyone with a large software project to
maintain, or a large set of text files to organize, can benefit
from the ID utilities.

Although the name `ID' is short for `identifier', the ID
utilities handle more than just identifiers; they also treat
other kinds of tokens, most notably numeric constants, and the
contents of certain character strings.


## 📋 Package Information

- **Name**: `idutils`
- **Version**: `4.6`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Text searching utility
- **Homepage**: [https://www.gnu.org/software/idutils/](https://www.gnu.org/software/idutils/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @gfrascadorio


## 🔧 Build Information

- **Derivation Path**: `/nix/store/i6g7cx9zvl4ad8n1clllafplsc1insdk-idutils-4.6.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/id/idutils/package.nix:54`
- **Outputs**:
  - `out`:  `/nix/store/i6g7cx9zvl4ad8n1clllafplsc1insdk-idutils-4.6`

## 🔗 Dependencies

- [[04f0zfjy7xia9z2v7gjd30lq4pa0m104-idutils-4.6.tar.xz]]
- [[0y20y5glzrd67xskzh9vjindzjl1jiiv-bison-3.8.2]]
- [[5lblxny27a302391s0swja5d9y6j08xs-gnulib-20241001]]
- [[7ys6vrd29swy0hb42rbhrc1sbsk4cq1g-autoconf-2.72]]
- [[82mw0nl5kb1zw36l4s4d0pdlfiadwlss-automake-1.18.1]]
- [[agnkcpgsw63ima1rywjanh2pqz1zpl18-gperf-3.3]]
- [[b4pa5k4if2jl33f1ynicjwz2nihy4z3c-texinfo-7.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dj4071dniqn7lsyg67yyxx1rjqp3zk6v-emacs-30.2]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[m0h8vm7wnxqmzy77yph902p607lx7np5-gettext-0.25.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[slcp4pdbh65jxz72z8vfrwwp4yki90ip-rsync-3.4.1]]

## 📁 Input Sources

- `/nix/store/cplkn5rmanf3kr5r126cqliii94jxjxh-nix-mapping.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:08:53 UTC*
