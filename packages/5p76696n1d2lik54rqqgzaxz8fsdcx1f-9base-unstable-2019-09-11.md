---
aliases:
  - _9base
tags:
  - license/unknown
  - maintainers/06kellyjac
  - outputs/man
  - outputs/out
  - outputs/troff
---

# _9base

## 📝 Description

9base is a port of various original Plan 9 tools for Unix, based on plan9port.
It also contains the Plan 9 libc, libbio, libregexp, libfmt and libutf.
The overall SLOC is about 66kSLOC, so this userland + all libs is much smaller than, e.g. bash.
9base can be used to run werc instead of the full blown plan9port.


## 📋 Package Information

- **Name**: `_9base`
- **Version**: `2019-09-11`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Port of various original Plan 9 tools for Unix, based on plan9port
- **Homepage**: [https://tools.suckless.org/9base/](https://tools.suckless.org/9base/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @06kellyjac


## 🔧 Build Information

- **Derivation Path**: `/nix/store/5p76696n1d2lik54rqqgzaxz8fsdcx1f-9base-unstable-2019-09-11.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/_9/_9base/package.nix:71`
- **Outputs**:
  - `man`:  `/nix/store/5p76696n1d2lik54rqqgzaxz8fsdcx1f-9base-unstable-2019-09-11`
  - `out`:  `/nix/store/5p76696n1d2lik54rqqgzaxz8fsdcx1f-9base-unstable-2019-09-11`
  - `troff`:  `/nix/store/5p76696n1d2lik54rqqgzaxz8fsdcx1f-9base-unstable-2019-09-11`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[m4w3di7p700sxc12vixmk3s9l41zywqs-9base-63916da]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/0zlv6b5rrz4nc4bi53jcygirs24g6sg6-config-substitutions.patch`
- `/nix/store/ffvivgygnakkbyh6sw9i5mdajjq8a1vr-getcallerpc-use-macro-or-stub.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/m1qk4i8vkij43xn4l3v22viqr7cpkils-dont-strip.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:42:29 UTC*
