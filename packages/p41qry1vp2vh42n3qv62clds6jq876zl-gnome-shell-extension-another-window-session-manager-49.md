---
aliases:
  - gnomeExtensions.another-window-session-manager
tags:
  - license/unknown
  - maintainers/honnip
  - outputs/out
---

# gnomeExtensions.another-window-session-manager

## 📝 Description

Close open windows gracefully and save them as a session. And you can restore them when necessary manually or automatically at startup. Most importantly, it supports both X11 and Wayland!

Main features:
- Restore the previous session at startup. disabled by default.
- Save running apps and windows automatically when necessary, this will be used to restore the previous session at startup.
- Close running apps and windows automatically before Log Out, Restart, Power Off. disabled by default.
- Close running windows gracefully
- Close apps with multiple windows gracefully via ydotool so you don't lose sessions of this app (See also: How to make Close by rules work)
- Save running apps and windows manually
- Restore a selected session at startup (See also: #9). disabled by default.
- Restore a saved session manually
- Restore window state, including Always on Top, Always on Visible Workspace and maximization
- Restore window workspace, size and position
- Restore 2 column window tiling
- Stash all supported window states so that those states will be restored after gnome shell restarts via Alt+F2 -> r or killall -3 gnome-shell.
- Move windows to their own workspace according to a saved session
- Support multi-monitor
- Remove saved session to trash
- Search saved session by the session name fuzzily

For more information, please visit https://github.com/nlpsuge/gnome-shell-extension-another-window-session-manager/blob/feature-close-save-session-while-logout/README.md.

Please report issues on Github.

## 📋 Package Information

- **Name**: `gnomeExtensions.another-window-session-manager`
- **Version**: `49`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Close open windows gracefully and save them as a session. And you can restore them when necessary manually or automatically at startup. Most importantly, it supports both X11 and Wayland!
- **Homepage**: [https://extensions.gnome.org/extension/4709/another-window-session-manager/](https://extensions.gnome.org/extension/4709/another-window-session-manager/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @honnip


## 🔧 Build Information

- **Derivation Path**: `/nix/store/p41qry1vp2vh42n3qv62clds6jq876zl-gnome-shell-extension-another-window-session-manager-49.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/desktops/gnome/extensions/buildGnomeExtension.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/p41qry1vp2vh42n3qv62clds6jq876zl-gnome-shell-extension-another-window-session-manager-49`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bnibwm3zslm7y7wi5a19z29nzjnm1qyp-source]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:11:56 UTC*
