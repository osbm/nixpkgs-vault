---
aliases:
  - udiskie
tags:
  - license/unknown
  - maintainers/dotlambda
  - outputs/dist
  - outputs/out
---

# udiskie

## 📝 Description

udiskie is a udisks2 front-end that allows to manage removeable media such
as CDs or flash drives from userspace.

Its features include:
- automount removable media
- notifications
- tray icon
- command line tools for manual un-/mounting
- LUKS encrypted devices
- unlocking with keyfiles (requires udisks 2.6.4)
- loop devices (mounting iso archives)
- password caching (requires python keyutils 0.3)


## 📋 Package Information

- **Name**: `udiskie`
- **Version**: `2.5.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Removable disk automounter for udisks
- **Homepage**: [https://github.com/coldfix/udiskie](https://github.com/coldfix/udiskie)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @dotlambda


## 🔧 Build Information

- **Derivation Path**: `/nix/store/iqbsrs191rsl8s11h2bcz9r9k8r5padp-udiskie-2.5.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ud/udiskie/package.nix:94`
- **Outputs**:
  - `dist`:  `/nix/store/iqbsrs191rsl8s11h2bcz9r9k8r5padp-udiskie-2.5.8`
  - `out`:  `/nix/store/iqbsrs191rsl8s11h2bcz9r9k8r5padp-udiskie-2.5.8`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[474kivdzi525za8vzpgr0ils1k0qf8r3-wrap-gapps-hook]]
- [[4dq8np7c2mimniwl3if93g7ncz1cjr4r-gtk+3-3.24.49]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[dnbzpphxbd6h31n44gfwbg1qf9q03wcr-pypa-build-hook.sh]]
- [[fmgak3lvqw3ff8wym1v40kgi0b5i1iza-python-runtime-deps-check-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[hw2g5hvz2qld87skldizxdd8xl5l8cmc-python3.13-docopt-0.6.2]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[jmg2c7bm1cbc0akgbbpjmrbsn792vw86-pytest-check-hook]]
- [[jqqc83j9v460xa1qlp77ky52gbqg5af8-gobject-introspection-wrapped-1.84.0]]
- [[jwxxa82dm8hs6cwzhkyfb4v8w35f6jqv-source]]
- [[mh835h1mhbqinppdi3ggz9f28b87f0vz-libnotify-0.8.6]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[r92cq63rjlpwiy2x8ihgvpphyqfqjkr1-udisks-2.10.2]]
- [[rlyzp1xm9ghkyf96qij1dnxki5g725px-python3.13-pygobject-3.50.0]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[vw9ps5df26syym597i1m4dv4fpf3m7wg-librsvg-2.60.0]]
- [[wddlhdpbafkf2n7yy6r2mf58vbnszlif-python3.13-keyutils-0.6]]
- [[yrjjl3kfrjd9529s7f5fyyvadraznmxs-libappindicator-gtk3-12.10.1+20.10.20200706.1]]
- [[yvzr26fvdmxmb2pwmq6c0qv771pjpvmz-asciidoc-10.2.1]]
- [[yx9ag0icz7v1fbkq3an2658q40b7cgd2-python3.13-pyyaml-6.0.2]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/7rpcvnfs4a2dywg7ib0jj9kl4a4adgcp-locale-path.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:18:08 UTC*
