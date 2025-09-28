---
aliases:
  - linuxKernel.packages.linux_6_12_hardened.apfs
tags:
  - license/unknown
  - maintainers/Luflosi
  - outputs/out
---

# linuxKernel.packages.linux_6_12_hardened.apfs

## 📝 Description

The Apple File System (APFS) is the copy-on-write filesystem currently
used on all Apple devices. This module provides a degree of experimental
support on Linux.
If you make use of the write support, expect data corruption.
Read-only support is somewhat more complete, with sealed volumes,
snapshots, and all the missing compression algorithms recently added.
Encryption is still not in the works though.


## 📋 Package Information

- **Name**: `linuxKernel.packages.linux_6_12_hardened.apfs`
- **Version**: `0.3.15-6.12.43`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: APFS module for linux
- **Homepage**: [https://github.com/linux-apfs/linux-apfs-rw](https://github.com/linux-apfs/linux-apfs-rw)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @Luflosi


## 🔧 Build Information

- **Derivation Path**: `/nix/store/s7kyswfa8d6k3lyxd4309nxiwnp5fcvq-apfs-0.3.15-6.12.43.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/apfs/default.nix:41`
- **Outputs**:
  - `out`:  `/nix/store/s7kyswfa8d6k3lyxd4309nxiwnp5fcvq-apfs-0.3.15-6.12.43`

## 🔗 Dependencies

- [[0i6l8h1ds9dkr1ivc77hzsdl51mfahm0-pahole-1.30]]
- [[6icggxnk1h5aam320l8x83gbi8f7xhkc-rust-bindgen-unwrapped-0.72.0]]
- [[6r5cldhv0mdkwwia0zdchk4aar0azvrd-gcc-14.3.0]]
- [[8qvzhry004aybdbrb9y8c387ah9k0mps-binutils-2.44]]
- [[96vv66p4biczw55qf9jhwqn7awwn861h-elfutils-0.193]]
- [[ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7]]
- [[bj2cabm1hsq8jgm6y2znmsldkbdp1i94-rustc-1.89.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[ha28phg14w5mvz13lwwyl63bcla9kpvs-source]]
- [[i9kj1nhzkg91xsq8ny4z4hipl0b42kad-gcc-wrapper-14.3.0]]
- [[kvysay8plzjaxgvj64sxz0b4d9xc25n0-binutils-wrapper-2.44]]
- [[kwgskdwfgqc49fvj0bwjmxnyssz82fj5-linux-hardened-6.12.43]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qvynva88na0r7zzjr2sn9b7122hd5p7v-uname]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:20:51 UTC*
