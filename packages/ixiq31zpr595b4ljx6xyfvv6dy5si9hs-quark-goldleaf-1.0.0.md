---
aliases:
  - quark-goldleaf
tags:
  - license/unknown
  - maintainers/TomaSajt
  - outputs/out
---

# quark-goldleaf

## 📝 Description

GUI tool for transfering files between a computer and a Nintendo Switch running Goldleaf

For the program to work properly, you will have to install Nintendo Switch udev rules.

You can either do this by enabling the NixOS module:

`programs.quark-goldleaf.enable = true;`

or by adding the package manually to udev packages:

`services.udev.packages = [ pkgs.quark-goldleaf ];


## 📋 Package Information

- **Name**: `quark-goldleaf`
- **Version**: `1.0.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GUI tool for transfering files between a computer and a Nintendo Switch running Goldleaf
- **Homepage**: [https://github.com/XorTroll/Goldleaf#quark-and-remote-browsing](https://github.com/XorTroll/Goldleaf#quark-and-remote-browsing)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`
## 👥 Maintainers

- @TomaSajt


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ixiq31zpr595b4ljx6xyfvv6dy5si9hs-quark-goldleaf-1.0.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/qu/quark-goldleaf/package.nix:105`
- **Outputs**:
  - `out`:  `/nix/store/ixiq31zpr595b4ljx6xyfvv6dy5si9hs-quark-goldleaf-1.0.0`

## 🔗 Dependencies

- [[02nvbmkaqzxp5jbnl7i1rcsj85r5cl5p-udev-check-hook]]
- [[474kivdzi525za8vzpgr0ils1k0qf8r3-wrap-gapps-hook]]
- [[4dq8np7c2mimniwl3if93g7ncz1cjr4r-gtk+3-3.24.49]]
- [[4lg80mawayzfa44lva39ifv60v1qy706-source]]
- [[b1wxzcys65cdsbawal82028jyvj4y972-openjdk-21.0.8+9]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dp8pr8wifc68161p3g1kg7j6nnj5yrrm-maven-3.9.11]]
- [[fq23lcwc1p6ww77gxriaa7n57wva6mag-copy-desktop-items-hook]]
- [[gq1x7r7fl6r3w50rrwba6y26xg1nqw70-imagemagick-7.1.2-3]]
- [[ihx3drmjxyjx1nqzj50a8sdpd6izx1v9-fix-config-path.patch]]
- [[jgdhwgh1kj32l7j5lapfj1bys9kx91lz-quark-goldleaf.desktop]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[wjmh8wc4plph7mfvrf7v4mlllprgamc2-quark-goldleaf-1.0.0-maven-deps]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/v6nxslbdk7cnjb40hp41z7jq48zjywxg-99-quark-goldleaf.rules`
- `/nix/store/zhwhvsw5i3nwqix7y44w4iav5lw9bgbm-fix-maven-plugin-versions.patch`
- `/nix/store/zmkzldwivs5x2rgg1k0i26f0lg9rd6d4-remove-pom-jfx.patch`

---
*Generated on 2025-09-27 12:53:07 UTC*
