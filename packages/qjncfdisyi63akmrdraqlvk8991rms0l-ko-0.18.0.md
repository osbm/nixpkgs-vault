---
aliases:
  - ko
tags:
  - license/unknown
  - maintainers/NickCao
  - maintainers/06kellyjac
  - maintainers/vdemeester
  - maintainers/developer-guy
  - outputs/out
---

# ko

## 📝 Description

ko is a simple, fast container image builder for Go applications.
It's ideal for use cases where your image contains a single Go application without any/many dependencies on the OS base image (e.g. no cgo, no OS package dependencies).
ko builds images by effectively executing go build on your local machine, and as such doesn't require docker to be installed. This can make it a good fit for lightweight CI/CD use cases.
ko makes multi-platform builds easy, produces SBOMs by default, and includes support for simple YAML templating which makes it a powerful tool for Kubernetes applications.


## 📋 Package Information

- **Name**: `ko`
- **Version**: `0.18.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Build and deploy Go applications
- **Homepage**: [https://github.com/ko-build/ko](https://github.com/ko-build/ko)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @NickCao
- @06kellyjac
- @vdemeester
- @developer-guy


## 🔧 Build Information

- **Derivation Path**: `/nix/store/qjncfdisyi63akmrdraqlvk8991rms0l-ko-0.18.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ko/ko/package.nix:69`
- **Outputs**:
  - `out`:  `/nix/store/qjncfdisyi63akmrdraqlvk8991rms0l-ko-0.18.0`

## 🔗 Dependencies

- [[5p4py0ipzs99czbfqcps94kmhh2xypa8-ko-0.18.0-go-modules]]
- [[5x9g9n8gzrdy806j6nzvyia7zv2pyzhg-git-minimal-2.51.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[nkshzjjqdw9fjq9bb75f20w3pmdrci09-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:12:14 UTC*
