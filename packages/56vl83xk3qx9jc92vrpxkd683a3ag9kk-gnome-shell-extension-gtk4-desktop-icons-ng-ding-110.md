---
aliases:
  - gnomeExtensions.gtk4-desktop-icons-ng-ding
tags:
  - license/unknown
  - maintainers/honnip
  - outputs/out
---

# gnomeExtensions.gtk4-desktop-icons-ng-ding

## 📝 Description

Adw. Desktop Icons

Libadwaita/Gtk4 port of Desktop Icons NG with multiple fixes and new features.

Icons can be positioned anywhere on desktop or are snapped to a grid. Can make links on the Desktop. GSconnect Integration, can send files to connected devices. Drag and Drop support on to Dock, Dash, or from Dock, Dash to the Desktop.

Updated and modified code base, uses Gio menus, all translations on Weblate. All functions are asynchronous where possible. It is ported to ESM modules, supports Gnome 45 and higher.

Multiple fixes and new features-
* Removed dependency on xdg-user-dirs
* Change name to Adw. Desktop Icons, version 100 :)
* Feature complete shortcut manager with editable keybindings for app actions.
* New About dialog and redesigned preferences. Proper credits and acknowledgements
* Right click menu now displays and activates actions for .desktop files.
* Added global hotkey accelerator to display or hide desktop icons.
* New ShortCutsManager that displays Adw.Window and widgets for shortcuts.
* Complete rewrite of the app, major clean up and restructuring.
* Add a .desktop icon with actions for app, can be displayed in dock for windows, launcher, menus etc with right click actions, including hiding all windows
* Show a shortcuts window for the application to list all available shortcuts.
* Improve multi-monitor support, saves monitor positon with icon position, allow to change fractional scaling in app if a second monitor connected at different zoom level.
* Fix dd-term focus loss isssue.
* App rewritten as Adw.Application GObject subclass, better css handling, use Adw.Stylemanager, better icons and emblems for stackTop items.
* Integrate ptyxis, replaces gnome-terminal on some distributions. Open ptyxis properly.
* Modern emblems like Gnome Files, allow multiple emblems
* Emblem for encrypted pdf, zip, 7z files
* Allow setting any user folder as the Desktop folder following xdg-sepecifications and updating the xdg-files and vice versa in the running program.
* Proper app icon, image and app name in Notifications.
* Proper integration for AppImage files, treat them like .desktop files. Integration with AppImageLauncher. Prefer that to open AppImage files if available.
* For Gnome 47, change highlighting and rubber band selection colors with accent-colors in Gnome Settings.
* Selection rectangle with rounded corners, similar to Gnome Files aesthetic.
* The stock gnome shell background menu can now be shown from the Gtk4 DING desktop right click menu. All shell settings can be accessed from that menu.
* Icons can be placed on any arbitrary position. Make a mess! - icons can overlap each other etc. Neat people can keep the default behavior and have the icons always snapped to a grid. Controlled in preferences, tweaks, 'Snap to grid'. Affects the shape of icons and drag and drop behavior as well. Free positioning has trapezoidal icons, drop only works with direct overlap. Grid positioning has rectangular icons, and drag and drop works on overlap with the grid holding the icon. This behavior is consistent with other desktop environments.
* Icons on background on overview, improved gesture switching icons appear to be on all work spaces on the background with workspace switching, with no flashing.
* Support for dragging icons onto the dock - Drag icons from desktop to and drop over application icon to open them with the app. Works with Dash to Dock and Dash to Panel.
* Support for dragging icons from desktop directly to Trash on Dash to Dock, or to mounted volumes on the dock, to copy them directly.
* Set the correct cursor with proposed action on drop on dock.
* Drag Navigation on Dock - dragging an icon over the Gnome Files icon on the dock or mounted drives, and hovering over it for 1/2 seconds will open a Gnome Files Window. Behavior can be changed in preferences.
* Drag Navigation - dragging an icon over a folder icon or a drive icon, and then hovering over it for one and half seconds will open that location in Gnome Files.
* Sets correct hovering behavior during drag and drop on the Dock, enables scrolling in the dock to icons when they are hidden.
* Drag and drop Favorite apps from Dash to Dock, Dash to Panel directly to Desktop. Pressing shift, ctr or alt while doing this will copy or move the app to Desktop, allowing launching from the desktop. Just dropping an app from the dock to the desktop will remove from Dash/Dock.
* Follows xdg-terminal-exec to display the correct terminal in right click menus, and will launch the correct terminal, even if xdg-terminal-exec is not installed.
* Shows the correct file manager in the right click menu and give the user the option to change the file manager.
* Gio menus, menus display all keyboard shortcuts.
* Uses Gtk4 AlertDialog, uses asynchronous promises for dialog's, shows button to launch URL for help and troubleshooting information.
* Automatically zip Folders if mailing them.
* Tool tips are now positioned correctly to not go under the dash or make it auto hide, or go over/under any gnome shell actors on the edge of the screen.
* Right Click Menus will not go under the dock.
* Make Links on Desktop with Alt button on Wayland. Shift, Ctr or Alt button control the effect, move, copy, drop or link. (Linking may not work on X11)
* Copied/dropped/pasted files retain dropped position. Undo action after trashing or moving files puts icons back in the old position.
* Better multi monitor support, preference to place icons on non primary monitor.
* GSconnect extension integration, can send files from desktop directly to connected mobile device.
* Accessibility support with screen readers
* Deals correctly with appimage files on desktop.
* Display GIMP thumbnails, even for snap and flatpack installs.

Please see Readme for full details of new features. Works best on Wayland. However your mileage may vary on X11. Multiple bugs fixed on X11.

Please report all issues on the Gitlab link below, this page is not monitored. All known issues as well as all the features are detailed there.

## 📋 Package Information

- **Name**: `gnomeExtensions.gtk4-desktop-icons-ng-ding`
- **Version**: `110`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Adw. Desktop Icons
- **Homepage**: [https://extensions.gnome.org/extension/5263/gtk4-desktop-icons-ng-ding/](https://extensions.gnome.org/extension/5263/gtk4-desktop-icons-ng-ding/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @honnip


## 🔧 Build Information

- **Derivation Path**: `/nix/store/56vl83xk3qx9jc92vrpxkd683a3ag9kk-gnome-shell-extension-gtk4-desktop-icons-ng-ding-110.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/desktops/gnome/extensions/buildGnomeExtension.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/56vl83xk3qx9jc92vrpxkd683a3ag9kk-gnome-shell-extension-gtk4-desktop-icons-ng-ding-110`

## 🔗 Dependencies

- [[0s59zsd94aw3kbd8qmikz2qzy91cjkqa-gtk4-ding_at_smedius.gitlab.com.patch]]
- [[474kivdzi525za8vzpgr0ils1k0qf8r3-wrap-gapps-hook]]
- [[80k29kqj9icg9xbdykcc18044h8m8f17-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:15:56 UTC*
