---
aliases:
  - timeshift
tags:
  - license/unknown
  - maintainers/ShamrockLee
  - maintainers/bobby285271
  - outputs/out
---

# timeshift

## 📝 Description

TimeShift creates filesystem snapshots using rsync+hardlinks or BTRFS snapshots.
Snapshots can be restored using TimeShift installed on the system or from Live CD or USB.
This package comes with runtime dependencies of command utilities provided by rsync, coreutils, mount, umount, psmisc, cron and btrfs.
If you want to use the commands provided by the system, use timeshift-minimal instead.


## 📋 Package Information

- **Name**: `timeshift`
- **Version**: `25.07.7`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: System restore tool for Linux
- **Homepage**: [https://github.com/linuxmint/timeshift](https://github.com/linuxmint/timeshift)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @ShamrockLee
- @bobby285271


## 🔧 Build Information

- **Derivation Path**: `/nix/store/8m787fv29fakbbka17jclvz1kys7ddvf-timeshift-25.07.7.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/applications/backup/timeshift/default.nix:30`
- **Outputs**:
  - `out`:  `/nix/store/8m787fv29fakbbka17jclvz1kys7ddvf-timeshift-25.07.7`

## 🔗 Dependencies

- [[3sbg89qzpa2lvjl41qjyvdna5hap16hm-btrfs-progs-6.16]]
- [[41a0ay5lwck0bc9aks3hlb5b86niifp3-mount-util-linux-2.41.1]]
- [[474kivdzi525za8vzpgr0ils1k0qf8r3-wrap-gapps-hook]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[6lxc09wb9pgl24r09ikqvf0l26cbg07g-grub-2.12]]
- [[bfrhypf8s25npqqk6h8hi5qyr3apb3vr-gdk-pixbuf-2.42.12]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bnbwi3a3fibvl518mmdcm41bc5ba71f1-lndir-1.0.5]]
- [[bx5vb29j2jq9ggsibsq110i1qv2yqfa6-timeshift-25.07.7]]
- [[cgvwsi10vx699fgbj8r8gnwsr21k6gf5-psmisc-23.7]]
- [[qx3xgii89gvv75qp2k4al6b5a5ghzs3s-cron-4.1]]
- [[ryjnwzp9z4kky2sw70a9pphpnc7d7a6p-debianutils-5.23.2]]
- [[slcp4pdbh65jxz72z8vfrwwp4yki90ip-rsync-3.4.1]]
- [[vw9ps5df26syym597i1m4dv4fpf3m7wg-librsvg-2.60.0]]
- [[x0mvfnnw8a0z9w1hklv9n148p0g2vklg-umount-util-linux-2.41.1]]
- [[xf54p2f2dk2hrjjnmgb0gqgnvpgyk60l-shared-mime-info-2.4]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:11:30 UTC*
