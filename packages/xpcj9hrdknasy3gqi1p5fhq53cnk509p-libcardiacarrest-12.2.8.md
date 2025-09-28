---
aliases:
  - libcardiacarrest
tags:
  - license/unknown
  - maintainers/oxij
  - outputs/dev
  - outputs/out
---

# libcardiacarrest

## 📝 Description

libcardiacarrest is a trivial implementation of libpulse
PulseAudio library API that unconditionally (but gracefully)
fails to connect to the PulseAudio daemon and does nothing else.

apulse and pressureaudio (which uses apulse internally) are an
inspiration for this but unlike those two projects
libcardiacarrest is not an emulation layer, all it does is it
gracefully fails to provide the requested PulseAudio service
hoping the application would try something else (e.g. ALSA or
JACK).


## 📋 Package Information

- **Name**: `libcardiacarrest`
- **Version**: `12.2.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Trivial implementation of libpulse PulseAudio library API
- **Homepage**: [https://github.com/oxij/libcardiacarrest](https://github.com/oxij/libcardiacarrest)
- **License**: `unknown`
## 👥 Maintainers

- @oxij


## 🔧 Build Information

- **Derivation Path**: `/nix/store/xpcj9hrdknasy3gqi1p5fhq53cnk509p-libcardiacarrest-12.2.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libcardiacarrest/package.nix:42`
- **Outputs**:
  - `dev`:  `/nix/store/xpcj9hrdknasy3gqi1p5fhq53cnk509p-libcardiacarrest-12.2.8`
  - `out`:  `/nix/store/xpcj9hrdknasy3gqi1p5fhq53cnk509p-libcardiacarrest-12.2.8`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[lvgn22vnwjhyfvsj23j2gycw5abhp3fw-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:12:48 UTC*
