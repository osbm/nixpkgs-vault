---
aliases:
  - gnomeExtensions.todo
tags:
  - license/unknown
  - maintainers/honnip
  - outputs/out
---

# gnomeExtensions.todo

## 📝 Description

Lightweight and user-friendly extension designed to help you manage your tasks efficiently. With a minimalistic interface, it allows you to add, modify, and delete tasks effortlessly. No complicated settings, just pure productivity! 

For managing multiple To-Do lists :

The following syntax enables efficient navigation, creation, deletion, and renaming of your to-do lists:

    @2 – Navigates to the to-do list identified by its number, here list 2.
    @Groceries – Accesses the to-do list with the name 'Groceries'.

List Creation

    +::Work Projects – Creates a new to-do list with the name 'Work Projects'.

List Deletion

    -::@2 – Deletes the to-do list at number 2.
    -::@Chores – Removes the to-do list with the name 'Chores'.

Renaming Lists

    @2::Weekend Plans – Renames the to-do list at number 2 to 'Weekend Plans'.
    @Vacation::Trip Itinerary – Changes the name of the list 'Vacation' to 'Trip Itinerary'.

Help

    !l – Adds an item with all current lists and they number and state.

This syntax provides a streamlined way to manage your lists intuitively through direct special inputs.

NOTE (Gnome 47): second list's initial name can be changed with @2::New name, after that you can change it with @Word::@Word, i made a mistake and made the initial name contain a number which isn't matching with /^(@((?!\d)[\w\s]+))::((?!\d)[\w\s]+)$/

## 📋 Package Information

- **Name**: `gnomeExtensions.todo`
- **Version**: `5`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Lightweight and user-friendly extension designed to help you manage your tasks efficiently. With a minimalistic interface, it allows you to add, modify, and delete tasks effortlessly. No complicated settings, just pure productivity! 
- **Homepage**: [https://extensions.gnome.org/extension/7418/todo/](https://extensions.gnome.org/extension/7418/todo/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @honnip


## 🔧 Build Information

- **Derivation Path**: `/nix/store/vk2jk6ymw3m5jhzp9mbdlz1wv9jnfk47-gnome-shell-extension-todo-5.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/desktops/gnome/extensions/buildGnomeExtension.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/vk2jk6ymw3m5jhzp9mbdlz1wv9jnfk47-gnome-shell-extension-todo-5`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qmif7vpy25dbmc6zn9n70wpr8ywa07cg-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:44:50 UTC*
