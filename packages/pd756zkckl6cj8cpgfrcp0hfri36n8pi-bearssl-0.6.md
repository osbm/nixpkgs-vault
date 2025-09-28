---
aliases:
  - bearssl
tags:
  - license/unknown
  - outputs/bin
  - outputs/dev
  - outputs/lib
  - outputs/out
---

# bearssl

## 📝 Description

BearSSL is an implementation of the SSL/TLS protocol (RFC 5246)
written in C. It aims at offering the following features:

* Be correct and secure. In particular, insecure protocol versions and
  choices of algorithms are not supported, by design; cryptographic
  algorithm implementations are constant-time by default.

* Be small, both in RAM and code footprint. For instance, a minimal
  server implementation may fit in about 20 kilobytes of compiled code
  and 25 kilobytes of RAM.

* Be highly portable. BearSSL targets not only “big” operating systems
  like Linux and Windows, but also small embedded systems and even
  special contexts like bootstrap code.

* Be feature-rich and extensible. SSL/TLS has many defined cipher
  suites and extensions; BearSSL should implement most of them, and
  allow extra algorithm implementations to be added afterwards,
  possibly from third parties.


## 📋 Package Information

- **Name**: `bearssl`
- **Version**: `0.6`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Implementation of the SSL/TLS protocol written in C
- **Homepage**: [https://www.bearssl.org/](https://www.bearssl.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/pd756zkckl6cj8cpgfrcp0hfri36n8pi-bearssl-0.6.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/be/bearssl/package.nix:45`
- **Outputs**:
  - `bin`:  `/nix/store/pd756zkckl6cj8cpgfrcp0hfri36n8pi-bearssl-0.6`
  - `dev`:  `/nix/store/pd756zkckl6cj8cpgfrcp0hfri36n8pi-bearssl-0.6`
  - `lib`:  `/nix/store/pd756zkckl6cj8cpgfrcp0hfri36n8pi-bearssl-0.6`
  - `out`:  `/nix/store/pd756zkckl6cj8cpgfrcp0hfri36n8pi-bearssl-0.6`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[scdvgvabzmvvhha9v5mdypvw8nkda7wm-bearssl-0.6.tar.gz]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:53:44 UTC*
