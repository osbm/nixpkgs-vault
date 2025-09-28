---
aliases:
  - nanopb
tags:
  - license/unknown
  - maintainers/kalbasit
  - maintainers/liarokapisv
  - outputs/out
---

# nanopb

## 📝 Description

Nanopb is a small code-size Protocol Buffers implementation in ansi C. It
is especially suitable for use in microcontrollers, but fits any memory
restricted system.

- Homepage: jpa.kapsi.fi/nanopb
- Documentation: jpa.kapsi.fi/nanopb/docs
- Downloads: jpa.kapsi.fi/nanopb/download
- Forum: groups.google.com/forum/#!forum/nanopb

In order to use the nanopb options in your proto files, you'll need to
tell protoc where to find the nanopb.proto file.
You can do so with the --proto_path (-I) option to add the directory
${nanopb}/share/nanopb/generator/proto like so:

protoc --proto_path=. --proto_path=${nanopb}/share/nanopb/generator/proto --plugin=protoc-gen-nanopb=${nanopb}/bin/protoc-gen-nanopb --nanopb_out=out file.proto


## 📋 Package Information

- **Name**: `nanopb`
- **Version**: `0.4.9.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Protocol Buffers with small code size
- **Homepage**: [https://jpa.kapsi.fi/nanopb/](https://jpa.kapsi.fi/nanopb/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @kalbasit
- @liarokapisv


## 🔧 Build Information

- **Derivation Path**: `/nix/store/xwmnb22433b3fp7c2jxj9vfgqv208rsd-nanopb-0.4.9.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/na/nanopb/package.nix:107`
- **Outputs**:
  - `out`:  `/nix/store/xwmnb22433b3fp7c2jxj9vfgqv208rsd-nanopb-0.4.9.1`

## 🔗 Dependencies

- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[d3jnz3bf16zyrlqdrsidkzq5k5zg0ic5-nanopb-generator-0.4.9.1]]
- [[lb481za4z3ykw6vx7zdwchc05ykimkr5-source]]
- [[v83gcqji43l1v2v1rg3h59v5sk7jraz4-nanopb-runtime-0.4.9.1]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:14:55 UTC*
