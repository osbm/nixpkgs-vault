---
aliases:
  - libfishsound
tags:
  - license/unknown
  - outputs/out
---

# libfishsound

## 📝 Description

libfishsound by itself is designed to handle raw codec streams from a lower level layer such as UDP datagrams. When these codecs are used in files, they are commonly encapsulated in Ogg to produce Ogg FLAC, Speex and Ogg Vorbis files.

libfishsound is a wrapper around the existing codec libraries and provides a consistent, higher-level programming interface. It has been designed for use in a wide variety of applications; it has no direct dependencies on Ogg encapsulation, though it is most commonly used in conjunction with liboggz to decode or encode FLAC, Speex or Vorbis audio tracks in Ogg files, including Ogg Theora and Annodex.

FishSound has been developed and tested on GNU/Linux, Darwin/MacOSX and Win32. It probably also works on other Unix-like systems via GNU autoconf. For Win32: nmake Makefiles, Visual Studio .NET 2003 solution files and Visual C++ 6.0 workspace files are all provided in the source distribution.


## 📋 Package Information

- **Name**: `libfishsound`
- **Version**: `1.0.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Simple programming interface for decoding and encoding audio data using Xiph.org codecs (FLAC, Speex and Vorbis)
- **Homepage**: [https://xiph.org/fishsound/](https://xiph.org/fishsound/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/kwr4sxlmajkraw0mna39jjsxkcsxzyhn-libfishsound-1.0.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libfishsound/package.nix:59`
- **Outputs**:
  - `out`:  `/nix/store/kwr4sxlmajkraw0mna39jjsxkcsxzyhn-libfishsound-1.0.0`

## 🔗 Dependencies

- [[0fklqll2nyf1sw3vjb8rl6iwh0qb3dgx-0001-Patch-configure.ac-to-specify-config-macro-dir.patch]]
- [[0ynn4y23ihq1ii92sgcfw62aljjgmi13-speex-1.2.1]]
- [[345q8xwbazzksaiaydm8kd6p5zb1ymr5-libvorbis-1.3.7]]
- [[3j979j928skdsfn7ny1xn2mz6g5kphmd-0003-Fix-incompatible-flac-callback-types.patch]]
- [[8f4dz87rkzinrp8k2xdb1gm37xpixnjy-flac-1.5.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[sjb7qnl5igxryg0wcanzbh0br4bvx750-0002-flac-set-vendor_string.length-0.patch]]
- [[wpk8p5pfy4vjbiihgj4gl1h2m6vvbhm3-libfishsound-1.0.0.tar.gz]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:45:46 UTC*
