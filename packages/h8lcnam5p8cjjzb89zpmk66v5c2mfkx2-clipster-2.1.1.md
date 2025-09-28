---
aliases:
  - clipster
tags:
  - license/unknown
  - maintainers/magnetophon
  - outputs/out
---

# clipster

## 📝 Description

Clipster was designed to try to add a good selection of useful features, while avoiding bad design decisions or becoming excessively large.
Its feature list includes:
- Event driven, rather than polling. More efficient, helps with power management.
- Control over when it write to disk, for similar reasons.
- Command-line options/config for everything.
- No global keybindings - that's the job of a Window Manager
- Sensible handling of unusual clipboard events. Some apps (Chrome, Emacs) trigger a clipboard 'update event' for every character you select, rather than just one event when you stop selecting.
- Preserves the last item in clipboard after an application closes. (Many apps clear the clipboard on exit).
- Minimal dependencies, no complicated build/install requirements.
- utf-8 support
- Proper handling of embedded newlines and control codes.
- Smart matching of urls, emails, regexes. (extract_*)
- Option to synchronise the SELECTION and CLIPBOARD clipboards. (sync_selections)
- Option to track one or both clipboards. (active_selections)
- Option to ignore clipboard updates form certain applications. (filter_classes)
- Ability to delete items in clipboard history.


## 📋 Package Information

- **Name**: `clipster`
- **Version**: `2.1.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Lightweight python clipboard manager
- **Homepage**: [https://github.com/mrichar1/clipster](https://github.com/mrichar1/clipster)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @magnetophon


## 🔧 Build Information

- **Derivation Path**: `/nix/store/h8lcnam5p8cjjzb89zpmk66v5c2mfkx2-clipster-2.1.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/cl/clipster/package.nix:40`
- **Outputs**:
  - `out`:  `/nix/store/h8lcnam5p8cjjzb89zpmk66v5c2mfkx2-clipster-2.1.1`

## 🔗 Dependencies

- [[474kivdzi525za8vzpgr0ils1k0qf8r3-wrap-gapps-hook]]
- [[4dq8np7c2mimniwl3if93g7ncz1cjr4r-gtk+3-3.24.49]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cj8bsii40qaiaibmmsai2d9y0gc8y9r4-libwnck-43.3]]
- [[jqqc83j9v460xa1qlp77ky52gbqg5af8-gobject-introspection-wrapped-1.84.0]]
- [[n393fvhifin38l15wxp9hqi9hbd248m0-python3-3.13.7-env]]
- [[nnfhzipnz3ij78piik46wkcc6d1m5hlb-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:49:32 UTC*
