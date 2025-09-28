---
aliases:
  - securefs
tags:
  - license/unknown
  - outputs/out
---

# securefs

## 📝 Description

Securefs is a filesystem in userspace (FUSE) that transparently encrypts
and authenticates data stored. It is particularly designed to secure
data stored in the cloud.
Securefs mounts a regular directory onto a mount point. The mount point
appears as a regular filesystem, where one can read/write/create files,
directories and symbolic links. The underlying directory will be
automatically updated to contain the encrypted and authenticated
contents.


## 📋 Package Information

- **Name**: `securefs`
- **Version**: `0.13.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Transparent encryption filesystem
- **Homepage**: [https://github.com/netheril96/securefs](https://github.com/netheril96/securefs)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/fnk3ss1bgs6196y4wrp44ca35gfa1qnm-securefs-0.13.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/se/securefs/package.nix:26`
- **Outputs**:
  - `out`:  `/nix/store/fnk3ss1bgs6196y4wrp44ca35gfa1qnm-securefs-0.13.1`

## 🔗 Dependencies

- [[6v03vcd7gnipi9dri34hj1paxhhnmv86-source]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[ji56v9i7bdf14w53nxy71cpr8rrrvmma-fuse-2.9.9]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:04:38 UTC*
