---
aliases:
  - serious-sam-classic
tags:
  - license/unknown
  - maintainers/l0b0
  - outputs/out
---

# serious-sam-classic

## 📝 Description

Note: This package allows to run both Serious Sam: The First Encounter (serioussam)
and The Second Encounter (serioussamse).

For serioussam you must copy all the assets of the original games into
~/.local/share/Serious-Engine/serioussam for serioussam and
~/.local/share/Serious-Engine/serioussamse for serioussamse.
Look at
https://github.com/tx00100xt/SeriousSamClassic/wiki/How-to-building-a-package-for-Debian-or-Ubuntu.md#game-resources
for instructions on how to do that.
For both games you must also copy the files SE1_10b.gro and ModEXT.txt into the assets.
For serioussam:
- https://raw.githubusercontent.com/tx00100xt/SeriousSamClassic/1.10.7/SamTFE/ModEXT.txt
- https://raw.githubusercontent.com/tx00100xt/SeriousSamClassic/1.10.7/SamTFE/SE1_10b.gro
For serioussamse:
- https://raw.githubusercontent.com/tx00100xt/SeriousSamClassic/1.10.7/SamTSE/ModEXT.txt
- https://raw.githubusercontent.com/tx00100xt/SeriousSamClassic/1.10.7/SamTSE/SE1_10b.gro


## 📋 Package Information

- **Name**: `serious-sam-classic`
- **Version**: `1.10.7`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Open source game engine version developed by Croteam for Serious Sam Classic
- **Homepage**: [https://github.com/tx00100xt/SeriousSamClassic](https://github.com/tx00100xt/SeriousSamClassic)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @l0b0


## 🔧 Build Information

- **Derivation Path**: `/nix/store/5isxw2rg2rgi32cr69n22a2gviai7v47-serious-sam-classic-1.10.7.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/se/serious-sam-classic/package.nix:63`
- **Outputs**:
  - `out`:  `/nix/store/5isxw2rg2rgi32cr69n22a2gviai7v47-serious-sam-classic-1.10.7`

## 🔗 Dependencies

- [[0y20y5glzrd67xskzh9vjindzjl1jiiv-bison-3.8.2]]
- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[345q8xwbazzksaiaydm8kd6p5zb1ymr5-libvorbis-1.3.7]]
- [[4z3zy54ips5245rgfb0d6z7pmracjaiy-libogg-1.3.6]]
- [[7dghrwbkpa50vnhfwy2px1pfbxpqdzr7-source]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bghw4ajik18x5k3snmp3r6b58x3jyapp-sdl2-compat-2.32.56]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gq1x7r7fl6r3w50rrwba6y26xg1nqw70-imagemagick-7.1.2-3]]
- [[mqwqv8lyg8nwikkbrip5h40pdl72rfww-nasm-2.16.03]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[wy61x67y125m36dp7l7xhzqbi30mxg1d-flex-2.6.4]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/px4990qkzhdasbwv7hmid97zlqw7b42b-tfe-fix-cmake-libdir-override.patch`
- `/nix/store/qjmvzaqd9iyxwx9lip3fnf2nnd1i9dgy-tfe-force-using-system-path.patch`
- `/nix/store/rabyiyw57gnqirln1di4icxwqp8q0zd5-tse-fix-cmake-libdir-override.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/wlqjcwr10wvam0smwvnlmjjg8zh64zcj-tse-force-using-system-path.patch`

---
*Generated on 2025-09-27 13:05:48 UTC*
