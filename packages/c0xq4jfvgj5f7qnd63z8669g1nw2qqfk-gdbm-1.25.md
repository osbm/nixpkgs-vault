---
aliases:
  - gdbm
tags:
  - license/unknown
  - outputs/dev
  - outputs/info
  - outputs/lib
  - outputs/man
  - outputs/out
---

# gdbm

## 📝 Description

GNU dbm (or GDBM, for short) is a library of database functions that use
extensible hashing and work similar to the standard UNIX dbm. These
routines are provided to a programmer needing to create and manipulate a
hashed database.

The basic use of GDBM is to store key/data pairs in a data file. Each
key must be unique and each key is paired with only one data item.

The library provides primitives for storing key/data pairs, searching and
retrieving the data by its key and deleting a key along with its data.
It also support sequential iteration over all key/data pairs in a
database.

For compatibility with programs using old UNIX dbm function, the package
also provides traditional dbm and ndbm interfaces.


## 📋 Package Information

- **Name**: `gdbm`
- **Version**: `1.25`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GNU dbm key/value database library
- **Homepage**: [https://www.gnu.org/software/gdbm/](https://www.gnu.org/software/gdbm/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/c0xq4jfvgj5f7qnd63z8669g1nw2qqfk-gdbm-1.25.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/gd/gdbm/package.nix:79`
- **Outputs**:
  - `dev`:  `/nix/store/c0xq4jfvgj5f7qnd63z8669g1nw2qqfk-gdbm-1.25`
  - `info`:  `/nix/store/c0xq4jfvgj5f7qnd63z8669g1nw2qqfk-gdbm-1.25`
  - `lib`:  `/nix/store/c0xq4jfvgj5f7qnd63z8669g1nw2qqfk-gdbm-1.25`
  - `man`:  `/nix/store/c0xq4jfvgj5f7qnd63z8669g1nw2qqfk-gdbm-1.25`
  - `out`:  `/nix/store/c0xq4jfvgj5f7qnd63z8669g1nw2qqfk-gdbm-1.25`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[hix6rm0f4rx0hsdp31vaky4zvr67v6r6-update-autotools-gnu-config-scripts-hook]]
- [[ii70hj2dqp8bvdbdmh98kw09wp2jwmlc-gdbm-1.25.tar.gz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/jw14p81ngrmmm1189rgkx28i030svjmw-upstream-darwin-clock-nanosleep-fix.patch`
- `/nix/store/k3azmfbl1rjkflj90ahbr383vgcfs28a-upstream-lockwait-test-fixes.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/vjxyg7cyqq0s25dmma01xg57kp6ri4wg-upstream-musl-ssize_t-fix.patch`

---
*Generated on 2025-09-27 11:56:41 UTC*
