---
aliases:
  - xjobs
tags:
  - license/unknown
  - maintainers/siriobalmelli
  - outputs/out
---

# xjobs

## 📝 Description

xjobs reads job descriptions line by line and executes them in parallel.

It limits the number of parallel executing jobs and starts new jobs when jobs finish.

Therefore, it combines the arguments from every input line with the utility
and arguments given on the command line.
If no utility is given as an argument to xjobs,
then the first argument on every job line will be used as utility.
To execute utility xjobs searches the directories given in the PATH environment variable
and uses the first file found in these directories.

xjobs is most useful on multi-processor/core machines when one needs to execute
several time consuming command several that could possibly be run in parallel.
With xjobs this can be achieved easily, and it is possible to limit the load
of the machine to a useful value.

It works similar to xargs, but starts several processes simultaneously
and gives only one line of arguments to each utility call.


## 📋 Package Information

- **Name**: `xjobs`
- **Version**: `20250529`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Program which reads job descriptions line by line and executes them in parallel
- **Homepage**: [https://www.maier-komor.de/xjobs.html](https://www.maier-komor.de/xjobs.html)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @siriobalmelli


## 🔧 Build Information

- **Derivation Path**: `/nix/store/d4bys0ga0hwqaw824fx1gc7y76yqbyz1-xjobs-20250529.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/xj/xjobs/package.nix:50`
- **Outputs**:
  - `out`:  `/nix/store/d4bys0ga0hwqaw824fx1gc7y76yqbyz1-xjobs-20250529`

## 🔗 Dependencies

- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[4f9j67x7cgs2hzjgyyzm8q6z1w2vgy41-which-2.23]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[wssmk2pv53xicydi0lx9r3makn30jpcy-xjobs-20250529.tgz]]
- [[wy61x67y125m36dp7l7xhzqbi30mxg1d-flex-2.6.4]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:11:54 UTC*
