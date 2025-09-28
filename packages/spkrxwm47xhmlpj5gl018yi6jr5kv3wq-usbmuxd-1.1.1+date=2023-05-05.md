---
aliases:
  - usbmuxd
tags:
  - license/unknown
  - outputs/out
---

# usbmuxd

## 📝 Description

usbmuxd stands for "USB multiplexing daemon". This daemon is in charge of
multiplexing connections over USB to an iOS device. To users, it means
you can sync your music, contacts, photos, etc. over USB. To developers, it
means you can connect to any listening localhost socket on the device. usbmuxd
is not used for tethering data transfer which uses a dedicated USB interface as
a virtual network device. Multiple connections to different TCP ports can happen
in parallel. The higher-level layers are handled by libimobiledevice.


## 📋 Package Information

- **Name**: `usbmuxd`
- **Version**: `1.1.1+date=2023-05-05`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Socket daemon to multiplex connections from and to iOS devices
- **Homepage**: [https://github.com/libimobiledevice/usbmuxd](https://github.com/libimobiledevice/usbmuxd)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/spkrxwm47xhmlpj5gl018yi6jr5kv3wq-usbmuxd-1.1.1+date=2023-05-05.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/us/usbmuxd/package.nix:45`
- **Outputs**:
  - `out`:  `/nix/store/spkrxwm47xhmlpj5gl018yi6jr5kv3wq-usbmuxd-1.1.1+date=2023-05-05`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[fy9wjrqf0pzd5x3rvy665v50ff747wfd-libusb-1.0.29]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[n7cncn0g5i7gc4hn0w3fm8gaplgwlsgy-libimobiledevice-1.3.0-unstable-2024-05-20]]
- [[p2kv96lqj1h23an7mv0vnj6n887nc775-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:17:57 UTC*
