---
aliases:
  - linuxKernel.packages.linux_5_4.hyperv-daemons
tags:
  - license/unknown
  - maintainers/peterhoeg
  - outputs/bin
  - outputs/lib
  - outputs/out
---

# linuxKernel.packages.linux_5_4.hyperv-daemons

## 📝 Description

This packages contains the daemons that are used by the Hyper-V hypervisor
on the host.

Microsoft calls their guest agents "Integration Services" which is why
we use that name here.


## 📋 Package Information

- **Name**: `linuxKernel.packages.linux_5_4.hyperv-daemons`
- **Version**: `5.4.299`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Integration Services for running NixOS under HyperV
- **Homepage**: [https://kernel.org](https://kernel.org)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @peterhoeg


## 🔧 Build Information

- **Derivation Path**: `/nix/store/3s14v7hndjasyjjlzy4savkdwpr1y6is-hyperv-daemons-5.4.299.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/hyperv-daemons/default.nix:123`
- **Outputs**:
  - `bin`:  `/nix/store/3s14v7hndjasyjjlzy4savkdwpr1y6is-hyperv-daemons-5.4.299`
  - `lib`:  `/nix/store/3s14v7hndjasyjjlzy4savkdwpr1y6is-hyperv-daemons-5.4.299`
  - `out`:  `/nix/store/3s14v7hndjasyjjlzy4savkdwpr1y6is-hyperv-daemons-5.4.299`

## 🔗 Dependencies

- [[4gwb34s96r5wc7xdz5k30g91fz5gl59c-hyperv-daemons-bin-5.4.299]]
- [[992ihg1wy3yhm95l99xj84l3wvkim7nm-hv-fcopy.service]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[d1jdn195x36h4zshxawb4m3phi8fn7b7-hv-vss.service]]
- [[il3w8s1nawpk3ag7v70hyj2klw3nldha-hv-kvp.service]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:13:07 UTC*
