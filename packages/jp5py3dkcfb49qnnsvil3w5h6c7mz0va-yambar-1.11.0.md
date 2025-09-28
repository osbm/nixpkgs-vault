---
aliases:
  - yambar
tags:
  - license/unknown
  - outputs/man
  - outputs/out
---

# yambar

## 📝 Description

yambar is a lightweight and configurable status panel (bar, for short) for
X11 and Wayland, that goes to great lengths to be both CPU and battery
efficient - polling is only done when absolutely necessary.

It has a number of modules that provide information in the form of tags.
For example, the clock module has a date tag that contains the current
date.

The modules do not know how to present the information though. This is
instead done by particles. And the user, you, decides which particles (and
thus how to present the data) to use.

Furthermore, each particle can have a decoration - a background color or a
graphical underline, for example.

There is no support for images or icons. use an icon font (e.g. Font
Awesome, or Material Icons) if you want a graphical representation.

There are a number of modules and particles builtin. More can be added as
plugins. You can even write your own!

To summarize: a bar displays information provided by modules, using
particles and decorations. How is configured by you.


## 📋 Package Information

- **Name**: `yambar`
- **Version**: `1.11.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Modular status panel for X11 and Wayland
- **Homepage**: [https://codeberg.org/dnkl/yambar](https://codeberg.org/dnkl/yambar)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/jp5py3dkcfb49qnnsvil3w5h6c7mz0va-yambar-1.11.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ya/yambar/package.nix:97`
- **Outputs**:
  - `man`:  `/nix/store/jp5py3dkcfb49qnnsvil3w5h6c7mz0va-yambar-1.11.0`
  - `out`:  `/nix/store/jp5py3dkcfb49qnnsvil3w5h6c7mz0va-yambar-1.11.0`

## 🔗 Dependencies

- [[02l2mwk9x35ww8hq6m836yrcy0ma7js8-wayland-1.24.0]]
- [[0y20y5glzrd67xskzh9vjindzjl1jiiv-bison-3.8.2]]
- [[3x5bmlv641xm5s1hk1nj4ffr0nk7vw2p-wayland-protocols-1.45]]
- [[3zc6j1j1qgis43ig9m9gl11iqf058s76-systemd-minimal-libs-257.8]]
- [[5jnsk32kmr80r0gygfzjlnm3sng90075-pipewire-1.4.7]]
- [[6ppggbmgb75hd0afplaig3p574gpb20j-fcft-3.3.2]]
- [[9jnak75f5yh6zx1221vglmw2dil6blql-libxcb-util-0.4.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[c1al2yzlwp5qpn63rmxfdgc8yph99501-libxcb-errors-1.0.1]]
- [[cc7q0gvagf507fmcgcrbi5nnlawch3zb-xcb-util-cursor-0.1.5]]
- [[dwvk5h1xqfs795djkl058mkv0ycc4b8p-libyaml-0.2.5]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[if30dvb18877vhsf1yhq7bzsgw20xlby-alsa-lib-1.2.14]]
- [[jck0dxj37g3s35g1b1rmfpk5xas10ydj-json-c-0.18]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[mh9qy59qmsbapyni7cf6zlsd7mn5kaqp-libxcb-wm-0.4.2]]
- [[myjswgr6vxfvq644ydvyhivypwxandp8-libmpdclient-2.24]]
- [[n4d8z8j2k033pp4wcah53ir38yjqq021-scdoc-1.11.3]]
- [[nimxv9jqla9w3ipfx3q544037a64g9hi-pixman-0.46.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rbjsvyngabldcxkvh1bqis3jaiy29x2j-wayland-scanner-1.24.0]]
- [[rqgfczspkldc6cgfqffc1pk54lvfk004-pulseaudio-17.0]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]
- [[wy61x67y125m36dp7l7xhzqbi30mxg1d-flex-2.6.4]]
- [[xjnir82a9r8njlnyag80ghykjshbidvb-source]]
- [[yskzdpnm13rk4dc3sk699hx05np0qxnr-tllist-1.1.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:10:09 UTC*
