---
aliases:
  - tmuxPlugins.resurrect
tags:
  - license/unknown
  - maintainers/RonanMacF
  - outputs/out
---

# tmuxPlugins.resurrect

## 📝 Description

This plugin goes to great lengths to save and restore all the details
from your tmux environment. Here's what's been taken care of:

* all sessions, windows, panes and their order
* current working directory for each pane
* exact pane layouts within windows (even when zoomed)
* active and alternative session
* active and alternative window for each session
* windows with focus
* active pane for each window
* "grouped sessions" (useful feature when using tmux with multiple monitors)
* programs running within a pane! More details in the restoring programs doc.

Optional:
* restoring vim and neovim sessions
* restoring pane contents


## 📋 Package Information

- **Name**: `tmuxPlugins.resurrect`
- **Version**: `2022-05-01`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Restore tmux environment after system restart
- **Homepage**: [https://github.com/tmux-plugins/tmux-resurrect](https://github.com/tmux-plugins/tmux-resurrect)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @RonanMacF


## 🔧 Build Information

- **Derivation Path**: `/nix/store/s49l7801klaphk3vzkvvbbs4saqjgy7v-tmuxplugin-resurrect-unstable-2022-05-01.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/misc/tmux-plugins/default.nix:684`
- **Outputs**:
  - `out`:  `/nix/store/s49l7801klaphk3vzkvvbbs4saqjgy7v-tmuxplugin-resurrect-unstable-2022-05-01`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[h65c3x3kwb0pc7h8cd0h1rfzvasbsy17-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:49:02 UTC*
