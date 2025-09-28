---
aliases:
  - parallel
tags:
  - license/unknown
  - maintainers/pSub
  - maintainers/tomberek
  - outputs/doc
  - outputs/man
  - outputs/out
---

# parallel

## 📝 Description

GNU Parallel is a shell tool for executing jobs in parallel.  A job
is typically a single command or a small script that has to be run
for each of the lines in the input.  The typical input is a list of
files, a list of hosts, a list of users, or a list of tables.

If you use xargs today you will find GNU Parallel very easy to use.
If you write loops in shell, you will find GNU Parallel may be able
to replace most of the loops and make them run faster by running
jobs in parallel.  If you use ppss or pexec you will find GNU
Parallel will often make the command easier to read.

GNU Parallel makes sure output from the commands is the same output
as you would get had you run the commands sequentially.  This makes
it possible to use output from GNU Parallel as input for other
programs.


## 📋 Package Information

- **Name**: `parallel`
- **Version**: `20250822`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Shell tool for executing jobs in parallel
- **Homepage**: [https://www.gnu.org/software/parallel/](https://www.gnu.org/software/parallel/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @pSub
- @tomberek


## 🔧 Build Information

- **Derivation Path**: `/nix/store/qmz7q1nphcv9g6p0phd5vriz233jc7lw-parallel-20250822.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/tools/misc/parallel/default.nix:62`
- **Outputs**:
  - `doc`:  `/nix/store/qmz7q1nphcv9g6p0phd5vriz233jc7lw-parallel-20250822`
  - `man`:  `/nix/store/qmz7q1nphcv9g6p0phd5vriz233jc7lw-parallel-20250822`
  - `out`:  `/nix/store/qmz7q1nphcv9g6p0phd5vriz233jc7lw-parallel-20250822`

## 🔗 Dependencies

- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lxw1zfs9v3nm19mpqbllvcl3s2hkpbjq-procps-4.0.4]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q331wl66bksvjp5qq0b3dhbcw3fx09x2-gawk-5.3.2]]
- [[wdqn191lwdd2479zzgn7zm9xk0sviqzd-parallel-20250822.tar.bz2]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:11:36 UTC*
