---
aliases:
  - vectorscan
tags:
  - license/unknown
  - maintainers/tnias
  - maintainers/vlaci
  - outputs/out
---

# vectorscan

## 📝 Description

A fork of Intel's Hyperscan, modified to run on more platforms. Currently
ARM NEON/ASIMD is 100% functional, and Power VSX are in development.
ARM SVE2 will be implemented when hardware becomes accessible to the
developers. More platforms will follow in the future, on demand/request.

Vectorscan will follow Intel's API and internal algorithms where possible,
but will not hesitate to make code changes where it is thought of giving
better performance or better portability. In addition, the code will be
gradually simplified and made more uniform and all architecture specific
code will be abstracted away.


## 📋 Package Information

- **Name**: `vectorscan`
- **Version**: `5.4.12`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Portable fork of the high-performance regular expression matching library
- **Homepage**: [https://www.vectorcamp.gr/vectorscan/](https://www.vectorcamp.gr/vectorscan/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @tnias
- @vlaci


## 🔧 Build Information

- **Derivation Path**: `/nix/store/3hgpzq69d784sph9w28pdhxsh0v8xi46-vectorscan-5.4.12.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ve/vectorscan/package.nix:103`
- **Outputs**:
  - `out`:  `/nix/store/3hgpzq69d784sph9w28pdhxsh0v8xi46-vectorscan-5.4.12`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[3zvhnvb5q37g1nsr1b4an0syv2qwi0wz-pcre-8.45]]
- [[6f2psfx7f4xqqwq4cr5gs6mz7m3p9x3m-sqlite-3.50.2]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[9zshxf6kk537mzc627ynbj5lgp1qff15-util-linux-2.41.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[d23kfphynym2r4j03c4di1yz100b2c23-ragel-6.10]]
- [[i3ph2z8ayfgsqlrj9y2gwiyv3fmj6w10-boost-1.87.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[xmkmvpgin3nfxa11fglra61ycmzr4dwa-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:21:27 UTC*
