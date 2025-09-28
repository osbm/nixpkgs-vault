---
aliases:
  - kdiskmark
tags:
  - license/unknown
  - maintainers/symphorien
  - outputs/out
---

# kdiskmark

## 📝 Description

If kdiskmark is not run as root it can rely on polkit to get the necessary
privileges. In this case you must install it with `environment.systemPackages`
on NixOS, nix-env will not work.


## 📋 Package Information

- **Name**: `kdiskmark`
- **Version**: `3.2.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: HDD and SSD benchmark tool with a friendly graphical user interface
- **Homepage**: [https://github.com/JonMagon/KDiskMark](https://github.com/JonMagon/KDiskMark)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @symphorien


## 🔧 Build Information

- **Derivation Path**: `/nix/store/p8zgdin8dsrdlgc9dr74jp0gra4wmw9f-kdiskmark-3.2.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/tools/filesystems/kdiskmark/default.nix:50`
- **Outputs**:
  - `out`:  `/nix/store/p8zgdin8dsrdlgc9dr74jp0gra4wmw9f-kdiskmark-3.2.0`

## 🔗 Dependencies

- [[6rbcy8zva30xk4lm4skl5ykz51vnjqdd-qtbase-6.9.2]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[biy13jabj4ihdcs1igp8iarif4pmcdm5-fio-3.41]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[ibjx4fb6iqplf03nis4gnwq3yji7h5j7-wrap-qt6-apps-hook]]
- [[ihxnk07al2cgi94drf6zr1x45fnhyw9k-qttools-6.9.2]]
- [[ndqlra0viycwrvgyy0js7kznwlyag4b4-polkit-qt-1-0.200.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pvbpgigy2zkw0g86ha1qxfkfdr9pww9s-source]]
- [[vy23z2n1gxch827assiang0qjs1g8nz3-extra-cmake-modules-6.18.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:08:00 UTC*
