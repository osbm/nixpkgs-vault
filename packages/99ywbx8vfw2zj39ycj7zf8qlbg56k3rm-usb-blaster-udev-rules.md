---
aliases:
  - usb-blaster-udev-rules
tags:
  - license/unknown
  - outputs/out
---

# usb-blaster-udev-rules

## 📝 Description

udev rules that give NixOS permission to communicate with usb blasters.
To use it under NixOS, add

  services.udev.packages = [ pkgs.usb-blaster-udev-rules ];

to the system configuration.


## 📋 Package Information

- **Name**: `usb-blaster-udev-rules`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: udev rules that give NixOS permission to communicate with usb blasters
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/99ywbx8vfw2zj39ycj7zf8qlbg56k3rm-usb-blaster-udev-rules.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/us/usb-blaster-udev-rules/package.nix:24`
- **Outputs**:
  - `out`:  `/nix/store/99ywbx8vfw2zj39ycj7zf8qlbg56k3rm-usb-blaster-udev-rules`

## 🔗 Dependencies

- [[02nvbmkaqzxp5jbnl7i1rcsj85r5cl5p-udev-check-hook]]
- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]

## 📁 Input Sources

- `/nix/store/4n040kw1vsdfn8l93ml1m1ym65h47mcs-usb-blaster.rules`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:17:46 UTC*
