---
aliases:
  - git-vendor
tags:
  - license/unknown
  - outputs/bin
  - outputs/doc
  - outputs/man
  - outputs/out
---

# git-vendor

## 📝 Description

git-vendor is a wrapper around git-subtree commands for checking out and updating vendored dependencies.

By default git-vendor conforms to the pattern used for vendoring golang dependencies:
  * Dependencies are stored under vendor/ directory in the repo.
  * Dependencies are stored under the fully qualified project path.
      e.g. https://github.com/brettlangdon/forge will be stored under vendor/github.com/brettlangdon/forge.


## 📋 Package Information

- **Name**: `git-vendor`
- **Version**: `1.3.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Git command for managing vendored dependencies
- **Homepage**: [https://github.com/brettlangdon/git-vendor](https://github.com/brettlangdon/git-vendor)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/lfz6ly6gdn31x083538r0l9y3v418r06-git-vendor-1.3.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/gi/git-vendor/package.nix:64`
- **Outputs**:
  - `bin`:  `/nix/store/lfz6ly6gdn31x083538r0l9y3v418r06-git-vendor-1.3.0`
  - `doc`:  `/nix/store/lfz6ly6gdn31x083538r0l9y3v418r06-git-vendor-1.3.0`
  - `man`:  `/nix/store/lfz6ly6gdn31x083538r0l9y3v418r06-git-vendor-1.3.0`
  - `out`:  `/nix/store/lfz6ly6gdn31x083538r0l9y3v418r06-git-vendor-1.3.0`

## 🔗 Dependencies

- [[63la4w74vzhjsc5ncn9fvj00833hk40n-common-file-actions.sh]]
- [[6d8hr2b268w4d3hqihr6h9i345zjgfc2-git]]
- [[a21gd5y8xssa7f1a359qmb57ls6yxz40-check-for-remaining-files.sh]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[kmpvilx0cr0qwqfldxqb8wxzl7b8ndz8-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:03:46 UTC*
