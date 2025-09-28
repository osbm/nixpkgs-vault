---
aliases:
  - pulseaudio
tags:
  - license/unknown
  - maintainers/lovek323
  - outputs/dev
  - outputs/out
---

# pulseaudio

## 📝 Description

PulseAudio is a sound server for POSIX and Win32 systems.  A
sound server is basically a proxy for your sound applications.
It allows you to do advanced operations on your sound data as it
passes between your application and your hardware.  Things like
transferring the audio to a different machine, changing the
sample format or channel count and mixing several sounds into
one are easily achieved using a sound server.


## 📋 Package Information

- **Name**: `pulseaudio`
- **Version**: `17.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Sound server for POSIX and Win32 systems
- **Homepage**: [http://www.pulseaudio.org/](http://www.pulseaudio.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @lovek323


## 🔧 Build Information

- **Derivation Path**: `/nix/store/rqgfczspkldc6cgfqffc1pk54lvfk004-pulseaudio-17.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/servers/pulseaudio/default.nix:283`
- **Outputs**:
  - `dev`:  `/nix/store/rqgfczspkldc6cgfqffc1pk54lvfk004-pulseaudio-17.0`
  - `out`:  `/nix/store/rqgfczspkldc6cgfqffc1pk54lvfk004-pulseaudio-17.0`

## 🔗 Dependencies

- [[02nvbmkaqzxp5jbnl7i1rcsj85r5cl5p-udev-check-hook]]
- [[28phnmnqgzmkqlby0znahvp3bgx6d6vv-dbus-1.14.10]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[3zc6j1j1qgis43ig9m9gl11iqf058s76-systemd-minimal-libs-257.8]]
- [[40xmgyi47ir13chaazfj51k7yfixg4qr-webrtc-audio-processing-1.3]]
- [[778k2csi3cc3hcfa4rn5x94fprhrj7vd-libcap-2.76]]
- [[7nw7qzp99bw4c256bm4hcapqx00r210p-check-0.15.2]]
- [[8phw25ry27jhc8dd29ccrnpv20c4hmvv-fftw-single-3.3.10]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dzynf7h9bw2qvzwkzm5kmjbgqzpsxj00-systemd-257.8]]
- [[fxawv4y9l5l2qd1h06xblpmvqyj6jc2z-speexdsp-1.2.1]]
- [[gla3w1j7cpkx25rp404b43hjg31r4dfb-libsndfile-1.2.2]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[h3srikh4wmcfw2vs6dr3x5jx4d725bkh-alsa-ucm-Replace-port-device-UCM-context-assertion-with-an-error.patch]]
- [[hh0jfgmx2wk6b251dfjg90nf1rg218if-libasyncns-0.8]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[i6mmaq637c7g8f0pm9c3a7dy31sj9faf-pulseaudio-17.0.tar.xz]]
- [[if30dvb18877vhsf1yhq7bzsgw20xlby-alsa-lib-1.2.14]]
- [[kzxwh3aqk7480761i5c0c7p6iwaln17d-sbc-2.1]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[nw2b07n5gag6b0c9j25qmadbxblizmzh-alsa-ucm-Check-UCM-verb-before-working-with-device-status.patch]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rd011snmw62ls8qrhgk255qbs1v5a5hc-dconf-0.40.0]]
- [[sp2vq01660i7gmsgddk4x9di14gwny4m-gnum4-1.4.20]]
- [[sv8lxxb30bqw2b360ni6rsp89mg2dvbp-libtool-2.5.4]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]
- [[xqkg0g2fljfg9akdnxk7wfsxy59y173w-soxr-0.1.3]]
- [[y8dsx6104ilm8kbx9hhqwd7kzzwa1v7h-perl5.40.0-XML-Parser-2.46]]
- [[ya4khw3b3vyk9fc8rz1vidvpfya614z0-bluez-5.83]]

## 📁 Input Sources

- `/nix/store/hlg89v9ziz70c67kjl58qp1807ym2n5m-add-option-for-installation-sysconfdir.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:34:04 UTC*
