---
aliases:
  - profile-sync-daemon
tags:
  - license/unknown
  - maintainers/prikhi
  - outputs/out
---

# profile-sync-daemon

## 📝 Description

Profile-sync-daemon (psd) is a tiny pseudo-daemon designed to manage your
browser's profile in tmpfs and to periodically sync it back to your
physical disc (HDD/SSD). This is accomplished via a symlinking step and
an innovative use of rsync to maintain back-up and synchronization
between the two. One of the major design goals of psd is a completely
transparent user experience.


## 📋 Package Information

- **Name**: `profile-sync-daemon`
- **Version**: `6.50`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Syncs browser profile dirs to RAM
- **Homepage**: [https://github.com/graysky2/profile-sync-daemon](https://github.com/graysky2/profile-sync-daemon)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @prikhi


## 🔧 Build Information

- **Derivation Path**: `/nix/store/dwqacf25zd9iwaxr1sbzrpsllhy97pay-profile-sync-daemon-6.50.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/pr/profile-sync-daemon/package.nix:33`
- **Outputs**:
  - `out`:  `/nix/store/dwqacf25zd9iwaxr1sbzrpsllhy97pay-profile-sync-daemon-6.50`

## 🔗 Dependencies

- [[4ilm20gxy0adnid8acay9fq6zfxc5p7p-source]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[9zshxf6kk537mzc627ynbj5lgp1qff15-util-linux-2.41.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:29:48 UTC*
