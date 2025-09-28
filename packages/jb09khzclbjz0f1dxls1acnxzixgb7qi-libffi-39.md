---
aliases:
  - darwin.libffi
tags:
  - not-available
  - license/unknown
  - maintainers/emilazy
  - maintainers/reckenrode
  - maintainers/toonn
  - outputs/dev
  - outputs/info
  - outputs/man
  - outputs/out
---

# darwin.libffi

## 📝 Description

The libffi library provides a portable, high level programming
interface to various calling conventions.  This allows a
programmer to call any function specified by a call interface
description at run-time.

FFI stands for Foreign Function Interface.  A foreign function
interface is the popular name for the interface that allows code
written in one language to call code written in another
language.  The libffi library really only provides the lowest,
machine dependent layer of a fully featured foreign function
interface.  A layer must exist above libffi that handles type
conversions for values passed between the two languages.


## 📋 Package Information

- **Name**: `darwin.libffi`
- **Version**: `39`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Foreign function call interface library
- **Homepage**: [https://github.com/apple-oss-distributions/libffi/](https://github.com/apple-oss-distributions/libffi/)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`
## 👥 Maintainers

- @emilazy
- @reckenrode
- @toonn


## 🔧 Build Information

- **Derivation Path**: `/nix/store/jb09khzclbjz0f1dxls1acnxzixgb7qi-libffi-39.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/darwin/apple-source-releases/libffi/package.nix:105`
- **Outputs**:
  - `dev`:  `/nix/store/jb09khzclbjz0f1dxls1acnxzixgb7qi-libffi-39`
  - `info`:  `/nix/store/jb09khzclbjz0f1dxls1acnxzixgb7qi-libffi-39`
  - `man`:  `/nix/store/jb09khzclbjz0f1dxls1acnxzixgb7qi-libffi-39`
  - `out`:  `/nix/store/jb09khzclbjz0f1dxls1acnxzixgb7qi-libffi-39`

## 🔗 Dependencies

- [[b4pa5k4if2jl33f1ynicjwz2nihy4z3c-texinfo-7.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[mlhslzxpb7nmiqqpisv92y2kxnqp5wv5-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[v4dbfbxcdcywcfqmns3lfklh26b35s48-dejagnu-1.6.3]]

## 📁 Input Sources

- `/nix/store/cqjcv9q2znmycyp61wfwnyjhwrzi7gcl-automake-1.18.patch`
- `/nix/store/i5l5j0dk17mxas7b3qdk6av9xrakf5f3-fix-tramponline-memory-leak.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/mc17ipiyvw1jpy6axn33c37yd08na496-llvm-18-compatibility.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:04:44 UTC*
