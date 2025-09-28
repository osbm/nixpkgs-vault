---
aliases:
  - sharutils
tags:
  - license/unknown
  - outputs/out
---

# sharutils

## 📝 Description

GNU shar makes so-called shell archives out of many files, preparing
them for transmission by electronic mail services.  A shell archive
is a collection of files that can be unpacked by /bin/sh.  A wide
range of features provide extensive flexibility in manufacturing
shars and in specifying shar smartness.  For example, shar may
compress files, uuencode binary files, split long files and
construct multi-part mailings, ensure correct unsharing order, and
provide simplistic checksums.

GNU unshar scans a set of mail messages looking for the start of
shell archives.  It will automatically strip off the mail headers
and other introductory text.  The archive bodies are then unpacked
by a copy of the shell. unshar may also process files containing
concatenated shell archives.


## 📋 Package Information

- **Name**: `sharutils`
- **Version**: `4.15.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tools for remote synchronization and `shell archives'
- **Homepage**: [https://www.gnu.org/software/sharutils/](https://www.gnu.org/software/sharutils/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/zz53bsc11sijgcv6l07j2vwb0kp3dwgd-sharutils-4.15.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sh/sharutils/package.nix:81`
- **Outputs**:
  - `out`:  `/nix/store/zz53bsc11sijgcv6l07j2vwb0kp3dwgd-sharutils-4.15.2`

## 🔗 Dependencies

- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[529mydxxk7pfsxn4a7jkg4kncpg5iiwv-02-fix-ftbfs-with-glibc-2.28.patch]]
- [[9is02xj4q35hn136pv5jzdj9cyb6s9af-01-fix-heap-buffer-overflow-cve-2018-1000097.patch]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gs17pi11hfqjs1krk52a7fia7ppn5qhb-sharutils-4.15.2-Do-not-include-lib-md5.c-into-src-shar.c.patch]]
- [[hix6rm0f4rx0hsdp31vaky4zvr67v6r6-update-autotools-gnu-config-scripts-hook]]
- [[k99qa90m0xsdm6bmijhkk0shaxglvxnh-sharutils-4.15.2-Fix-building-with-GCC-10.patch]]
- [[m0h8vm7wnxqmzy77yph902p607lx7np5-gettext-0.25.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[svr67206l85h581rmgjvy36p728lm8qx-sharutils-4.15.2.tar.xz]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:07:27 UTC*
