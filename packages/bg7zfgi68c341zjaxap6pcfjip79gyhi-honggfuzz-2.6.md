---
aliases:
  - honggfuzz
tags:
  - license/unknown
  - maintainers/cpu
  - maintainers/chivay
  - outputs/out
---

# honggfuzz

## 📝 Description

Honggfuzz is a security oriented, feedback-driven, evolutionary,
easy-to-use fuzzer with interesting analysis options. It is
multi-process and multi-threaded, blazingly fast when the persistent
fuzzing mode is used and has a solid track record of uncovered security
bugs.

Honggfuzz uses low-level interfaces to monitor processes and it will
discover and report hijacked/ignored signals from crashes. Feed it
a simple corpus directory (can even be empty for the feedback-driven
fuzzing), and it will work its way up, expanding it by utilizing
feedback-based coverage metrics.


## 📋 Package Information

- **Name**: `honggfuzz`
- **Version**: `2.6`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Security oriented, feedback-driven, evolutionary, easy-to-use fuzzer
- **Homepage**: [https://honggfuzz.dev/](https://honggfuzz.dev/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @cpu
- @chivay


## 🔧 Build Information

- **Derivation Path**: `/nix/store/bg7zfgi68c341zjaxap6pcfjip79gyhi-honggfuzz-2.6.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ho/honggfuzz/package.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/bg7zfgi68c341zjaxap6pcfjip79gyhi-honggfuzz-2.6`

## 🔗 Dependencies

- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[2kyd964z0dfx8xsdd3vaxvz275ybzqxi-blocksruntime-0-unstable-2017-10-28]]
- [[5h6ng7076xwc5ckiy5m6bqhnh6r7ylqr-clang-wrapper-19.1.7]]
- [[6b5cgp72v8vd6812ysrwb3kj4ijakaq3-llvm-19.1.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bsdfb2xa35m8s4g8fc3brby8xcrlr0n5-libunwind-1.8.2]]
- [[nmkmyb7a228amldqqq405d7q9149hgyx-binutils-2.44]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pa8q7qqs7w7hv6ianpb5a6fsjpkh86ll-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:06:24 UTC*
