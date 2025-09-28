---
aliases:
  - ath9k-htc-blobless-firmware
tags:
  - license/unknown
  - outputs/out
---

# ath9k-htc-blobless-firmware

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

- **Name**: `ath9k-htc-blobless-firmware`
- **Version**: `1.4.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Blobless, open source wifi firmware for ath9k_htc.ko
- **Homepage**: [http://lists.infradead.org/mailman/listinfo/ath9k_htc_fw](http://lists.infradead.org/mailman/listinfo/ath9k_htc_fw)
- **License**: `unknown`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/3l7i7w999n0px3rwxb04d5n9acpqw4l7-ath9k-htc-blobless-firmware-1.4.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/firmware/ath9k/default.nix:146`
- **Outputs**:
  - `out`:  `/nix/store/3l7i7w999n0px3rwxb04d5n9acpqw4l7-ath9k-htc-blobless-firmware-1.4.0`

## 🔗 Dependencies

- [[1n9wsbmgwq3cddk4wh5ma6kgwmw0cpq8-gcc-4.7.4.tar.bz2]]
- [[34z5nzjijzv6by2ki5wmy0zdzz0hnnzr-mpfr-3.1.1.tar.bz2]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bm15ffij7jzf7w5y0yjldla7nsjnx2ag-source]]
- [[hy4n60psgpmv2mf0k3lw277938x6c7ak-binutils-2.23.1.tar.bz2]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[ql73vn5vlm0f8wh1jginxvmg6ig0960v-gmp-5.0.5.tar.bz2]]
- [[sp2vq01660i7gmsgddk4x9di14gwny4m-gnum4-1.4.20]]
- [[zf97i8k7sx9wzmbvx63z9r9mm3pb6s8n-mpc-1.0.1.tar.gz]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:41:28 UTC*
