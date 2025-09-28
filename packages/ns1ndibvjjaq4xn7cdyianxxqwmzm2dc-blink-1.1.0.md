---
aliases:
  - blink
tags:
  - license/unknown
  - maintainers/t4ccer
  - outputs/out
---

# blink

## 📝 Description

blink is a virtual machine that runs x86-64-linux programs on different operating systems and hardware architectures. It's designed to do the same thing as the qemu-x86_64 command, except that
- blink is much smaller in size than qemu-x86_64
- blink will run your Linux binaries on any POSIX platform, whereas qemu-x86_64 only supports Linux
- blink goes 2x faster than qemu-x86_64 on some benchmarks, such as SSE integer / floating point math. Blink is also faster at running ephemeral programs such as compilers


## 📋 Package Information

- **Name**: `blink`
- **Version**: `1.1.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tiniest x86-64-linux emulator
- **Homepage**: [https://github.com/jart/blink](https://github.com/jart/blink)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @t4ccer


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ns1ndibvjjaq4xn7cdyianxxqwmzm2dc-blink-1.1.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/bl/blink/package.nix:35`
- **Outputs**:
  - `out`:  `/nix/store/ns1ndibvjjaq4xn7cdyianxxqwmzm2dc-blink-1.1.0`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[38cg0jbpyh1479zxxplr1h2drz6xg1m5-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:55 UTC*
