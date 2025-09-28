---
aliases:
  - gnomeExtensions.gnome-bedtime
tags:
  - license/unknown
  - maintainers/honnip
  - outputs/out
---

# gnomeExtensions.gnome-bedtime

## 📝 Description

Hey Gnome, it's bedtime! Converts to grayscale the entire Gnome workspace by using a smooth transition. Best to use during evening/night.

This behavior is similar to Android's bedtime mode which converts the phone screen to grayscale. It should somewhat make your device less appealing and limit the usage of it before bedtime. On my side, at least, it still requires a fair amount of self control in order to make that happen.

The extension has a nice Settings UI where you can customize it to your liking:
- Set an automatic schedule for turning on/off the Bedtime Mode
- Add an On Demand button to Top Bar or a Quick Settings toggle to manually enable/disable the mode
- Control the On Demand button visibility, appearance and position in Top Bar
- Choose another color preset and intensity, if you prefer a different color scheme
- Change color intensity on the fly by scrolling over the On Demand button in Top Bar

Multi language support is also available, please check the GitHub page if you want to help with the translations. So far, the extension is fully translated to French, Italian, Spanish, Dutch, German, Czech, Persian, Romanian and English.

If you want to use a keyboard shortcut in order to toggle the Bedtime Mode then you can use this command for the shortcut:

bash -c 'schema_id=org.gnome.shell.extensions.bedtime-mode; schema_dir=~/.local/share/gnome-shell/extensions/gnomebedtime@ionutbortis.gmail.com/schemas/; if [[ $(gsettings --schemadir $schema_dir get $schema_id bedtime-mode-active) == true ]]; then turn_on=false; else turn_on=true; fi; gsettings --schemadir $schema_dir set $schema_id bedtime-mode-active $turn_on;'


## 📋 Package Information

- **Name**: `gnomeExtensions.gnome-bedtime`
- **Version**: `22`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Hey Gnome, it's bedtime! Converts to grayscale the entire Gnome workspace by using a smooth transition. Best to use during evening/night.
- **Homepage**: [https://extensions.gnome.org/extension/4012/gnome-bedtime/](https://extensions.gnome.org/extension/4012/gnome-bedtime/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @honnip


## 🔧 Build Information

- **Derivation Path**: `/nix/store/8xfpph4b9jhiwa0phj3a22q9mnykm71p-gnome-shell-extension-gnome-bedtime-22.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/desktops/gnome/extensions/buildGnomeExtension.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/8xfpph4b9jhiwa0phj3a22q9mnykm71p-gnome-shell-extension-gnome-bedtime-22`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[h50k0rcb0dhqkzx8wxb74mzd385fnl4q-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:15:38 UTC*
