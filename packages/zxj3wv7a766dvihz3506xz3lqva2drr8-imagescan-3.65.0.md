---
aliases:
  - utsushi
tags:
  - license/unknown
  - maintainers/wucke13
  - maintainers/mwilsoncoding
  - outputs/out
---

# utsushi

## 📝 Description

ImageScanV3 (aka utsushi) scanner driver. Non-free plugins are not
included, so no network support. To use the SANE backend, in
<literal>/etc/nixos/configuration.nix</literal>:

<literal>
hardware.sane = {
  enable = true;
  extraBackends = [ pkgs.utsushi ];
};
services.udev.packages = [ pkgs.utsushi ];
</literal>

Supported hardware:
DS-1610, DS-1630, DS-1660W, DS-310, DS-320, DS-360W, DS-40, DS-410,
DS-50000, DS-510, DS-520, DS-530, DS-535, DS-535H, DS-5500, DS-560,
DS-570W, DS-575W, DS-60000, DS-6500, DS-70, DS-70000, DS-7500, DS-760,
DS-770, DS-775, DS-780N, DS-80W, DS-860, EC-4020 Series, EC-4030 Series,
EC-4040 Series, EP-10VA Series, EP-30VA Series, EP-708A Series, EP-709A
Series, EP-710A Series, EP-711A Series, EP-712A Series, EP-808A Series,
EP-810A Series, EP-811A Series, EP-812A Series, EP-879A Series, EP-880A
Series, EP-881A Series, EP-882A Series, EP-978A3 Series, EP-979A3 Series,
EP-982A3 Series, EP-M570T Series, ES-200, ES-300W, ES-300WR, ES-400,
ES-50, ES-50, ES-500W, ES-500WR, ES-55R, ES-60W, ES-60WB, ES-60WW,
ES-65WR, ET-16500 Series, ET-2500 Series, ET-2550 Series, ET-2600 Series,
ET-2610 Series, ET-2650 Series, ET-2700 Series, ET-2710 Series, ET-2720
Series, ET-2750 Series, ET-2760 Series, ET-3600 Series, ET-3700 Series,
ET-3710 Series, ET-3750 Series, ET-3760 Series, ET-4500 Series, ET-4550
Series, ET-4700 Series, ET-4750 Series, ET-4760 Series, ET-7700 Series,
ET-7750 Series, ET-8700 Series, ET-M2140 Series, ET-M2170 Series,
ET-M3140 Series, ET-M3170 Series, ET-M3180 Series, EW-052A Series,
EW-452A Series, EW-M5071FT Series, EW-M571T Series, EW-M630T Series,
EW-M660FT Series, EW-M670FT Series, EW-M770T Series, EW-M970A3T Series,
FF-640, FF-680W, GT-S650, L1455 Series, L220 Series, L222 Series, L3050
Series, L3060 Series, L3070 Series, L3100 Series, L3110 Series, L3150
Series, L3160 Series, L360 Series, L362 Series, L364 Series, L365 Series,
L366 Series, L375 Series, L380 Series, L382 Series, L385 Series, L386
Series, L395 Series, L396 Series, L405 Series, L4150 Series, L4160
Series, L455 Series, L475 Series, L485 Series, L486 Series, L495 Series,
L5190 Series, L565 Series, L566 Series, L575 Series, L605 Series, L6160
Series, L6170 Series, L6190 Series, L655 Series, L7160 Series, L7180
Series, LX-10000F, LX-10000FK, LX-10010MF, LX-7000F, M2140 Series, M2170
Series, M3140 Series, M3170 Series, M3180 Series, PX-048A Series, PX-049A
Series, PX-M160T Series, PX-M270FT Series, PX-M270T Series, PX-M380F,
PX-M381FL, PX-M5080F Series, PX-M5081F Series, PX-M680F Series, PX-M7050
Series, PX-M7050FP, PX-M7050FX, PX-M7070FX, PX-M7110F, PX-M7110FP,
PX-M780F Series, PX-M781F Series, PX-M840FX, PX-M860F, PX-M880FX,
PX-M884F, PX-M885F, PX-M886FL, Perfection V19, Perfection V39, ST-2000
Series, ST-3000 Series, ST-4000 Series, ST-M3000 Series, WF-2750 Series,
WF-2760 Series, WF-2810 Series, WF-2830 Series, WF-2850 Series, WF-2860
Series, WF-3720 Series, WF-3730 Series, WF-4720 Series, WF-4730 Series,
WF-4740 Series, WF-6530 Series, WF-6590 Series, WF-7710 Series, WF-7720
Series, WF-8510 Series, WF-8590 Series, WF-C17590 Series, WF-C20590
Series, WF-C5710 Series, WF-C5790 Series, WF-C5790BA, WF-C579R Series,
WF-C579RB, WF-C8610 Series, WF-C8690 Series, WF-C8690B, WF-C869R Series,
WF-M20590 Series, WF-M5799 Series, WF-R8590 Series, XP-2100 Series,
XP-220 Series, XP-230 Series, XP-235 Series, XP-240 Series, XP-243 245
247 Series, XP-255 257 Series, XP-3100 Series, XP-332 335 Series, XP-340
Series, XP-342 343 345 Series, XP-352 355 Series, XP-4100 Series, XP-430
Series, XP-432 435 Series, XP-440 Series, XP-442 445 Series, XP-452 455
Series, XP-5100 Series, XP-530 Series, XP-540 Series, XP-6000 Series,
XP-6100 Series, XP-630 Series, XP-640 Series, XP-7100 Series, XP-830
Series, XP-8500 Series, XP-8600 Series, XP-900 Series, XP-960 Series,
XP-970 Series


## 📋 Package Information

- **Name**: `utsushi`
- **Version**: `3.65.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: SANE utsushi backend for some Epson scanners
- **Homepage**: [https://gitlab.com/utsushi/imagescan](https://gitlab.com/utsushi/imagescan)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @wucke13
- @mwilsoncoding


## 🔧 Build Information

- **Derivation Path**: `/nix/store/zxj3wv7a766dvihz3506xz3lqva2drr8-imagescan-3.65.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ut/utsushi/package.nix:122`
- **Outputs**:
  - `out`:  `/nix/store/zxj3wv7a766dvihz3506xz3lqva2drr8-imagescan-3.65.0`

## 🔗 Dependencies

- [[1fzxi5zfzvgbj9j19wl9ihk41nhmjyw3-autoconf-archive-2024.10.16]]
- [[2nqngnhl2pn7lq0b893p2wv2hwsq5b6n-iscan-3.65.0-sane-backends-1.1.patch?id=dec60bb6900d6ebdaaa6aa1dcb845b30b739f9b5]]
- [[3gh0snr9wn0i6gzya2g42hmm0cc2lwg3-sane-backends-1.4.0]]
- [[3zc6j1j1qgis43ig9m9gl11iqf058s76-systemd-minimal-libs-257.8]]
- [[9q4y5bicp78pyz6gyjk4a84xj9pmvdc9-gtkmm-2.24.5]]
- [[abssh28d2wb065pd73p1xfz53j338ac2-iscan-3.63.0-autoconf-2.70.patch?id=4fe8a9e6c60f9163cadad830ba4935c069c67b10]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[fy9wjrqf0pzd5x3rvy665v50ff747wfd-libusb-1.0.29]]
- [[gq1x7r7fl6r3w50rrwba6y26xg1nqw70-imagemagick-7.1.2-3]]
- [[i3ph2z8ayfgsqlrj9y2gwiyv3fmj6w10-boost-1.87.0]]
- [[i6k0i6qb8aa799rcjk46zcl7q6zjypbn-iscan-3.61.0-imagemagick-7.patch?id=985c92af4730d864e86fa87746185b0246e9db93]]
- [[ijwn7jm2vc6vqsyj3rziflzh79lmsdlx-source]]
- [[jqv6yrb9lcalxsh8n9dg2072ymjzqyvl-boost-1.74.patch]]
- [[k2lm2qkl0haj7vph5sa2r97my0ah0q1b-libxslt-1.1.43]]
- [[lf2b9rp3s5fd2rby5hvk0imkh0drzr24-git]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[n0grjv721n0b1yjk4kw2saqy323k407i-tesseract-4.1.3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:18:30 UTC*
