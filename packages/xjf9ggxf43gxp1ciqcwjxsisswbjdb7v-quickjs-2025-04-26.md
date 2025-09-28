---
aliases:
  - quickjs
tags:
  - license/unknown
  - maintainers/stesie
  - outputs/info
  - outputs/out
---

# quickjs

## 📝 Description

QuickJS is a small and embeddable Javascript engine. It supports the
ES2023 specification including modules, asynchronous generators, proxies
and BigInt.

Main Features:

- Small and easily embeddable: just a few C files, no external
  dependency, 210 KiB of x86 code for a simple hello world program.
- Fast interpreter with very low startup time: runs the 76000 tests of
  the ECMAScript Test Suite in less than 2 minutes on a single core of a
  desktop PC. The complete life cycle of a runtime instance completes in
  less than 300 microseconds.
- Almost complete ES2023 support including modules, asynchronous
  generators and full Annex B support (legacy web compatibility).
- Passes nearly 100% of the ECMAScript Test Suite tests when selecting
  the ES2023 features. A summary is available at Test262 Report.
- Can compile Javascript sources to executables with no external dependency.
- Garbage collection using reference counting (to reduce memory usage and
  have deterministic behavior) with cycle removal.
- Command line interpreter with contextual colorization implemented in
  Javascript.
- Small built-in standard library with C library wrappers.



## 📋 Package Information

- **Name**: `quickjs`
- **Version**: `2025-04-26`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Small and embeddable Javascript engine
- **Homepage**: [https://bellard.org/quickjs/](https://bellard.org/quickjs/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @stesie


## 🔧 Build Information

- **Derivation Path**: `/nix/store/xjf9ggxf43gxp1ciqcwjxsisswbjdb7v-quickjs-2025-04-26.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/qu/quickjs/package.nix:90`
- **Outputs**:
  - `info`:  `/nix/store/xjf9ggxf43gxp1ciqcwjxsisswbjdb7v-quickjs-2025-04-26`
  - `out`:  `/nix/store/xjf9ggxf43gxp1ciqcwjxsisswbjdb7v-quickjs-2025-04-26`

## 🔗 Dependencies

- [[6xnka7wy07sz7azxwphih6yrc6inf1v4-quickjs-2025-04-26.tar.xz]]
- [[b4pa5k4if2jl33f1ynicjwz2nihy4z3c-texinfo-7.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:53:47 UTC*
