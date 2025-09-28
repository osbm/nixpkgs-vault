---
aliases:
  - primecount
tags:
  - license/unknown
  - maintainers/timokau
  - maintainers/7c6f434c
  - maintainers/collares
  - outputs/dev
  - outputs/lib
  - outputs/man
  - outputs/out
---

# primecount

## 📝 Description

primecount is a command-line program and C/C++ library that counts the
primes below an integer x ≤ 10^31 using highly optimized implementations
of the combinatorial prime counting algorithms.

primecount includes implementations of all important combinatorial prime
counting algorithms known up to this date all of which have been
parallelized using OpenMP. primecount contains the first ever open source
implementations of the Deleglise-Rivat algorithm and Xavier Gourdon's
algorithm (that works). primecount also features a novel load balancer
that is shared amongst all implementations and that scales up to hundreds
of CPU cores. primecount has already been used to compute several prime
counting function world records.


## 📋 Package Information

- **Name**: `primecount`
- **Version**: `7.19`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Fast prime counting function implementations
- **Homepage**: [https://github.com/kimwalisch/primecount](https://github.com/kimwalisch/primecount)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @timokau
- @7c6f434c
- @collares


## 🔧 Build Information

- **Derivation Path**: `/nix/store/r4w13riry7rk6rp4hdmj6byi2myyvi8y-primecount-7.19.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/pr/primecount/package.nix:51`
- **Outputs**:
  - `dev`:  `/nix/store/r4w13riry7rk6rp4hdmj6byi2myyvi8y-primecount-7.19`
  - `lib`:  `/nix/store/r4w13riry7rk6rp4hdmj6byi2myyvi8y-primecount-7.19`
  - `man`:  `/nix/store/r4w13riry7rk6rp4hdmj6byi2myyvi8y-primecount-7.19`
  - `out`:  `/nix/store/r4w13riry7rk6rp4hdmj6byi2myyvi8y-primecount-7.19`

## 🔗 Dependencies

- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[x4pigav4rcqy3w21dgvfymiaks77wazg-primesieve-12.9]]
- [[zhfvrxxix36b6pk7ss6grmpkj3nfm0m7-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:29:05 UTC*
