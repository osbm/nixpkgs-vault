---
aliases:
  - donkey
tags:
  - license/unknown
  - maintainers/raboof
  - outputs/out
---

# donkey

## 📝 Description

Donkey is an alternative for S/KEY's "key" command.  The new feature that
the original key doesn't have is print an entry for skeykeys as
follows;

    kazu 0099 al02004          115d83956f1089b6  Apr 26,1995 22:13:27

This means that donkey is also an alternative for "keyinit".  Since the
entry is printed to stdout (not to /etc/skeykeys), you can easily send
it to a remote operator by e-mail (with a PGP signature or something).
So, it is possible to initiate S/KEY without logging in from the console of
the host.

The name "Donkey" is an acronym of "Don't Key".


## 📋 Package Information

- **Name**: `donkey`
- **Version**: `1.2.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Alternative for S/KEY's 'key' command
- **Homepage**: [https://devel.ringlet.net/security/donkey](https://devel.ringlet.net/security/donkey)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @raboof


## 🔧 Build Information

- **Derivation Path**: `/nix/store/v2fb4i2jpa1392lhqjr3dkj9pgcq0r4x-donkey-1.2.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/do/donkey/package.nix:33`
- **Outputs**:
  - `out`:  `/nix/store/v2fb4i2jpa1392lhqjr3dkj9pgcq0r4x-donkey-1.2.0`

## 🔗 Dependencies

- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[5srjrlnf3jgp3xg6gwrxb6ffdcj2s41q-libmd-1.1.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[j0xb8fbfslbp9141pjz4n5jydpd1ls2d-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:49:37 UTC*
