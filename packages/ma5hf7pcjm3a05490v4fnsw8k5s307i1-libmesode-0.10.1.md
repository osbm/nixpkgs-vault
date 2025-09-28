---
aliases:
  - libmesode
tags:
  - license/unknown
  - maintainers/devhell
  - outputs/out
---

# libmesode

## 📝 Description

Reasons for forking:

- Remove Windows support
- Support only one XML Parser implementation (expat)
- Support only one SSL implementation (OpenSSL)

This simplifies maintenance of the library when used in Profanity.
Whilst Profanity will run against libstrophe, libmesode provides extra
TLS functionality such as manual SSL certificate verification.


## 📋 Package Information

- **Name**: `libmesode`
- **Version**: `0.10.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Fork of libstrophe (https://github.com/strophe/libstrophe) for use with Profanity XMPP Client
- **Homepage**: [https://github.com/profanity-im/libmesode/](https://github.com/profanity-im/libmesode/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @devhell


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ma5hf7pcjm3a05490v4fnsw8k5s307i1-libmesode-0.10.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libmesode/package.nix:40`
- **Outputs**:
  - `out`:  `/nix/store/ma5hf7pcjm3a05490v4fnsw8k5s307i1-libmesode-0.10.1`

## 🔗 Dependencies

- [[6f3qzi98831xs1ffwaw31wlvrap56zlk-source]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[7nw7qzp99bw4c256bm4hcapqx00r210p-check-0.15.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qzl8kni5a4xh81ampjh16cj72gkw4j4b-expat-2.7.1]]
- [[sv8lxxb30bqw2b360ni6rsp89mg2dvbp-libtool-2.5.4]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:48:45 UTC*
