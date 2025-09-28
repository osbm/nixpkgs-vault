---
aliases:
  - http2tcp
tags:
  - license/unknown
  - maintainers/clkamp
  - outputs/out
---

# http2tcp

## 📝 Description

The http2tcp tools allow to tunnel tcp connections (presumably
ssh) via syntactically correct http requests. It is designed to
work in the presence of so-called "transparent"
store-and-forward proxies disallowing POST requests.

It also turned out to be useful to stabilise connections where
the client's internet connection is unreliable (frequent long
network outages, rapidly changing IP address, etc).


## 📋 Package Information

- **Name**: `http2tcp`
- **Version**: `0.5`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tool for tunneling TCP connections via HTTP GET requests
- **Homepage**: [https://www.linta.de/~aehlig/http2tcp/](https://www.linta.de/~aehlig/http2tcp/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @clkamp


## 🔧 Build Information

- **Derivation Path**: `/nix/store/dynrvz2csl57ckyaf351pzdcmbvzgxsd-http2tcp-0.5.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ht/http2tcp/package.nix:33`
- **Outputs**:
  - `out`:  `/nix/store/dynrvz2csl57ckyaf351pzdcmbvzgxsd-http2tcp-0.5`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rll7p3xhj0jcq33z9kg8mf0np698c4n8-http2tcp-0.5.tar.gz]]
- [[xx660ihark6b7q4cj56vffd1ixjaqr91-python3-3.13.7-env]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:06:01 UTC*
