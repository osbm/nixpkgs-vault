---
aliases:
  - libevent
tags:
  - license/unknown
  - outputs/dev
  - outputs/openssl
  - outputs/out
---

# libevent

## 📝 Description

The libevent API provides a mechanism to execute a callback function
when a specific event occurs on a file descriptor or after a timeout
has been reached.  Furthermore, libevent also support callbacks due
to signals or regular timeouts.

libevent is meant to replace the event loop found in event driven
network servers.  An application just needs to call event_dispatch()
and then add or remove events dynamically without having to change
the event loop.


## 📋 Package Information

- **Name**: `libevent`
- **Version**: `2.1.12`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Event notification library
- **Homepage**: [https://libevent.org/](https://libevent.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/gnxpxzfajq6f469akx81ws3c8b3c0v43-libevent-2.1.12.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libevent/package.nix:74`
- **Outputs**:
  - `dev`:  `/nix/store/gnxpxzfajq6f469akx81ws3c8b3c0v43-libevent-2.1.12`
  - `openssl`:  `/nix/store/gnxpxzfajq6f469akx81ws3c8b3c0v43-libevent-2.1.12`
  - `out`:  `/nix/store/gnxpxzfajq6f469akx81ws3c8b3c0v43-libevent-2.1.12`

## 🔗 Dependencies

- [[1dnb44k7lscpfkvsvbpvks0g623phgdl-883630f76cbf512003b81de25cd96cb75c6cf0f9.patch]]
- [[1jyxg41l6igmycw2kf6nn8jy25xrd3i8-libevent-2.1.12-stable.tar.gz]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[hix6rm0f4rx0hsdp31vaky4zvr67v6r6-update-autotools-gnu-config-scripts-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:45:33 UTC*
