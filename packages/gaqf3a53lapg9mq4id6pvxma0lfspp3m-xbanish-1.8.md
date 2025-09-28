---
aliases:
  - xbanish
tags:
  - license/unknown
  - maintainers/choochootrain
  - outputs/out
---

# xbanish

## 📝 Description

xbanish hides the mouse cursor when you start typing, and shows it again when
the mouse cursor moves or a mouse button is pressed.  This is similar to
xterm's pointerMode setting, but xbanish works globally in the X11 session.

unclutter's -keystroke mode is supposed to do this, but it's broken[0].  I
looked into fixing it, but the unclutter source code is terrible, so I wrote
xbanish.

The name comes from ratpoison's "banish" command that sends the cursor to the
corner of the screen.


## 📋 Package Information

- **Name**: `xbanish`
- **Version**: `1.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Hides mouse pointer while not in use
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @choochootrain


## 🔧 Build Information

- **Derivation Path**: `/nix/store/gaqf3a53lapg9mq4id6pvxma0lfspp3m-xbanish-1.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/xb/xbanish/package.nix:38`
- **Outputs**:
  - `out`:  `/nix/store/gaqf3a53lapg9mq4id6pvxma0lfspp3m-xbanish-1.8`

## 🔗 Dependencies

- [[2fbx94cnniix1a6h9b265icc5syn829m-libxfixes-6.0.1]]
- [[30vv9sbj3zwdld70lvdwh5bn2p80ikyc-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[d99f4z55b6p4hx1wfl4r6d6i0zi5bh7m-libxext-1.3.6]]
- [[f2zlnw16484q5c9hi6fjnmbiimskrwsg-libxt-1.3.1]]
- [[nncd4f9vl1alqwmiff6a138ppbsgbp5l-libx11-1.8.12]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[xsh1xzh45dh4z7s7aj6vvm8b267p3n6v-libXi-1.8.2]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:16:03 UTC*
