---
aliases:
  - fatrace
tags:
  - license/unknown
  - outputs/out
---

# fatrace

## 📝 Description

fatrace reports file access events from all running processes.
Its main purpose is to find processes which keep waking up the disk
unnecessarily and thus prevent some power saving.
Requires a Linux kernel with the FANOTIFY configuration option enabled.
Enabling X86_MSR is also recommended for power-usage-report on x86.


## 📋 Package Information

- **Name**: `fatrace`
- **Version**: `0.19.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Report system-wide file access events
- **Homepage**: [https://github.com/martinpitt/fatrace](https://github.com/martinpitt/fatrace)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/ba66z6q1wvml6ia0k7m58wsycqjxlcay-fatrace-0.19.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/fa/fatrace/package.nix:33`
- **Outputs**:
  - `out`:  `/nix/store/ba66z6q1wvml6ia0k7m58wsycqjxlcay-fatrace-0.19.1`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[4f9j67x7cgs2hzjgyyzm8q6z1w2vgy41-which-2.23]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[z1p5id6gffnw8rab5bi4mg6q4hc0lffa-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:59:07 UTC*
