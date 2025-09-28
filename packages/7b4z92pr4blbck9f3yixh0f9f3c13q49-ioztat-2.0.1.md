---
aliases:
  - ioztat
tags:
  - license/unknown
  - maintainers/numinit
  - outputs/out
---

# ioztat

## 📝 Description

ioztat is a storage load analysis tool for OpenZFS. It provides
iostat-like statistics at an individual dataset/zvol level.

The statistics offered are read and write operations per second, read and
write throughput per second, and the average size of read and write
operations issued in the current reporting interval. Viewing these
statistics at the individual dataset level allows system administrators
to identify storage "hot spots" in larger multi-tenant
systems -- particularly those with many VMs or containers operating
essentially independent workloads.


## 📋 Package Information

- **Name**: `ioztat`
- **Version**: `2.0.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Storage load analysis tool for OpenZFS
- **Homepage**: [https://github.com/jimsalterjrs/ioztat](https://github.com/jimsalterjrs/ioztat)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @numinit


## 🔧 Build Information

- **Derivation Path**: `/nix/store/7b4z92pr4blbck9f3yixh0f9f3c13q49-ioztat-2.0.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/io/ioztat/package.nix:42`
- **Outputs**:
  - `out`:  `/nix/store/7b4z92pr4blbck9f3yixh0f9f3c13q49-ioztat-2.0.1`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[az5k8l21vwlsmh6is5vm1kdyja90mh9g-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:14:01 UTC*
