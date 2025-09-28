---
aliases:
  - linuxKernel.packages.linux_5_4.apfs
tags:
  - license/unknown
  - maintainers/Luflosi
  - outputs/out
---

# linuxKernel.packages.linux_5_4.apfs

## 📝 Description

The Apple File System (APFS) is the copy-on-write filesystem currently
used on all Apple devices. This module provides a degree of experimental
support on Linux.
If you make use of the write support, expect data corruption.
Read-only support is somewhat more complete, with sealed volumes,
snapshots, and all the missing compression algorithms recently added.
Encryption is still not in the works though.


## 📋 Package Information

- **Name**: `linuxKernel.packages.linux_5_4.apfs`
- **Version**: `0.3.15-5.4.299`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: APFS module for linux
- **Homepage**: [https://github.com/linux-apfs/linux-apfs-rw](https://github.com/linux-apfs/linux-apfs-rw)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @Luflosi


## 🔧 Build Information

- **Derivation Path**: `/nix/store/hhzm6g2rih2ma1h1z9lcbpmn1a26ljzq-apfs-0.3.15-5.4.299.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/apfs/default.nix:41`
- **Outputs**:
  - `out`:  `/nix/store/hhzm6g2rih2ma1h1z9lcbpmn1a26ljzq-apfs-0.3.15-5.4.299`

## 🔗 Dependencies

- [[0i6l8h1ds9dkr1ivc77hzsdl51mfahm0-pahole-1.30]]
- [[6r5cldhv0mdkwwia0zdchk4aar0azvrd-gcc-14.3.0]]
- [[8qvzhry004aybdbrb9y8c387ah9k0mps-binutils-2.44]]
- [[96vv66p4biczw55qf9jhwqn7awwn861h-elfutils-0.193]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[ha28phg14w5mvz13lwwyl63bcla9kpvs-source]]
- [[i9kj1nhzkg91xsq8ny4z4hipl0b42kad-gcc-wrapper-14.3.0]]
- [[kvysay8plzjaxgvj64sxz0b4d9xc25n0-binutils-wrapper-2.44]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qxfy048h57w5zgyl85wjv0npd8inj0iw-linux-5.4.299]]
- [[ypycd29v643n3f7r3fhmm7bzaxqnwakk-uname]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:12:33 UTC*
