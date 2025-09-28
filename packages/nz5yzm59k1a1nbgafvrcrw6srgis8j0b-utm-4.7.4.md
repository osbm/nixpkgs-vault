---
aliases:
  - utm
tags:
  - not-available
  - license/unknown
  - maintainers/rrbutani
  - maintainers/wegank
  - outputs/out
---

# utm

## 📝 Description

UTM is a full featured system emulator and virtual machine host for iOS
and macOS. It is based off of QEMU. In short, it allows you to run
Windows, Linux, and more on your Mac, iPhone, and iPad.

Features:
  - Full system emulation (MMU, devices, etc) using QEMU
  - 30+ processors supported including x86_64, ARM64, and RISC-V
  - VGA graphics mode using SPICE and QXL
  - Text terminal mode
  - USB devices
  - JIT based acceleration using QEMU TCG
  - Frontend designed from scratch for macOS 11 and iOS 11+ using the
    latest and greatest APIs
  - Create, manage, run VMs directly from your device
  - Hardware accelerated virtualization using Hypervisor.framework and
    QEMU
  - Boot macOS guests with Virtualization.framework on macOS 12+

See https://docs.getutm.app/ for more information.


## 📋 Package Information

- **Name**: `utm`
- **Version**: `4.7.4`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Full featured system emulator and virtual machine host for iOS and macOS
- **Homepage**: [https://mac.getutm.app/](https://mac.getutm.app/)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`
## 👥 Maintainers

- @rrbutani
- @wegank


## 🔧 Build Information

- **Derivation Path**: `/nix/store/nz5yzm59k1a1nbgafvrcrw6srgis8j0b-utm-4.7.4.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ut/utm/package.nix:41`
- **Outputs**:
  - `out`:  `/nix/store/nz5yzm59k1a1nbgafvrcrw6srgis8j0b-utm-4.7.4`

## 🔗 Dependencies

- [[19ix53n9lkdnpk922fl6y032fr81c9w2-undmg-1.1.0-unstable-2024-08-02]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[qicwxz2ihv926ja7gkb0kjjgldkimrdi-UTM.dmg]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:18:26 UTC*
