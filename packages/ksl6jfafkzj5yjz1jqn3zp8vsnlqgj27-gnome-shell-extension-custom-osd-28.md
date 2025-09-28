---
aliases:
  - gnomeExtensions.custom-osd
tags:
  - license/unknown
  - maintainers/honnip
  - outputs/out
---

# gnomeExtensions.custom-osd

## 📝 Description

Fully customize your OSD ( On Screen Display ) pop ups like Volume , Brightness or Caffeine , Lock Keys etc. 

UPDATE (v25, v26):
- Profiles: New default profiles added for new users to get started
- Vertical Position: Please note vertical position convention is changed: +50 is Top and -50 is Bottom of screen
- Size also changed a bit so you may need to resize existing OSDs in settings
- Square/Circle toggle option allows to get squarish/circlish shapes (as you vary Shape Shift)
- New Special Effects: Progress Ring and Background Image (see below)
- Gradient: New radial gradient direction and option to set end color opacity
- Level: New level color, opacity and thickness options
- Border: New border color, opacity and thickness options
- Padding: New horizontal and vertical padding options
- Shadow: New shadow color option
- Font: Improved implementation of font attributes (font style, stretch, weight)
- Trigger custom OSDs from command line (e.g. from a script) (see ReadMe on Github: https://github.com/neuromorph/custom-osd?tab=readme-ov-file#trigger-custom-osds-from-command-line)

Progress Ring / Disk:
- Select Sepcial Effect 'Progress Ring' in settings
- Set 'Ring Gap from Border' and 'Level Thickness' to get a Progress Ring or Progress Disk
- For Disk, set Gap to 100 and adjust Level. For Ring reduce Gap to 40-50 and adjust Level.
- Combine with color / opacity styles for fg, bg, level and border

Background Image:
- Set any image as OSD background (smaller size preferred)
- Select Special Effect 'Background Image'
- In 'Background Image FIle', provide path to a local file e.g. Pictures/myOsdImage.png

Features:
- Customize OSD position, orientation, size, numeric %,  monitor to show on, hide-delay and style 
- Select any combination of components to display: icon, text-label, level-bar, numeric %.
- OSD components can be turned On/Off based on OSD types.
- Special effects like Progress Ring, Gradient, Blur, Background Image etc
- Clock OSD to show current date/time on a hotkey (default none. set hotkey in settings).
- Create and Save multiple Settings profiles and choose one to apply (Profiles page in settings).
- Import / Export settings profiles.
- Share / get profile presets in github.


Translations : Spanish, Indonesian and French (thanks to contributors)


## 📋 Package Information

- **Name**: `gnomeExtensions.custom-osd`
- **Version**: `28`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Fully customize your OSD ( On Screen Display ) pop ups like Volume , Brightness or Caffeine , Lock Keys etc. 
- **Homepage**: [https://extensions.gnome.org/extension/6142/custom-osd/](https://extensions.gnome.org/extension/6142/custom-osd/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @honnip


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ksl6jfafkzj5yjz1jqn3zp8vsnlqgj27-gnome-shell-extension-custom-osd-28.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/desktops/gnome/extensions/buildGnomeExtension.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/ksl6jfafkzj5yjz1jqn3zp8vsnlqgj27-gnome-shell-extension-custom-osd-28`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[zhz28fakbl9kc2pm5jjk7i1wkvd66dg0-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:13:39 UTC*
