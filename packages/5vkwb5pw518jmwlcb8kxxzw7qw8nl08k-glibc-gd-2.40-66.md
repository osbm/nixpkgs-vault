---
aliases:
  - glibc_memusage
tags:
  - license/unknown
  - maintainers/Ma27
  - maintainers/ConnorBaker
  - outputs/bin
  - outputs/debug
  - outputs/dev
  - outputs/getent
  - outputs/out
  - outputs/static
---

# glibc_memusage

## 📝 Description

Any Unix-like operating system needs a C library: the library which
defines the "system calls" and other basic facilities such as
open, malloc, printf, exit...

The GNU C library is used as the C library in the GNU system and
most systems with the Linux kernel.


## 📋 Package Information

- **Name**: `glibc_memusage`
- **Version**: `2.40-66`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GNU C Library
- **Homepage**: [https://www.gnu.org/software/libc/](https://www.gnu.org/software/libc/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @Ma27
- @ConnorBaker


## 🔧 Build Information

- **Derivation Path**: `/nix/store/5vkwb5pw518jmwlcb8kxxzw7qw8nl08k-glibc-gd-2.40-66.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/libraries/glibc/default.nix:219`
- **Outputs**:
  - `bin`:  `/nix/store/5vkwb5pw518jmwlcb8kxxzw7qw8nl08k-glibc-gd-2.40-66`
  - `debug`:  `/nix/store/5vkwb5pw518jmwlcb8kxxzw7qw8nl08k-glibc-gd-2.40-66`
  - `dev`:  `/nix/store/5vkwb5pw518jmwlcb8kxxzw7qw8nl08k-glibc-gd-2.40-66`
  - `getent`:  `/nix/store/5vkwb5pw518jmwlcb8kxxzw7qw8nl08k-glibc-gd-2.40-66`
  - `out`:  `/nix/store/5vkwb5pw518jmwlcb8kxxzw7qw8nl08k-glibc-gd-2.40-66`
  - `static`:  `/nix/store/5vkwb5pw518jmwlcb8kxxzw7qw8nl08k-glibc-gd-2.40-66`

## 🔗 Dependencies

- [[05r5l4x91za42j1g75hc6dn969amrd61-gd-2.3.3]]
- [[0y20y5glzrd67xskzh9vjindzjl1jiiv-bison-3.8.2]]
- [[6r5cldhv0mdkwwia0zdchk4aar0azvrd-gcc-14.3.0]]
- [[8qvzhry004aybdbrb9y8c387ah9k0mps-binutils-2.44]]
- [[bgkb3y8qyl0xv9m1rmr8734h6l9nhnr3-libidn2-2.3.8]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[ckxmy2dr3kmsjf6niqn27hsa1y9igf1h-python3-minimal-3.13.7]]
- [[f1305aqkwkvrpxy69rxbvs54ixmlm1dq-glibc-2.40-66]]
- [[h52lzzip82l66c7bv23g7xckp89y5kgr-linux-headers-6.16]]
- [[i9kj1nhzkg91xsq8ny4z4hipl0b42kad-gcc-wrapper-14.3.0]]
- [[k6vhjwcchsimhjpq3qwp37r3yvq7b79i-glibc-2.40.tar.xz]]
- [[mzg1vkyzabv01ja719b3zj9hzwkzhyk2-libpng-apng-1.6.49]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/001gp43bjqzx60cg345n2slzg7131za8-nix-nss-open-files.patch`
- `/nix/store/2wlbvj13lm5rln4i71b3972lcfd91hzs-2.40-master.patch`
- `/nix/store/7kw224hdyxd7115lrqh9a4dv2x8msq2s-fix-x64-abi.patch`
- `/nix/store/b1w7zbvm39ff1i52iyjggyvw2rdxz104-dont-use-system-ld-so-cache.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/mnglr8rr7nl444h7p50ysyq8qd0fm1lm-dont-use-system-ld-so-preload.patch`
- `/nix/store/nc5hqqizlj7042vvhvx121kzf4nwh35p-nix-locale-archive.patch`
- `/nix/store/pcpx2ayccijipfl32zchx0mg7rzvj6zx-0001-Revert-Remove-all-usage-of-BASH-or-BASH-in-installed.patch`
- `/nix/store/r989dk196nl9frhnfsa1lb7knhbyjxw6-separate-debug-info.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/sj0qllprnrmk1cqnnk57vvn2cqgjynbx-reenable_DT_HASH.patch`
- `/nix/store/za0pg7fmysrcwrqcal26fnmzw6vycgdn-fix_path_attribute_in_getconf.patch`

---
*Generated on 2025-09-27 12:05:55 UTC*
