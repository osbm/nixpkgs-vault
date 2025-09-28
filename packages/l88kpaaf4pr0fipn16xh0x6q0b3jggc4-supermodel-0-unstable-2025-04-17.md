---
aliases:
  - supermodel
tags:
  - license/unknown
  - maintainers/msanft
  - outputs/out
---

# supermodel

## 📝 Description

Supermodel requires specific files to be present in the $HOME directory of
the user running the emulator. To ensure these files are present, move the
configuration and assets as follows:

<code>cp $out/share/supermodel/Config/Supermodel.ini ~/.config/supermodel/Config/Supermodel.ini</code>
<code>cp -r $out/share/supermodel/Assets/* ~/.local/share/supermodel/Assets/</code>

Then the emulator can be started with:
<code>supermodel -game-xml-file=$out/share/supermodel/Config/Games.xml /path/to/romset</code>.


## 📋 Package Information

- **Name**: `supermodel`
- **Version**: `0-unstable-2025-04-17`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Sega Model 3 Arcade Emulator
- **Homepage**: [https://github.com/trzy/supermodel](https://github.com/trzy/supermodel)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @msanft


## 🔧 Build Information

- **Derivation Path**: `/nix/store/l88kpaaf4pr0fipn16xh0x6q0b3jggc4-supermodel-0-unstable-2025-04-17.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/su/supermodel/package.nix:49`
- **Outputs**:
  - `out`:  `/nix/store/l88kpaaf4pr0fipn16xh0x6q0b3jggc4-supermodel-0-unstable-2025-04-17`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[3wl257xhgal4shqwng9p90jalhrc4bnc-glu-9.0.3]]
- [[bghw4ajik18x5k3snmp3r6b58x3jyapp-sdl2-compat-2.32.56]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[nncd4f9vl1alqwmiff6a138ppbsgbp5l-libx11-1.8.12]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rjr24yvx0yd2kw6a94rqzxsszf97ifzz-SDL2_net-2.2.0]]
- [[zyv15dkfx2nh7bcf4x2pqaph5iy20c1d-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:57:27 UTC*
