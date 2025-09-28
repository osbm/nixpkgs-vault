---
aliases:
  - nettle
tags:
  - license/unknown
  - maintainers/vcunat
  - outputs/dev
  - outputs/out
---

# nettle

## 📝 Description

Nettle is a cryptographic library that is designed to fit
easily in more or less any context: In crypto toolkits for
object-oriented languages (C++, Python, Pike, ...), in
applications like LSH or GNUPG, or even in kernel space.  In
most contexts, you need more than the basic cryptographic
algorithms, you also need some way to keep track of available
algorithms, their properties and variants.  You often have
some algorithm selection process, often dictated by a protocol
you want to implement.

And as the requirements of applications differ in subtle and
not so subtle ways, an API that fits one application well can
be a pain to use in a different context.  And that is why
there are so many different cryptographic libraries around.

Nettle tries to avoid this problem by doing one thing, the
low-level crypto stuff, and providing a simple but general
interface to it.  In particular, Nettle doesn't do algorithm
selection.  It doesn't do memory allocation. It doesn't do any
I/O.


## 📋 Package Information

- **Name**: `nettle`
- **Version**: `3.10.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Cryptographic library
- **Homepage**: [https://www.lysator.liu.se/~nisse/nettle/](https://www.lysator.liu.se/~nisse/nettle/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @vcunat


## 🔧 Build Information

- **Derivation Path**: `/nix/store/zcqnvxxzciz32hjngdfybshixmx2lc8m-nettle-3.10.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/libraries/nettle/generic.nix:44`
- **Outputs**:
  - `dev`:  `/nix/store/zcqnvxxzciz32hjngdfybshixmx2lc8m-nettle-3.10.2`
  - `out`:  `/nix/store/zcqnvxxzciz32hjngdfybshixmx2lc8m-nettle-3.10.2`

## 🔗 Dependencies

- [[5fnl19ibazlhzcrmxg56s11v29rw1cqc-gmp-with-cxx-6.3.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i9kj1nhzkg91xsq8ny4z4hipl0b42kad-gcc-wrapper-14.3.0]]
- [[ji5f9h32ks9p6qh7v8qq9q0rmy6zlh3m-nettle-3.10.2.tar.gz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[sp2vq01660i7gmsgddk4x9di14gwny4m-gnum4-1.4.20]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:19:31 UTC*
