---
aliases:
  - deterministic-uname
tags:
  - license/unknown
  - maintainers/Artturin
  - outputs/out
---

# deterministic-uname

## 📝 Description

This package provides a replacement for `uname` whose output depends only
on `stdenv.buildPlatform`, or a configurable `forPlatform`.  It is meant
to be used from within derivations. Many packages' build processes run
`uname` at compile time and embed its output into the result of the build.
Since `uname` calls into the kernel, and the Nix sandbox currently does
not intercept these calls, builds made on different kernels will produce
different results.


## 📋 Package Information

- **Name**: `deterministic-uname`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Print certain system information (hardcoded with lib/system values)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @Artturin


## 🔧 Build Information

- **Derivation Path**: `/nix/store/wkmm9rdc87nc399mg2aswbba8jvf5zs0-uname.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/de/deterministic-uname/package.nix:48`
- **Outputs**:
  - `out`:  `/nix/store/wkmm9rdc87nc399mg2aswbba8jvf5zs0-uname`

## 🔗 Dependencies

- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[q6r8nhgmx37s1vk3580hn9q1illlh9n2-getopt-1.1.6]]

## 📁 Input Sources

- `/nix/store/3q9ql8z69p1mmhihn2gn1bi7qz2zg182-deterministic-uname.sh`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:43:12 UTC*
