---
aliases:
  - btrfs-auto-snapshot
tags:
  - license/unknown
  - maintainers/motiejus
  - outputs/out
---

# btrfs-auto-snapshot

## 📝 Description

btrfs-auto-snapshot is a Bash script designed to bring as much of the
functionality of the wonderful ZFS snapshot tool zfs-auto-snapshot to
BTRFS as possible. Designed to run from cron (using
/etc/cron.{daily,hourly,weekly}) it automatically creates a snapshot of
the specified BTRFS filesystem (or, optionally, all of them) and then
automatically purges the oldest snapshots of that type (hourly, daily, et
al) based on a user-defined retention policy.

Snapshots are stored in a '.btrfs' directory at the root of the BTRFS
filesystem being snapped and are read-only by default.


## 📋 Package Information

- **Name**: `btrfs-auto-snapshot`
- **Version**: `2.0.4`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: BTRFS Automatic Snapshot Service for Linux
- **Homepage**: [https://github.com/hunleyd/btrfs-auto-snapshot](https://github.com/hunleyd/btrfs-auto-snapshot)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @motiejus


## 🔧 Build Information

- **Derivation Path**: `/nix/store/1jmz4ch82prrl00192irif5pjp84gkbl-btrfs-auto-snapshot-2.0.4.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/bt/btrfs-auto-snapshot/package.nix:53`
- **Outputs**:
  - `out`:  `/nix/store/1jmz4ch82prrl00192irif5pjp84gkbl-btrfs-auto-snapshot-2.0.4`

## 🔗 Dependencies

- [[0yfsyywy1gk58b930lhrawa8g74xr6c3-source]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[3sbg89qzpa2lvjl41qjyvdna5hap16hm-btrfs-progs-6.16]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[9zshxf6kk537mzc627ynbj5lgp1qff15-util-linux-2.41.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cflrzgbglppcagf2jfix9hgq25126m9z-gnugrep-3.12]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q331wl66bksvjp5qq0b3dhbcw3fx09x2-gawk-5.3.2]]
- [[q6r8nhgmx37s1vk3580hn9q1illlh9n2-getopt-1.1.6]]
- [[whmvyjphw10d78zfrb04kqjlc0dy68z3-gnused-4.9]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:48:10 UTC*
