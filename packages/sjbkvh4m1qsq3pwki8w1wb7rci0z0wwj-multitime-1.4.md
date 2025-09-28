---
aliases:
  - multitime
tags:
  - license/unknown
  - outputs/out
---

# multitime

## 📝 Description

Unix's `time` utility is a simple and often effective way of measuring
how long a command takes to run. Unfortunately, running a command once
can give misleading timings: the process may create a cache on its first
execution, running faster subsequently; other processes may cause the
command to be starved of CPU or IO time; etc. It is common to see people
run `time` several times and take whichever values they feel most
comfortable with. Inevitably, this causes problems.

`multitime` is, in essence, a simple extension to time which runs a
command multiple times and prints the timing means (with confidence
intervals), standard deviations, minimums, medians, and maximums having
done so. This can give a much better understanding of the command's
performance.


## 📋 Package Information

- **Name**: `multitime`
- **Version**: `1.4`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Time command execution over multiple executions
- **Homepage**: [https://tratt.net/laurie/src/multitime/](https://tratt.net/laurie/src/multitime/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/sjbkvh4m1qsq3pwki8w1wb7rci0z0wwj-multitime-1.4.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/mu/multitime/package.nix:22`
- **Outputs**:
  - `out`:  `/nix/store/sjbkvh4m1qsq3pwki8w1wb7rci0z0wwj-multitime-1.4`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[f78wczryj941n33506v3541hv82ws3gi-source]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:12:14 UTC*
