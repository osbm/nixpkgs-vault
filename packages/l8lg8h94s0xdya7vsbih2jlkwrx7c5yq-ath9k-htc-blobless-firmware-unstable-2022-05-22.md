---
aliases:
  - ath9k-htc-blobless-firmware-unstable
tags:
  - license/unknown
  - outputs/out
---

# ath9k-htc-blobless-firmware-unstable

## 📝 Description

Firmware for Qualcomm Atheros cards which use the ath9k_htc.ko
Linux driver, supporting 802.11 abgn on both 2.4ghz and 5ghz
bands, 3x3-antenna MIMO, up to 600mbit/sec.

Most devices which use this driver are based on the Qualcomm
Atheros AR9271 chip, which is a PCIe device.  If your device
is connected via USB, it will also include a Qualcomm Atheros
AR7010, which bridges from a USB gadget interface to a PCIe
host interface.  This repository includes the firmware for
both chips.

This firmware is completely open source with no blobs, which
is quite rare in the wifi world.  Wifi chips have their own
dedicated general-purpose CPUs.  This source code allows you
to see what those CPUs are doing and modify their behavior.


## 📋 Package Information

- **Name**: `ath9k-htc-blobless-firmware-unstable`
- **Version**: `2022-05-22`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Blobless, open source wifi firmware for ath9k_htc.ko
- **Homepage**: [http://lists.infradead.org/mailman/listinfo/ath9k_htc_fw](http://lists.infradead.org/mailman/listinfo/ath9k_htc_fw)
- **License**: `unknown`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/l8lg8h94s0xdya7vsbih2jlkwrx7c5yq-ath9k-htc-blobless-firmware-unstable-2022-05-22.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/firmware/ath9k/default.nix:146`
- **Outputs**:
  - `out`:  `/nix/store/l8lg8h94s0xdya7vsbih2jlkwrx7c5yq-ath9k-htc-blobless-firmware-unstable-2022-05-22`

## 🔗 Dependencies

- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[a31hfg174g63m23lkhjdndpxymiby5nk-mpc-1.1.0.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[c6j37j163j4krdss09qklavi0n69nh51-binutils-2.35.tar.bz2]]
- [[hk63zcd4qzp62awbzf85jndpqa0185aj-gmp-6.2.0.tar.bz2]]
- [[jci0p69b8sqqkanlj0cciyqr2dfks3qz-mpfr-4.1.0.tar.bz2]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[s6i9l37pjwj8nld105kchhkl6rbc6vma-source]]
- [[sp2vq01660i7gmsgddk4x9di14gwny4m-gnum4-1.4.20]]
- [[vjgj8x10fvlcjcaa7p49mnqnh8pvjww8-gcc-10.2.0.tar.gz]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:41:29 UTC*
