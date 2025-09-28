---
aliases:
  - cvsq
tags:
  - license/unknown
  - maintainers/clkamp
  - outputs/out
---

# cvsq

## 📝 Description

cvsq is a collection of tools to work locally with CVS.

cvsq queues commits and other cvs commands in a queue to be executed later,
when the machine is online again. In case of a commit (the default action)
an actual copy of the working directory is made, so that you can continue
editing without affecting the scheduled commit. You can even schedule
several successive commits to the same file and they will be correctly
committed as successive commits at the time of upload. This is different
from an earlier script also named cvsq that you might have seen elsewhere.

lcvs uses rsync to maintain a local copy of a cvs repository. It also
gives a convenient interface to call cvs in such a way that it believes the
current working directory refers to the local copy rather than to the actual
repository. This is useful for commands like log, diff, etc; however it cannot
be used for commits (that's what cvsq is for).


## 📋 Package Information

- **Name**: `cvsq`
- **Version**: `1.11`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Collection of tools to work locally with CVS
- **Homepage**: [https://www.linta.de/~aehlig/cvsq/](https://www.linta.de/~aehlig/cvsq/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @clkamp


## 🔧 Build Information

- **Derivation Path**: `/nix/store/c82ibvw529s4avhs10vslxlr4bhrf50p-cvsq-1.11.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/cv/cvsq/package.nix:93`
- **Outputs**:
  - `out`:  `/nix/store/c82ibvw529s4avhs10vslxlr4bhrf50p-cvsq-1.11`

## 🔗 Dependencies

- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[9sgdww5b3pl21vqy8j6dnyk16g1yigpr-cvsq-1.11.tgz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[g6k89fy44fzk8a9qrcgyz8l27zahgqd1-diffutils-3.12]]
- [[gi5izcpszaxq8y1rkkzn00kyx2rc2fnq-net-tools-2.10]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[mvpyzm6gla532x8m87q1fxzs4yazkakb-cvs-1.12.13+real-30]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[sl3ibba3ad7ipf41rfzy6v8h4s0cgdci-findutils-4.10.0]]
- [[slcp4pdbh65jxz72z8vfrwwp4yki90ip-rsync-3.4.1]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:02:45 UTC*
