---
aliases:
  - ddrescue
tags:
  - license/unknown
  - maintainers/fpletz
  - outputs/out
---

# ddrescue

## 📝 Description

GNU ddrescue is a data recovery tool.  It copies data from one file
or block device (hard disc, cdrom, etc) to another, trying hard to
rescue data in case of read errors.

The basic operation of ddrescue is fully automatic.  That is, you
don't have to wait for an error, stop the program, read the log, run
it in reverse mode, etc.

If you use the logfile feature of ddrescue, the data is rescued very
efficiently (only the needed blocks are read).  Also you can
interrupt the rescue at any time and resume it later at the same
point.

Automatic merging of backups: If you have two or more damaged copies
of a file, cdrom, etc, and run ddrescue on all of them, one at a
time, with the same output file, you will probably obtain a complete
and error-free file.  This is so because the probability of having
damaged areas at the same places on different input files is very
low.  Using the logfile, only the needed blocks are read from the
second and successive copies.


## 📋 Package Information

- **Name**: `ddrescue`
- **Version**: `1.29.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GNU ddrescue, a data recovery tool
- **Homepage**: [https://www.gnu.org/software/ddrescue/ddrescue.html](https://www.gnu.org/software/ddrescue/ddrescue.html)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @fpletz


## 🔧 Build Information

- **Derivation Path**: `/nix/store/bdp4y6y2nr0ph0f6bbbl9yk83g79mcd9-ddrescue-1.29.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/dd/ddrescue/package.nix:23`
- **Outputs**:
  - `out`:  `/nix/store/bdp4y6y2nr0ph0f6bbbl9yk83g79mcd9-ddrescue-1.29.1`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rnsrqrjkzb0rgd72q55dxly1n83ny5bh-lzip-1.25]]
- [[vw1idbgkk6yqf4yw5s4y2gl5q47p7r7j-ddrescue-1.29.1.tar.lz]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:40:59 UTC*
