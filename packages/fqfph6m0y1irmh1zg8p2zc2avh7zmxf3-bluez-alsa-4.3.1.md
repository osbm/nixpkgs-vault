---
aliases:
  - bluez-alsa
tags:
  - license/unknown
  - maintainers/oxij
  - outputs/out
---

# bluez-alsa

## 📝 Description

Bluez-ALSA (BlueALSA) is an ALSA backend for Bluez 5 audio interface.
Bluez-ALSA registers all Bluetooth devices with audio profiles in Bluez
under a virtual ALSA PCM device called `bluealsa` that supports both
playback and capture.

Some backstory: Bluez 5 removed built-in support for ALSA in favor of a
generic interface for 3rd party appliations. Thereafter, PulseAudio
implemented a backend for that interface and became the only way to get
Bluetooth audio with Bluez 5. Users prefering ALSA stayed on Bluez 4.
However, Bluez 4 eventually became deprecated.

This package is a rebirth of a direct interface between ALSA and Bluez 5,
that, unlike PulseAudio, provides KISS near-metal-like experience. It is
not possible to run BluezALSA and PulseAudio Bluetooth at the same time
due to limitations in Bluez, but it is possible to run PulseAudio over
BluezALSA if you disable `bluetooth-discover` and `bluez5-discover`
modules in PA and configure it to play/capture sound over `bluealsa` PCM.


## 📋 Package Information

- **Name**: `bluez-alsa`
- **Version**: `4.3.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Bluez 5 Bluetooth Audio ALSA Backend
- **Homepage**: [https://github.com/Arkq/bluez-alsa](https://github.com/Arkq/bluez-alsa)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @oxij


## 🔧 Build Information

- **Derivation Path**: `/nix/store/fqfph6m0y1irmh1zg8p2zc2avh7zmxf3-bluez-alsa-4.3.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/bl/bluez-alsa/package.nix:68`
- **Outputs**:
  - `out`:  `/nix/store/fqfph6m0y1irmh1zg8p2zc2avh7zmxf3-bluez-alsa-4.3.1`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[28phnmnqgzmkqlby0znahvp3bgx6d6vv-dbus-1.14.10]]
- [[39cjpzrja9nlwnz564n58qspjkrmk7ss-libbsd-0.12.2]]
- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[g3jllw2yq0sg91v7d8z7k4fbwfr5a31j-fdk-aac-2.0.3]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[if30dvb18877vhsf1yhq7bzsgw20xlby-alsa-lib-1.2.14]]
- [[kzxwh3aqk7480761i5c0c7p6iwaln17d-sbc-2.1]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pp99kqhfn7z3a58pjkv4kiyrs62k0bj4-readline-8.3p1]]
- [[q0n6q4ihz5sf42w4j9fzy9pbg23xd3ch-source]]
- [[ya4khw3b3vyk9fc8rz1vidvpfya614z0-bluez-5.83]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:44:00 UTC*
