---
aliases:
  - gscreenshot
tags:
  - license/unknown
  - maintainers/davisrichard437
  - outputs/dist
  - outputs/out
---

# gscreenshot

## 📝 Description

gscreenshot provides a common frontend and expanded functionality to a
number of X11 and Wayland screenshot and region selection utilities.

In a nutshell, gscreenshot supports the following:

- Capturing a full-screen screenshot
- Capturing a region of the screen interactively
- Capturing a window interactively
- Capturing the cursor
- Capturing the cursor, using an alternate cursor glyph
- Capturing a screenshot with a delay
- Showing a notification when a screenshot is taken
- Capturing a screenshot from the command line or a custom script
- Capturing a screenshot using a GUI
- Saving to a variety of image formats including 'bmp', 'eps', 'gif', 'jpeg', 'pcx', 'pdf', 'ppm', 'tiff', 'png', and 'webp'.
- Copying a screenshot to the system clipboard
- Opening a screenshot in the configured application after capture

Other than region selection, gscreenshot's CLI is non-interactive and is suitable for use in scripts.


## 📋 Package Information

- **Name**: `gscreenshot`
- **Version**: `3.9.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Screenshot frontend (CLI and GUI) for a variety of screenshot backends
- **Homepage**: [https://github.com/thenaterhood/gscreenshot](https://github.com/thenaterhood/gscreenshot)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @davisrichard437


## 🔧 Build Information

- **Derivation Path**: `/nix/store/8jrhrb0xldf25bh9izvkgfx4p7k5mg2z-gscreenshot-3.9.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/gs/gscreenshot/package.nix:66`
- **Outputs**:
  - `dist`:  `/nix/store/8jrhrb0xldf25bh9izvkgfx4p7k5mg2z-gscreenshot-3.9.2`
  - `out`:  `/nix/store/8jrhrb0xldf25bh9izvkgfx4p7k5mg2z-gscreenshot-3.9.2`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[11ims70b1fr01h15n3v611w1qvndvwjz-slop-7.6]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[474kivdzi525za8vzpgr0ils1k0qf8r3-wrap-gapps-hook]]
- [[4dq8np7c2mimniwl3if93g7ncz1cjr4r-gtk+3-3.24.49]]
- [[6vwms701y3kk0kdcfs4fkv345v6pd64k-python3.13-xlib-0.33]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[9bb1kg4m58af1wl68crg7bljq3vfi74s-scrot-1.12.1]]
- [[9v86zhyw3s3n6xgz62xvz018vxswfpgg-wl-clipboard-2.2.1]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[d5rgq2qwa73cabnkp2smb30x3wvi326f-xdg-utils-1.2.1]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[fa1g77a4qwniinzgz3m2b4w9zymm5yv8-xclip-0.13]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[jqqc83j9v460xa1qlp77ky52gbqg5af8-gobject-introspection-wrapped-1.84.0]]
- [[m0h8vm7wnxqmzy77yph902p607lx7np5-gettext-0.25.1]]
- [[nd1zw16vl28mxd1k04mxdbw8cwcxadla-slurp-1.5.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[qsiywi5rnyazpvg33b9hzb523vw43yyd-grim-1.5.0]]
- [[rlyzp1xm9ghkyf96qij1dnxki5g725px-python3.13-pygobject-3.50.0]]
- [[sq52aisvvjkjzrzvzg2lgyvbvjav3izj-source]]
- [[swwhxdnkhx8q81vm3m58k5kmlgsm4b51-python3.13-pillow-11.3.0]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[wiymq0rb9pki1dcp8nvwj0gqd8x9ppw7-setuptools-build-hook]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/614xcjs4f2215n2mrfsgqpa4g7rm1w7z-0001-Changing-paths-to-be-nix-compatible.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:58:38 UTC*
