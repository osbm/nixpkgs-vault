---
aliases:
  - klee
tags:
  - broken
  - not-available
  - license/unknown
  - maintainers/numinit
  - outputs/out
---

# klee

## 📝 Description

KLEE is a symbolic virtual machine built on top of the LLVM compiler
infrastructure. Currently, there are two primary components:

1. The core symbolic virtual machine engine; this is responsible for
   executing LLVM bitcode modules with support for symbolic values. This
   is comprised of the code in lib/.

2. A POSIX/Linux emulation layer oriented towards supporting uClibc, with
   additional support for making parts of the operating system environment
   symbolic.

Additionally, there is a simple library for replaying computed inputs on
native code (for closed programs). There is also a more complicated
infrastructure for replaying the inputs generated for the POSIX/Linux
emulation layer, which handles running native programs in an environment
that matches a computed test input, including setting up files, pipes,
environment variables, and passing command line arguments.


## 📋 Package Information

- **Name**: `klee`
- **Version**: `3.1-unstable-2025-07-11`
- **Available**: ❌ No
- **Broken**: ⚠️ Yes
- **Description**: Symbolic virtual machine built on top of LLVM
- **Homepage**: [https://klee.github.io](https://klee.github.io)
- **License**: `unknown`
- **Platforms**: `x86_64-linux`
## 👥 Maintainers

- @numinit


## 🔧 Build Information

- **Derivation Path**: `/nix/store/hf30ayl1s4kylnzjavs657cf53n32yr9-klee-3.1-unstable-2025-07-11.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/applications/science/logic/klee/default.nix:242`
- **Outputs**:
  - `out`:  `/nix/store/hf30ayl1s4kylnzjavs657cf53n32yr9-klee-3.1-unstable-2025-07-11`

## 🔗 Dependencies

- [[1yibn9v0xv4m2pzp6ig11rgjc1k2nmx8-source]]
- [[6f2psfx7f4xqqwq4cr5gs6mz7m3p9x3m-sqlite-3.50.2]]
- [[6gws6n92iv1sxvqqin5n019pwksx4z8w-gtest-1.17.0]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[b4y19q75wdcxf0fbmwssaagk5qf1l2wv-clang-wrapper-18.1.8]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bpqyc2dgjkbmyg1gcfdyn9p8bk2b64yx-source]]
- [[inqmrj86x1lxakg6gbd4gnbhadzxg883-stp-2.3.4]]
- [[jsi9c6ldcrjqr7aa956vvxpr06gsmjrq-python3-3.13.7-env]]
- [[rbcdhs8mv7qy90sh5fbr6h04pb113yd0-cryptominisat-5.11.21]]
- [[rmcafjm4ks0fmbwgccin1n98ib4lnyxq-llvm-18.1.8]]
- [[rnxrff5q5w7d7rgfvlwixx8rphc2m416-python3.13-lit-18.1.8]]
- [[s3p916hlznamz7qvqqlvjnaczyzsh4qr-gperftools-2.17]]
- [[vlmikf07fis0kvvsx883rinwrwjcl612-klee-uclibc-1.4]]
- [[wdamnb83rgncqyzz29zna6xnkyr1xfjl-z3-4.15.3]]
- [[wza4l4zvyf4cbi4wpys2j1rw9wb181nc-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:11:13 UTC*
