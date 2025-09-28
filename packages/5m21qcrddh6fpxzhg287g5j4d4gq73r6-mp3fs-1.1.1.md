---
aliases:
  - mp3fs
tags:
  - license/unknown
  - maintainers/Luflosi
  - outputs/out
---

# mp3fs

## 📝 Description

A read-only FUSE filesystem which transcodes between audio formats
(currently FLAC and Ogg Vorbis to MP3) on the fly when opened and read.
This can let you use a FLAC or Ogg Vorbis collection with software
and/or hardware which only understands the MP3 format, or transcode
files through simple drag-and-drop in a file browser.


## 📋 Package Information

- **Name**: `mp3fs`
- **Version**: `1.1.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: FUSE file system that transparently transcodes to MP3
- **Homepage**: [https://khenriks.github.io/mp3fs/](https://khenriks.github.io/mp3fs/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @Luflosi


## 🔧 Build Information

- **Derivation Path**: `/nix/store/5m21qcrddh6fpxzhg287g5j4d4gq73r6-mp3fs-1.1.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/mp/mp3fs/package.nix:51`
- **Outputs**:
  - `out`:  `/nix/store/5m21qcrddh6fpxzhg287g5j4d4gq73r6-mp3fs-1.1.1`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[2kq00m8x7fyj453426v57y24v0ykyyzd-source]]
- [[345q8xwbazzksaiaydm8kd6p5zb1ymr5-libvorbis-1.3.7]]
- [[8f4dz87rkzinrp8k2xdb1gm37xpixnjy-flac-1.5.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[fvy2dpx8zbgmax6cvfpfyzb2cxzadfsd-lame-3.100]]
- [[ji56v9i7bdf14w53nxy71cpr8rrrvmma-fuse-2.9.9]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[x9vwm2d8chwlz6k01dh82gjl07zixjxi-libid3tag-0.16.3]]
- [[zb5cj6gmxg0g561dg8vkmb4sb67z2b07-pandoc-cli-3.6]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:08:34 UTC*
