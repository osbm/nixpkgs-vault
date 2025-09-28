---
aliases:
  - fastfetchMinimal
tags:
  - license/unknown
  - maintainers/luftmensch-luftmensch
  - maintainers/khaneliman
  - maintainers/Defelo
  - outputs/man
  - outputs/out
---

# fastfetchMinimal

## 📝 Description

Fast and highly customizable system info script.

Feature flags (all default to 'true' except rpmSupport, flashfetchSupport and zfsSupport):
* audioSupport: PulseAudio functionality
* brightnessSupport: External display brightness detection via DDCUtil
* dbusSupport: DBus functionality for Bluetooth, WiFi, player & media detection
* flashfetchSupport: Build the flashfetch utility (default: false)
* gnomeSupport: GNOME integration (dconf, dbus, gio)
* imageSupport: Image rendering (chafa and imagemagick)
* openclSupport: OpenCL features
* openglSupport: OpenGL features
* rpmSupport: RPM package detection (default: false)
* sqliteSupport: Package counting via SQLite
* terminalSupport: Terminal font detection
* vulkanSupport: Vulkan GPU information and DRM features
* waylandSupport: Wayland display detection
* x11Support: X11 display information
* xfceSupport: XFCE integration for theme and terminal font detection
* zfsSupport: zpool information


## 📋 Package Information

- **Name**: `fastfetchMinimal`
- **Version**: `2.53.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Actively maintained, feature-rich and performance oriented, neofetch like system information tool
- **Homepage**: [https://github.com/fastfetch-cli/fastfetch](https://github.com/fastfetch-cli/fastfetch)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @luftmensch-luftmensch
- @khaneliman
- @Defelo


## 🔧 Build Information

- **Derivation Path**: `/nix/store/fwbkqy9n6nylz9y6fq8p1kncl86m3dy4-fastfetch-2.53.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/fa/fastfetch/package.nix:266`
- **Outputs**:
  - `man`:  `/nix/store/fwbkqy9n6nylz9y6fq8p1kncl86m3dy4-fastfetch-2.53.0`
  - `out`:  `/nix/store/fwbkqy9n6nylz9y6fq8p1kncl86m3dy4-fastfetch-2.53.0`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[lzvy25g887aypn07ah8igv72z7b9jb88-version-check-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pn03b9dijjmykv1k5sfjm4h990h4k25f-make-binary-wrapper-hook]]
- [[pp8mjbgppni1mx52ky990cm8qmi3jlrg-hwdata-0.398]]
- [[snbfinsd48w01hi51bzzpdl7m5n1cwif-libdrm-2.4.125]]
- [[w6559zhdi7wrj19fq9xby97q4cp9y80l-source]]
- [[zwz5kljnak55jw3ib23miwxpdgbarf4y-yyjson-0.12.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:58:56 UTC*
