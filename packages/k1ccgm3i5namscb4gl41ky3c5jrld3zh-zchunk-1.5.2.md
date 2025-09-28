---
aliases:
  - zchunk
tags:
  - license/unknown
  - outputs/dev
  - outputs/lib
  - outputs/man
  - outputs/out
---

# zchunk

## 📝 Description

zchunk is a compressed file format that splits the file into independent
chunks. This allows you to only download changed chunks when downloading a
new version of the file, and also makes zchunk files efficient over rsync.

zchunk files are protected with strong checksums to verify that the file
you downloaded is, in fact, the file you wanted.


## 📋 Package Information

- **Name**: `zchunk`
- **Version**: `1.5.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: File format designed for highly efficient deltas while maintaining good compression
- **Homepage**: [https://github.com/zchunk/zchunk](https://github.com/zchunk/zchunk)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/k1ccgm3i5namscb4gl41ky3c5jrld3zh-zchunk-1.5.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/zc/zchunk/package.nix:57`
- **Outputs**:
  - `dev`:  `/nix/store/k1ccgm3i5namscb4gl41ky3c5jrld3zh-zchunk-1.5.2`
  - `lib`:  `/nix/store/k1ccgm3i5namscb4gl41ky3c5jrld3zh-zchunk-1.5.2`
  - `man`:  `/nix/store/k1ccgm3i5namscb4gl41ky3c5jrld3zh-zchunk-1.5.2`
  - `out`:  `/nix/store/k1ccgm3i5namscb4gl41ky3c5jrld3zh-zchunk-1.5.2`

## 🔗 Dependencies

- [[ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[g1smgp5dhq2ii8np7vm7n5znki3ak1b1-curl-8.14.1]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[jkkx945106rp68bbaqkh1i8bqfc8l63c-source]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:10:36 UTC*
