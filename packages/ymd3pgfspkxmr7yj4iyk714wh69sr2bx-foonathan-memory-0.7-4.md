---
aliases:
  - foonathan-memory
tags:
  - license/unknown
  - maintainers/panicgh
  - outputs/dev
  - outputs/out
---

# foonathan-memory

## 📝 Description

The C++ STL allocator model has various flaws. For example, they are
fixed to a certain type, because they are almost necessarily required to
be templates. So you can't easily share a single allocator for multiple
types. In addition, you can only get a copy from the containers and not
the original allocator object. At least with C++11 they are allowed to be
stateful and so can be made object not instance based. But still, the
model has many flaws. Over the course of the years many solutions have
been proposed, for example EASTL. This library is another. But instead of
trying to change the STL, it works with the current implementation.


## 📋 Package Information

- **Name**: `foonathan-memory`
- **Version**: `0.7-4`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: STL compatible C++ memory allocator library
- **Homepage**: [https://memory.foonathan.net/](https://memory.foonathan.net/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @panicgh


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ymd3pgfspkxmr7yj4iyk714wh69sr2bx-foonathan-memory-0.7-4.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/fo/foonathan-memory/package.nix:52`
- **Outputs**:
  - `dev`:  `/nix/store/ymd3pgfspkxmr7yj4iyk714wh69sr2bx-foonathan-memory-0.7-4`
  - `out`:  `/nix/store/ymd3pgfspkxmr7yj4iyk714wh69sr2bx-foonathan-memory-0.7-4`

## 🔗 Dependencies

- [[45k2h1fk6899yy2pdb3zdhhlp7my5aff-source]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[ifmw9799ky9lvz4zqg200wfqaq1bm5yq-doctest-2.4.11]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/3rffddh4531v2dm2bvx9675xxhswpisc-0001-Use-system-doctest.patch.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:48:23 UTC*
