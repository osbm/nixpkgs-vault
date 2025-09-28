---
aliases:
  - oprofile
tags:
  - license/unknown
  - outputs/out
---

# oprofile

## 📝 Description

OProfile is a system-wide profiler for Linux systems, capable of
profiling all running code at low overhead.  It consists of a
kernel driver and a daemon for collecting sample data, and
several post-profiling tools for turning data into information.

OProfile leverages the hardware performance counters of the CPU
to enable profiling of a wide variety of interesting statistics,
which can also be used for basic time-spent profiling. All code
is profiled: hardware and software interrupt handlers, kernel
modules, the kernel, shared libraries, and applications.


## 📋 Package Information

- **Name**: `oprofile`
- **Version**: `1.4.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: System-wide profiler for Linux
- **Homepage**: [http://oprofile.sourceforge.net/](http://oprofile.sourceforge.net/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/xclpg56pcmnr642nx2jdwndy02y0nh69-oprofile-1.4.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/tools/profiling/oprofile/default.nix:50`
- **Outputs**:
  - `out`:  `/nix/store/xclpg56pcmnr642nx2jdwndy02y0nh69-oprofile-1.4.0`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[h52lzzip82l66c7bv23g7xckp89y5kgr-linux-headers-6.16]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[nmkmyb7a228amldqqq405d7q9149hgyx-binutils-2.44]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vv6azl8q2vy1m15dvmylqh2qq3vbz5q7-popt-1.19]]
- [[x9fp4ydi6nbhspv9yjn3h2hk2yxczhrj-oprofile-1.4.0.tar.gz]]
- [[ygnzs2q541dx2p4fkn1zqzahr4i5wdpa-libiberty-14.3.0]]

## 📁 Input Sources

- `/nix/store/j5ikf9bn76fbiv6bhzmwhrklgvx0myn1-fix-autoconf-detection-of-perf_events.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:01:27 UTC*
