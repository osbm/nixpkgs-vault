---
aliases:
  - loccount
tags:
  - license/unknown
  - maintainers/calvertvl
  - outputs/out
---

# loccount

## 📝 Description

loccount is a re-implementation of David A. Wheeler's sloccount tool
in Go.  It is faster and handles more different languages. Because
it's one source file in Go, it is easier to maintain and extend than the
multi-file, multi-language implementation of the original.

The algorithms are largely unchanged and can be expected to produce
identical numbers for languages supported by both tools.  Python is
an exception; loccount corrects buggy counting of single-quote multiline
literals in sloccount 2.26.


## 📋 Package Information

- **Name**: `loccount`
- **Version**: `2.16`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Re-implementation of sloccount in Go
- **Homepage**: [https://gitlab.com/esr/loccount](https://gitlab.com/esr/loccount)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @calvertvl


## 🔧 Build Information

- **Derivation Path**: `/nix/store/i0fdglhx1azarn8c6jnal8xhlv3w2wlm-loccount-2.16.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/lo/loccount/package.nix:36`
- **Outputs**:
  - `out`:  `/nix/store/i0fdglhx1azarn8c6jnal8xhlv3w2wlm-loccount-2.16`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cwd8gdqz83rr29nkjrrjpij663rsna0p-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:16:24 UTC*
