---
aliases:
  - libossp_uuid
tags:
  - license/unknown
  - outputs/out
---

# libossp_uuid

## 📝 Description

OSSP uuid is a ISO-C:1999 application programming interface
(API) and corresponding command line interface (CLI) for the
generation of DCE 1.1, ISO/IEC 11578:1996 and RFC 4122
compliant Universally Unique Identifier (UUID). It supports
DCE 1.1 variant UUIDs of version 1 (time and node based),
version 3 (name based, MD5), version 4 (random number based)
and version 5 (name based, SHA-1). Additional API bindings are
provided for the languages ISO-C++:1998, Perl:5 and
PHP:4/5. Optional backward compatibility exists for the ISO-C
DCE-1.1 and Perl Data::UUID APIs.

UUIDs are 128 bit numbers which are intended to have a high
likelihood of uniqueness over space and time and are
computationally difficult to guess. They are globally unique
identifiers which can be locally generated without contacting
a global registration authority. UUIDs are intended as unique
identifiers for both mass tagging objects with an extremely
short lifetime and to reliably identifying very persistent
objects across a network.


## 📋 Package Information

- **Name**: `libossp_uuid`
- **Version**: `1.6.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: OSSP uuid ISO-C and C++ shared library
- **Homepage**: [http://www.ossp.org/pkg/lib/uuid/](http://www.ossp.org/pkg/lib/uuid/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/11kgh8wnlsz6343yafg9gpmamg3hhc3k-libossp-uuid-1.6.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libossp_uuid/package.nix:25`
- **Outputs**:
  - `out`:  `/nix/store/11kgh8wnlsz6343yafg9gpmamg3hhc3k-libossp-uuid-1.6.2`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qk7izm930lbzlsaxjvv4qrs0p5cfz8cx-uuid-1.6.2.tar.gz]]

## 📁 Input Sources

- `/nix/store/12lyvlxz6vhw9pk43iacgclbj99fbnmh-shtool.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:50:07 UTC*
