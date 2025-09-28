---
aliases:
  - miriway
tags:
  - license/unknown
  - maintainers/OPNA2608
  - outputs/out
---

# miriway

## 📝 Description

Miriway is a starting point for creating a Wayland based desktop environment using Mir.

At the core of Miriway is miriway-shell, a Mir based Wayland compositor that provides:

- A "floating windows" window managament policy;
- Support for Wayland (and via Xwayland) X11 applications;
- Dynamic workspaces;
- Additional Wayland support for "shell components" such as panels and docs; and,
- Configurable shortcuts for launching standard apps such as launcher and terminal emulator.

In addition to miriway-shell, Miriway has:

- A "terminal emulator finder" script miriway-terminal, that works with most terminal emulators;
- A launch script miriway to simplify starting Miriway;
- A default configuration file miriway-shell.config; and,
- A greeter configuration miriway.desktop so Miriway can be selected at login

Miriway has been tested with shell components from several desktop environments and there are notes on
enabling these in miriway-shell.config.


## 📋 Package Information

- **Name**: `miriway`
- **Version**: `25.10`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Mir based Wayland compositor
- **Homepage**: [https://github.com/Miriway/Miriway](https://github.com/Miriway/Miriway)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @OPNA2608


## 🔧 Build Information

- **Derivation Path**: `/nix/store/glmmqkgqaz07hfv3y5hl34nnih2103h0-miriway-25.10.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/mi/miriway/package.nix:69`
- **Outputs**:
  - `out`:  `/nix/store/glmmqkgqaz07hfv3y5hl34nnih2103h0-miriway-25.10`

## 🔗 Dependencies

- [[02l2mwk9x35ww8hq6m836yrcy0ma7js8-wayland-1.24.0]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[by779xx7waywsnj4bn9vnwyg6a2b59mj-inotify-tools-4.23.9.0]]
- [[i3ph2z8ayfgsqlrj9y2gwiyv3fmj6w10-boost-1.87.0]]
- [[k81w6jk1nwdf49yjkq02c6d5d8k7f2h1-mir-2.22.1]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qsidpixs89pihd5qjm02q93yilshiz96-libxkbcommon-1.11.0]]
- [[rw75gm65xmx0pg15a1ay5ilvawpdbi57-swaybg-1.2.1]]
- [[v28sdl3535sxb6a71z5faqdzbns9pv0h-bash-interactive-5.3p3]]
- [[xw3crpsxxbpd1jxhvjsvia8rn63z6rfy-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:19:57 UTC*
