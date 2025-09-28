---
aliases:
  - android-tools
tags:
  - license/unknown
  - maintainers/adrian-gierakowski
  - maintainers/hadilq
  - maintainers/johnrtitor
  - maintainers/numinit
  - maintainers/RossComputerGuy
  - outputs/out
---

# android-tools

## 📝 Description

Android SDK Platform-Tools is a component for the Android SDK. It
includes tools that interface with the Android platform, such as adb and
fastboot. These tools are required for Android app development. They're
also needed if you want to unlock your device bootloader and flash it
with a new system image.
Currently the following tools are supported:
- adb
- fastboot
- mke2fs.android (required by fastboot)
- simg2img, img2simg, append2simg
- lpdump, lpmake, lpadd, lpflash, lpunpack
- mkbootimg, unpack_bootimg, repack_bootimg, avbtool
- mkdtboimg


## 📋 Package Information

- **Name**: `android-tools`
- **Version**: `35.0.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Android SDK platform tools
- **Homepage**: [https://github.com/nmeum/android-tools](https://github.com/nmeum/android-tools)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @adrian-gierakowski
- @hadilq
- @johnrtitor
- @numinit
- @RossComputerGuy


## 🔧 Build Information

- **Derivation Path**: `/nix/store/3qlj6dljlya2mkzcal03y2nynnmbrli9-android-tools-35.0.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/tools/misc/android-tools/default.nix:77`
- **Outputs**:
  - `out`:  `/nix/store/3qlj6dljlya2mkzcal03y2nynnmbrli9-android-tools-35.0.2`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[3f2abhm65lrdsqhh6fwx8l2k6hkpyjwy-fmt-10.2.1]]
- [[3zc6j1j1qgis43ig9m9gl11iqf058s76-systemd-minimal-libs-257.8]]
- [[41s84g5y48afa0w1df9rjz6sny3k464r-protobuf-32.0]]
- [[4j0kzhkdw26xxkpmj4psg00qvsmcfmxz-python3-3.13.7-env]]
- [[6gws6n92iv1sxvqqin5n019pwksx4z8w-gtest-1.17.0]]
- [[81nia7jwqkv3a6akgzwh0hdanshvvfm4-0003-extras-libjsonpb-Fix-incompatibility-with-protobuf-v.patch]]
- [[8rgz3781yw1gmfkj3lg2z5pn1y5k855h-lz4-1.10.0]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[a1n7vvfw15c8l06cq26dmcwx11qgzlal-android-tools-35.0.2.tar.xz]]
- [[ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[ilky15hn83zp9cxkh8bq41ph6nn2j61n-brotli-1.1.0]]
- [[izjrwizjx9aif73k8wmnxbnwl8p11jfh-pcre2-10.44]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:56:38 UTC*
