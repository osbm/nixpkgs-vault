---
aliases:
  - solaar
tags:
  - license/unknown
  - maintainers/spinus
  - maintainers/ysndr
  - maintainers/oxalica
  - outputs/dist
  - outputs/out
  - outputs/udev
---

# solaar

## 📝 Description

Solaar is a Linux manager for many Logitech keyboards, mice, and trackpads that
connect wirelessly to a USB Unifying, Lightspeed, or Nano receiver, connect
directly via a USB cable, or connect via Bluetooth. Solaar does not work with
peripherals from other companies.

Solaar can be used as a GUI application or via its command-line interface.

This tool requires either to be run with root/sudo or alternatively to have the udev rules files installed. On NixOS this can be achieved by setting `hardware.logitech.wireless.enable`.


## 📋 Package Information

- **Name**: `solaar`
- **Version**: `1.1.14`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Linux devices manager for the Logitech Unifying Receiver
- **Homepage**: [https://pwr-solaar.github.io/Solaar/](https://pwr-solaar.github.io/Solaar/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @spinus
- @ysndr
- @oxalica


## 🔧 Build Information

- **Derivation Path**: `/nix/store/vm4lzx7nj56ixzf62rad18fvqwxkyy1h-solaar-1.1.14.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/so/solaar/package.nix:85`
- **Outputs**:
  - `dist`:  `/nix/store/vm4lzx7nj56ixzf62rad18fvqwxkyy1h-solaar-1.1.14`
  - `out`:  `/nix/store/vm4lzx7nj56ixzf62rad18fvqwxkyy1h-solaar-1.1.14`
  - `udev`:  `/nix/store/vm4lzx7nj56ixzf62rad18fvqwxkyy1h-solaar-1.1.14`

## 🔗 Dependencies

- [[02nvbmkaqzxp5jbnl7i1rcsj85r5cl5p-udev-check-hook]]
- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[1cd88kz2fjbdyv8p03ffnyg12gscnnwp-python3.13-hid-parser-0.1.0]]
- [[1vz0z9yknx8qm0g6vd1z9zp493gsm2gr-python3.13-evdev-1.9.2]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2z29rigf7q3ghh4mnr59bmh8679r2i20-python3.13-pyudev-0.24.3]]
- [[474kivdzi525za8vzpgr0ils1k0qf8r3-wrap-gapps-hook]]
- [[4dq8np7c2mimniwl3if93g7ncz1cjr4r-gtk+3-3.24.49]]
- [[6vwms701y3kk0kdcfs4fkv345v6pd64k-python3.13-xlib-0.33]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bfrhypf8s25npqqk6h8hi5qyr3apb3vr-gdk-pixbuf-2.42.12]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[fikd8dcsvw56iibbm12jm2wsmqgk6k5l-python3.13-pytest-mock-3.14.1]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[gw18fiibdnn237gp7f88xh4nx5db9yj4-python3.13-psutil-7.0.0]]
- [[ihxj4nkr207p44mzx3a6wv3f1lsqy7ld-python3.13-dbus-python-1.4.0]]
- [[jmg2c7bm1cbc0akgbbpjmrbsn792vw86-pytest-check-hook]]
- [[jqqc83j9v460xa1qlp77ky52gbqg5af8-gobject-introspection-wrapped-1.84.0]]
- [[nmy2q4zs1nnh2qlxb2nghy041k3vvyjy-python3.13-typing-extensions-4.14.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[r28vvh52vpd7jg4lwavf323abajp0a1m-source]]
- [[rlyzp1xm9ghkyf96qij1dnxki5g725px-python3.13-pygobject-3.50.0]]
- [[vfb2h653y4k8ag9vlrqa6gh2pdjkkin2-python3.13-pytest-cov-stub-1.0.0]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[vw9ps5df26syym597i1m4dv4fpf3m7wg-librsvg-2.60.0]]
- [[wiymq0rb9pki1dcp8nvwj0gqd8x9ppw7-setuptools-build-hook]]
- [[yrjjl3kfrjd9529s7f5fyyvadraznmxs-libappindicator-gtk3-12.10.1+20.10.20200706.1]]
- [[yx9ag0icz7v1fbkq3an2658q40b7cgd2-python3.13-pyyaml-6.0.2]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:11:57 UTC*
