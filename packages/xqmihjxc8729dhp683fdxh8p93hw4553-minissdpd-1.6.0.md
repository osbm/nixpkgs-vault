---
aliases:
  - minissdpd
tags:
  - license/unknown
  - outputs/out
---

# minissdpd

## 📝 Description

MiniSSDPd receives NOTIFY packets and stores (caches) that information
for later use by UPnP Control Points on the machine. MiniSSDPd receives
M-SEARCH packets and answers on behalf of the UPnP devices running on
the machine. Software must be patched in order to take advantage of
MiniSSDPd, and MiniSSDPd must be started before any other UPnP program.


## 📋 Package Information

- **Name**: `minissdpd`
- **Version**: `1.6.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Small daemon to speed up UPnP device discoveries
- **Homepage**: [http://miniupnp.free.fr/minissdpd.html](http://miniupnp.free.fr/minissdpd.html)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/xqmihjxc8729dhp683fdxh8p93hw4553-minissdpd-1.6.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/mi/minissdpd/package.nix:34`
- **Outputs**:
  - `out`:  `/nix/store/xqmihjxc8729dhp683fdxh8p93hw4553-minissdpd-1.6.0`

## 🔗 Dependencies

- [[4ikqf2l4p1q7n6qypj454k476ql2h631-libnfnetlink-1.0.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[l71bspg84vjp156gwprxgvvq30qdxw5i-minissdpd-1.6.0.tar.gz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/42vcp6771ppxd45ml3mbzpxkmjq3rjbk-makefile-install-dir.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:22:42 UTC*
