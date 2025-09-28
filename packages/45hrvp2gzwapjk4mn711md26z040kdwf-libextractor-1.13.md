---
aliases:
  - libextractor
tags:
  - license/unknown
  - maintainers/jorsn
  - outputs/out
---

# libextractor

## 📝 Description

GNU libextractor is a library used to extract meta-data from files
of arbitrary type.  It is designed to use helper-libraries to perform
the actual extraction, and to be trivially extendable by linking
against external extractors for additional file types.

The goal is to provide developers of file-sharing networks or
WWW-indexing bots with a universal library to obtain simple keywords
to match against queries.  libextractor contains a shell-command
extract that, similar to the well-known file command, can extract
meta-data from a file an print the results to stdout.

Currently, libextractor supports the following formats: HTML, PDF,
PS, OLE2 (DOC, XLS, PPT), OpenOffice (sxw), StarOffice (sdw), DVI,
MAN, FLAC, MP3 (ID3v1 and ID3v2), NSF(E) (NES music), SID (C64
music), OGG, WAV, EXIV2, JPEG, GIF, PNG, TIFF, DEB, RPM, TAR(.GZ),
ZIP, ELF, S3M (Scream Tracker 3), XM (eXtended Module), IT (Impulse
Tracker), FLV, REAL, RIFF (AVI), MPEG, QT and ASF.  Also, various
additional MIME types are detected.


## 📋 Package Information

- **Name**: `libextractor`
- **Version**: `1.13`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Simple library for keyword extraction
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @jorsn


## 🔧 Build Information

- **Derivation Path**: `/nix/store/45hrvp2gzwapjk4mn711md26z040kdwf-libextractor-1.13.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/libraries/libextractor/default.nix:102`
- **Outputs**:
  - `out`:  `/nix/store/45hrvp2gzwapjk4mn711md26z040kdwf-libextractor-1.13`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[1jggrk899zyajdg7srrilwqpivkzdqz8-gst-plugins-good-1.26.5]]
- [[345q8xwbazzksaiaydm8kd6p5zb1ymr5-libvorbis-1.3.7]]
- [[4dq8np7c2mimniwl3if93g7ncz1cjr4r-gtk+3-3.24.49]]
- [[8f4dz87rkzinrp8k2xdb1gm37xpixnjy-flac-1.5.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[c84lczi43scicdxf2nmqs8nyglz8p0nx-exiv2-0.28.diff]]
- [[c98ilv55im32083jvahcxh6f8pgq0n94-exiv2-0.28.7]]
- [[cldyirjyjhr6zaf1mk4x8735j1c9v8f3-gst-hardcode-plugins.patch]]
- [[fyx64mpv2vvlsg90z8jq17b2qac3jn35-libgsf-1.14.53]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[khcnbl4hfjibl6zyn5r3rpdsmzw5pvbr-gstreamer-1.26.5]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[m0h8vm7wnxqmzy77yph902p607lx7np5-gettext-0.25.1]]
- [[p433q2paz48iw6dr4s3z01hq24lnbhzl-libmpeg2-0.5.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qy6jmq3x3wjl0d6vzwnlzmd9mqsmai94-gst-plugins-base-1.26.5]]
- [[rxp4c3809py9x7phcnh5b7kl3n3f6a2g-rpm-4.20.1]]
- [[sv8lxxb30bqw2b360ni6rsp89mg2dvbp-libtool-2.5.4]]
- [[xhywpl9idmkbvsm45x8cxby1i1vvmazq-libextractor-1.13.tar.gz]]
- [[y4lfwlviqzkdrk9973a02vpl0fk4h1vy-bzip2-1.0.8]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:45:38 UTC*
