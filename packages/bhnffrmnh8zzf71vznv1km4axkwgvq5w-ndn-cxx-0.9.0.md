---
aliases:
  - ndn-cxx
tags:
  - license/unknown
  - maintainers/sjmackenzie
  - maintainers/bertof
  - outputs/out
---

# ndn-cxx

## 📝 Description

ndn-cxx is a C++ library, implementing Named Data Networking (NDN)
primitives that can be used to implement various NDN applications.
NDN operates by addressing and delivering Content Objects directly
by Name instead of merely addressing network end-points. In addition,
the NDN security model explicitly secures individual Content Objects
rather than securing the connection or “pipe”. Named and secured
content resides in distributed caches automatically populated on
demand or selectively pre-populated. When requested by name, NDN
delivers named content to the user from the nearest cache, thereby
traversing fewer network hops, eliminating redundant requests,
and consuming less resources overall.


## 📋 Package Information

- **Name**: `ndn-cxx`
- **Version**: `0.9.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Named Data Networking (NDN) or Content Centric Networking (CCN) abstraction
- **Homepage**: [https://named-data.net/](https://named-data.net/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @sjmackenzie
- @bertof


## 🔧 Build Information

- **Derivation Path**: `/nix/store/bhnffrmnh8zzf71vznv1km4axkwgvq5w-ndn-cxx-0.9.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/nd/ndn-cxx/package.nix:56`
- **Outputs**:
  - `out`:  `/nix/store/bhnffrmnh8zzf71vznv1km4axkwgvq5w-ndn-cxx-0.9.0`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[4b4zc0cg1hj290r7v12a7s5fyx0lfzfz-doxygen-1.14.0]]
- [[6f2psfx7f4xqqwq4cr5gs6mz7m3p9x3m-sqlite-3.50.2]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i3ph2z8ayfgsqlrj9y2gwiyv3fmj6w10-boost-1.87.0]]
- [[jj74sk0knhz05zywad0syxjhzhv59nj6-waf-setup-hook]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[mxniklnk1kcl8j655vnk3wcw1zd2hykj-python3.13-sphinx-8.2.3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[v829yj1962jswin8napfwppn2ci0g841-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:16:24 UTC*
