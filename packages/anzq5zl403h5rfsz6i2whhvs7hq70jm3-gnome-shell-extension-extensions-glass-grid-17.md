---
aliases:
  - gnomeExtensions.extensions-glass-grid
tags:
  - license/unknown
  - maintainers/honnip
  - outputs/out
---

# gnomeExtensions.extensions-glass-grid

## 📝 Description

A quick overlay glass panel showing a grid to view / manage installed extensions.
 
- The overlay can be quickly launched / dismissed using indicator toggle button in Panel or using a hotkey (default: &lt;Super&gt;E). Both can be set from the Settings menu in the overlay itself.
- The overlay will dismiss on Esc or automatically when it looses key focus. That is when you trigger open something e.g. extension preferences or when you click on some other app. [Note below].

Header / Top layout: 
    - Info button: It will open an about dialog also showing brief tool guide.
    - Settings button: Opens a menu with settings for background theme, font size, Indicator button Add/Remove, launch Hotkey.
    - Theme Mode: Toggle between Dark / Light and Neutral modes.
    - ego button: Opens extensions.gnome.org
    - Extension app button: Launches the Extensions app.
    - Switch: Enable / Disable all the extensions. It does not disable itself here for obvious reasons. Specifically disabling Glass Grid from it's own entry in the grid will disable/inactivate itself. 'Enabling all' will enable the extensions that were enabled before you pressed Disable All.

Grid Layout:
    - Extension Name button: By default, it will open the extension preferences. If the extension has an update, it will show update-message. If the extension has an error, it will show error-message.
    - Settings button: It will open the extension preferences. Gray button means the extension does not have preferences (so disabled).
    - Reload button: It will reload the extension stylesheet css file(s). This is useful when you are trying to customize an extension's style.
    - The grid layout scrolls horizontally when number of extensions are more than a page capacity. (Page Switcher popup animation included).
    - You can use keyboard arrow keys to navigate (supports automatic pagination when key-focus moves to another page). When opened, key focus would be on the title.

Note: This is since as a Gnome shell extension, the UI overlay is essentially transient like the panel menu. Glass grid is more persistent than the panel menu by design but less than an app window since it is not a desktop app. So think of it like the app grid in overview, to get some idea.


## 📋 Package Information

- **Name**: `gnomeExtensions.extensions-glass-grid`
- **Version**: `17`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: A quick overlay glass panel showing a grid to view / manage installed extensions.
- **Homepage**: [https://extensions.gnome.org/extension/6269/extensions-glass-grid/](https://extensions.gnome.org/extension/6269/extensions-glass-grid/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @honnip


## 🔧 Build Information

- **Derivation Path**: `/nix/store/anzq5zl403h5rfsz6i2whhvs7hq70jm3-gnome-shell-extension-extensions-glass-grid-17.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/desktops/gnome/extensions/buildGnomeExtension.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/anzq5zl403h5rfsz6i2whhvs7hq70jm3-gnome-shell-extension-extensions-glass-grid-17`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[smmy2np13784g8zx5pckq7wh2s0shajb-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:14:58 UTC*
