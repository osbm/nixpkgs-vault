---
aliases:
  - idevicerestore
tags:
  - license/unknown
  - maintainers/nh2
  - outputs/out
---

# idevicerestore

## 📝 Description

The idevicerestore tool allows to restore firmware files to iOS devices.

It is a full reimplementation of all granular steps which are performed during
restore of a firmware to a device.

In general, upgrades and downgrades are possible, however subject to
availability of SHSH blobs from Apple for signing the firmare files.

To restore a device to some firmware, simply run the following:
$ sudo idevicerestore -l

This will download and restore a device to the latest firmware available.


## 📋 Package Information

- **Name**: `idevicerestore`
- **Version**: `1.0.0+date=2023-05-23`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Restore/upgrade firmware of iOS devices
- **Homepage**: [https://github.com/libimobiledevice/idevicerestore](https://github.com/libimobiledevice/idevicerestore)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @nh2


## 🔧 Build Information

- **Derivation Path**: `/nix/store/2nzg83rp19wgr2ywsxixg1nqcpn2ap8d-idevicerestore-1.0.0+date=2023-05-23.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/id/idevicerestore/package.nix:47`
- **Outputs**:
  - `out`:  `/nix/store/2nzg83rp19wgr2ywsxixg1nqcpn2ap8d-idevicerestore-1.0.0+date=2023-05-23`

## 🔗 Dependencies

- [[58pfzq0ll9n7rk65kjkqzjrsx9fl5bk7-source]]
- [[5lmnv4qikhycr4942lvjrw8sbygckqrc-libzip-1.11.4]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[g1smgp5dhq2ii8np7vm7n5znki3ak1b1-curl-8.14.1]]
- [[igb8afg3picmlk9rvzfqk2414c4ms7y9-libirecovery-1.2.1]]
- [[k96rvnnc5wwc5ayzv8rncpy4rh1jlq6x-libusbmuxd-2.1.1]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[n7cncn0g5i7gc4hn0w3fm8gaplgwlsgy-libimobiledevice-1.3.0-unstable-2024-05-20]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:09:24 UTC*
