---
aliases:
  - primesieve
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

# primesieve

## 📝 Description

primesieve is a command-line program and C/C++ library for quickly
generating prime numbers. It is very cache efficient, it detects your
CPU's L1 & L2 cache sizes and allocates its main data structures
accordingly. It is also multi-threaded by default, it uses all available
CPU cores whenever possible i.e. if sequential ordering is not
required. primesieve can generate primes and prime k-tuplets up to 264.


## 📋 Package Information

- **Name**: `primesieve`
- **Version**: `12.9`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Fast C/C++ prime number generator
- **Homepage**: [https://primesieve.org/](https://primesieve.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @timokau
- @7c6f434c
- @collares


## 🔧 Build Information

- **Derivation Path**: `/nix/store/x4pigav4rcqy3w21dgvfymiaks77wazg-primesieve-12.9.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/pr/primesieve/package.nix:41`
- **Outputs**:
  - `dev`:  `/nix/store/x4pigav4rcqy3w21dgvfymiaks77wazg-primesieve-12.9`
  - `lib`:  `/nix/store/x4pigav4rcqy3w21dgvfymiaks77wazg-primesieve-12.9`
  - `man`:  `/nix/store/x4pigav4rcqy3w21dgvfymiaks77wazg-primesieve-12.9`
  - `out`:  `/nix/store/x4pigav4rcqy3w21dgvfymiaks77wazg-primesieve-12.9`

## 🔗 Dependencies

- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[r9inlq7m528d1aszh5m11dj7i5p567cs-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:29:05 UTC*
