---
aliases:
  - gnomeExtensions.open-bar
tags:
  - license/unknown
  - maintainers/honnip
  - outputs/out
---

# gnomeExtensions.open-bar

## 📝 Description

Theming Top Bar / Top Panel , Menus , Dash / Dock , Gnome Shell , Gtk Apps. 
Open the bar and let the colors 🍹 flow.

**Please report on GitHub if something is broken due to an update or if you have any suggestions. Also, refer to GitHub link below (homepage) for more screenshots.

•  Open Bar allows you to theme the Top Bar, Pop-up Menus, Dash, Dock and rest of the Gnome Shell.
•  You can also extend the theme to Gtk and Flatpak apps to the extent possible with CSS.
•  You can choose any color for Accent and for everything else in the shell.
•  There are a lot of settings to allow full customization and they are grouped as tabs in the left panel.
•  To make things easier, there is an auto-theme feature that picks colors from the desktop background.
•  You can start with selecting the Type of bar, then select the desired Auto-Theme and apply.
•  Floating or Island bars are great on the desktop but when a window is maximized, you must try Window-Max bar.
•  Next, you can apply styles to Dash/Dock, Shell and Apps as desired for full theming experience.
•  Lastly, feel free to play with the settings and things will start becoming much easier.


Compatibility with Extensions:
- It should be (mostly) compatible with custom user themes and other extensions that affect the Top Panel 
- Some extensions do not use standard widget and API (i.e. 'PanelMenu.Button' and 'main.addToStatusArea') when adding indicator to Panel and fixing that makes them work correctly with Open Bar (or with user themes for that matter). Refer issue #24 on GitHub for some fixes.


Auto Theming:
- Note: If you want to save your current settings, please use Export Settings option before applying Auto-theme. You can import it back whenever needed.
- Auto-themes will use the color palette generated from the desktop background image.
- Other settings will be set as selected, by the user, in the preferences tabs.
- Styles will apply to the Top Bar, Menus and optionally to the shell.
        
        --- True Color     :  Palette colors as-is (biased towards dark). 
        --- Pastel Theme   :  Colors are pastelified (biased towards light).
        --- Dark Theme     :  Colors are darkened as needed.
        --- Light Theme    :  Colors are lightened as needed.

- You can select themes separately for both Gnome Dark and Light modes. 
- Once theme is applied, you can further tweak any of the manual settings to finetune the theme. 
- Color changes made in current mode will be saved for that mode alone. Other settings will apply to both modes.
- There is an option for Auto-refreshing theme when background changes. This will overwrite current theme colors with newly generated ones when background is changed.
- There are more settings in Auto-Theme. You can select if you want the secondary menu BG color to be derived from BG or auto-selected from palette. You can specify any preferred accent color or let the theme choose from the background. You can also select if foreground color should be auto-generated or use manual selection etc.
- Since it is one size fit all solution, 'No Free Lunch' theorem applies. Not all options will work best for all backgrounds, so the additional knobs above will help you select the desired one. One of the theme combinations should work well for you at least with little bit tweaking, if needed.
  

Customize:
- Bar Type: Fixed, Floating or Islands / Trilands
- Bar position, height, margin, paddings
- Bar foreground color, font
- Bar background color, transparency, gradient, shadow, highlights, candybar 
- Shape rectangular to pill, border width, color, neon glow
- Menu customizations: foreground, background colors, transparency, border, shadow,  accent/selection, hover colors
etc.
- Includes a custom color palette, under the default palette, in each color button popup. The palette is auto-generated from the desktop background.
- Add accent hint to GTK/Flatpak apps' Headerbar, Sidebar or Card/Dialogs. Add Traffic Light controls, window border, rounded window corners (or square),  popover styles etc.


SETTINGS NOTES:
If the panel/menu isn't looking right, you need to tweak some settings. There are a lot of knobs to allow for different setups/tastes. It can also make it a bit overwhelming if you are not familiar with css styles but with some experimentation it will become a lot easier. Here are brief notes:
- BG/FG color: Background or Foreground colors. Foreground is typically text and icons.
- Alpha: Transparency for the color. 0 is transparent while 1 is opaque.
- Panel BG will affect the bar while Tri/Islands BG will affect the individual indicator buttons/combos (in Trilands/Islands mode).
- Gradient goes from Start color to End color. If you want a single color fading, select same color for both with different Alphas. e.g. Setting end color alpha to 0 will form a gradient from Start color to transparent.
- Highlight color: It is the background color upon hover or focus. You can choose to highlight with border instead.
- Vertical padding: Controls size of highlights in Mainland/Floating. Also controls size of Islands/Trilands. Increase bar height if padding squeezes the text.
- Panel Shadow: a downward shadow for the panel bar. Shadow Spread controls both shadow transparency and spread together.
- Border: 
    = Width controls thickness (grows inwards for Islands). Adjust bar height accordingly, after setting border width.  
    = Radius will control the shape from rectangle at radius 0 to Pill at radius close to bar height. 
    = Neon glow: adds a neon-light like glow to the border. You need dark, relatively opaque background with bright/neon colored, relatively opaque border. Neon will override Panel shadow in Mainland and Floating mode.
 - Menus: 
    = FG/BG, border, highlight are similar to above but for menus.
    = Accent/active color is for menu items that are active e.g. Today's day in Calendar or WiFi in Quick Settings or even an active menu item with opened submenu. 
    = Shadow applies to the panel menu. Use white/bright color in dark theme and black/dark color in light theme for the effect to show and help with contrast. Using same color as menu border is also a good idea. Use the Alphas for both border and shadow to increase or reduce their effect.
- Lastly, be a tiny bit gentler with the sliders in the settings as they modify the stylesheet behind the scene for every update.

## 📋 Package Information

- **Name**: `gnomeExtensions.open-bar`
- **Version**: `43`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Theming Top Bar / Top Panel , Menus , Dash / Dock , Gnome Shell , Gtk Apps. 
- **Homepage**: [https://extensions.gnome.org/extension/6580/open-bar/](https://extensions.gnome.org/extension/6580/open-bar/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @honnip


## 🔧 Build Information

- **Derivation Path**: `/nix/store/rrq53l6z77jing5y5j3h2l64h1w9hvqg-gnome-shell-extension-open-bar-43.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/desktops/gnome/extensions/buildGnomeExtension.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/rrq53l6z77jing5y5j3h2l64h1w9hvqg-gnome-shell-extension-open-bar-43`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[yd627zdnml1a2hys3lb4msbg654r20sj-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:41:16 UTC*
