---
aliases:
  - refind
tags:
  - license/unknown
  - maintainers/johnrtitor
  - maintainers/RossComputerGuy
  - outputs/man
  - outputs/out
---

# refind

## 📝 Description

rEFInd is a graphical boot manager for EFI- and UEFI-based
computers, such as all Intel-based Macs and recent (most 2011
and later) PCs. rEFInd presents a boot menu showing all the EFI
boot loaders on the EFI-accessible partitions, and optionally
BIOS-bootable partitions on Macs. EFI-compatible OSes, including
Linux, provide boot loaders that rEFInd can detect and
launch. rEFInd can launch Linux EFI boot loaders such as ELILO,
GRUB Legacy, GRUB 2, and 3.3.0 and later kernels with EFI stub
support. EFI filesystem drivers for ext2/3/4fs, ReiserFS, HFS+,
and ISO-9660 enable rEFInd to read boot loaders from these
filesystems, too. rEFInd's ability to detect boot loaders at
runtime makes it very easy to use, particularly when paired with
Linux kernels that provide EFI stub support.


## 📋 Package Information

- **Name**: `refind`
- **Version**: `0.14.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Graphical {,U}EFI boot manager
- **Homepage**: [http://refind.sourceforge.net/](http://refind.sourceforge.net/)
- **License**: `unknown`
- **Platforms**: `i686-linux`, `x86_64-linux`, `aarch64-linux`
## 👥 Maintainers

- @johnrtitor
- @RossComputerGuy


## 🔧 Build Information

- **Derivation Path**: `/nix/store/yll38x1ah0z0011scc379syb4sc16r2n-refind-0.14.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/re/refind/package.nix:170`
- **Outputs**:
  - `man`:  `/nix/store/yll38x1ah0z0011scc379syb4sc16r2n-refind-0.14.2`
  - `out`:  `/nix/store/yll38x1ah0z0011scc379syb4sc16r2n-refind-0.14.2`

## 🔗 Dependencies

- [[18d6j78sgc82sbxyncq2fii0m0hbanwv-refind-src-0.14.2.tar.gz]]
- [[1flrg6g5ply4l2kqrzh9fxycrvby97l5-gnu-efi-3.0.19]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]
- [[zn9n5b7sbddv4py8fn59lny4pdb3m9sc-efibootmgr-18]]

## 📁 Input Sources

- `/nix/store/7s96dlmbr08hvqpxgmw2rdwxq569bp51-0001-toolchain.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/qzji3bxdm1acv648g72v4dgibcf9yzq7-0002-preserve-dates.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:16:52 UTC*
