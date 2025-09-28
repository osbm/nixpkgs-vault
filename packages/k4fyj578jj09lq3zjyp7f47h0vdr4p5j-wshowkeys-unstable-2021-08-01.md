---
aliases:
  - wshowkeys
tags:
  - license/unknown
  - maintainers/berbiche
  - outputs/out
---

# wshowkeys

## 📝 Description

Displays keypresses on screen on supported Wayland compositors (requires
wlr_layer_shell_v1 support).
Note: This tool requires root permissions to read input events, but these
permissions are dropped after startup. The NixOS module provides such a
setuid binary (use "programs.wshowkeys.enable = true;").


## 📋 Package Information

- **Name**: `wshowkeys`
- **Version**: `2021-08-01`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Displays keys being pressed on a Wayland session
- **Homepage**: [https://github.com/ammgws/wshowkeys](https://github.com/ammgws/wshowkeys)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @berbiche


## 🔧 Build Information

- **Derivation Path**: `/nix/store/k4fyj578jj09lq3zjyp7f47h0vdr4p5j-wshowkeys-unstable-2021-08-01.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ws/wshowkeys/package.nix:45`
- **Outputs**:
  - `out`:  `/nix/store/k4fyj578jj09lq3zjyp7f47h0vdr4p5j-wshowkeys-unstable-2021-08-01`

## 🔗 Dependencies

- [[02l2mwk9x35ww8hq6m836yrcy0ma7js8-wayland-1.24.0]]
- [[3x5bmlv641xm5s1hk1nj4ffr0nk7vw2p-wayland-protocols-1.45]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dkssw3csslvbv7cb9mrmfccns92l65c5-pango-1.56.3]]
- [[gzklha1gq3m3r8vr7qhfjnkxn2cs9f8c-source]]
- [[hrv8mr0dq75s9sci0zvkhnhiqxp5zikd-libinput-1.29.0]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qsidpixs89pihd5qjm02q93yilshiz96-libxkbcommon-1.11.0]]
- [[rbjsvyngabldcxkvh1bqis3jaiy29x2j-wayland-scanner-1.24.0]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]
- [[vww2w4bppjkr8spz5gcq5hkr98pf85zs-cairo-1.18.4]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:15:11 UTC*
