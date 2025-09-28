---
aliases:
  - libpressureaudio
tags:
  - license/unknown
  - maintainers/jagajaga
  - outputs/out
---

# libpressureaudio

## 📝 Description

apulse (https://github.com/i-rinat/apulse) implements most of libpulse
API over pure ALSA in 5% LOC of the original PulseAudio.

But apulse is made to be used as a wrapper that substitutes its
replacement libs into LD_LIBRARY_PATH. The problem with that is
that you still have to link against the original libpulse.

pressureaudio (http://git.r-36.net/pressureaudio/) wraps apulse
with everything you need to replace libpulse completely.

This derivation is a reimplementation of pressureaudio in pure
nix.

You can simply override libpulse with this and most
packages would just work.


## 📋 Package Information

- **Name**: `libpressureaudio`
- **Version**: `0.1.14`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Libpulse without any sound daemons over pure ALSA
- **Homepage**: [https://github.com/i-rinat/apulse](https://github.com/i-rinat/apulse)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @jagajaga


## 🔧 Build Information

- **Derivation Path**: `/nix/store/sr7k91x6yq35c2xlcj13hahpq1l71pqv-libpressureaudio-0.1.14.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/misc/apulse/pressureaudio.nix:72`
- **Outputs**:
  - `out`:  `/nix/store/sr7k91x6yq35c2xlcj13hahpq1l71pqv-libpressureaudio-0.1.14`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[f368fizl82c6krd1a5gcxp0m6m4zd474-intltool-0.51.0]]
- [[i6mmaq637c7g8f0pm9c3a7dy31sj9faf-pulseaudio-17.0.tar.xz]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qphz2h8rj3rdyk7gj6b65fqlcnadd27r-apulse-0.1.14]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:50:41 UTC*
