---
aliases:
  - rs
tags:
  - license/unknown
  - outputs/out
---

# rs

## 📝 Description

rs reads the standard input, interpreting each line as a row of blank-
separated entries in an array, transforms the array according to the op-
tions, and writes it on the standard output. With no arguments (argc < 2)
it transforms stream input into a columnar format convenient for terminal
viewing, i.e. if the length (in bytes!) of the first line is smaller than
the display width, -et is implied, -t otherwise.

The shape of the input array is deduced from the number of lines and the
number of columns on the first line. If that shape is inconvenient, a more
useful one might be obtained by skipping some of the input with the -k
option. Other options control interpretation of the input columns.

The shape of the output array is influenced by the rows and cols specifi-
cations, which should be positive integers. If only one of them is a po-
sitive integer, rs computes a value for the other which will accommodate
all of the data. When necessary, missing data are supplied in a manner
specified by the options and surplus data are deleted. There are options
to control presentation of the output columns, including transposition of
the rows and columns.


## 📋 Package Information

- **Name**: `rs`
- **Version**: `20200313`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Reshape a data array from standard input
- **Homepage**: [http://www.mirbsd.org/htman/i386/man1/rs.htm](http://www.mirbsd.org/htman/i386/man1/rs.htm)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/pg90c78k2nc9j3ds0ald2xkdw4b5i6zm-rs-20200313.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/rs/rs/package.nix:46`
- **Outputs**:
  - `out`:  `/nix/store/pg90c78k2nc9j3ds0ald2xkdw4b5i6zm-rs-20200313`

## 🔗 Dependencies

- [[39cjpzrja9nlwnz564n58qspjkrmk7ss-libbsd-0.12.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i9kj1nhzkg91xsq8ny4z4hipl0b42kad-gcc-wrapper-14.3.0]]
- [[kgy4nhrjh4wjkmw0hyz0f6pypplw3zv6-rs-20200313.tar.gz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/rnbial2p8rir7pgkqdgamv16jcykbk86-macos-reallocarray.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:21:22 UTC*
