---
aliases:
  - perfect_dark
tags:
  - not-available
  - license/unknown
  - maintainers/PaulGrandperrin
  - maintainers/normalcea
  - maintainers/SigmaSquadron
  - outputs/out
---

# perfect_dark

## 📝 Description

This is a port of Ryan Dywer's decompilation of classic N64
shooter Perfect Dark to modern systems.

You will need to provide a copy of the ROM at
`$HOME/.local/share/perfectdark/data/pd.ntsc-final.z64` to launch
the game.

Though `ntsc-final` is the recommended default, you can change
the ROM variant of this game with an expression like this:

```nix
  perfect_dark.override { romID = "jpn-final"; }
```

Supported romIDs are `[
  "ntsc-final"
  "pal-final"
  "jpn-final"
]`.


## 📋 Package Information

- **Name**: `perfect_dark`
- **Version**: `0-unstable-2025-08-25`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Modern cross-platform port of Perfect Dark
- **Homepage**: [https://github.com/fgsfdsfgs/perfect_dark/](https://github.com/fgsfdsfgs/perfect_dark/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @PaulGrandperrin
- @normalcea
- @SigmaSquadron


## 🔧 Build Information

- **Derivation Path**: `/nix/store/8wilclrvhmhlypnwdd9an777pcwip9g3-perfect_dark-0-unstable-2025-08-25.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/pe/perfect_dark/package.nix:106`
- **Outputs**:
  - `out`:  `/nix/store/8wilclrvhmhlypnwdd9an777pcwip9g3-perfect_dark-0-unstable-2025-08-25`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[3a07z0aj8y4qjz8syg4akjb7c21d3ba7-source]]
- [[761d6f8hhrvq2qrbqc6ygxr3x34img28-libglvnd-1.7.0]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bghw4ajik18x5k3snmp3r6b58x3jyapp-sdl2-compat-2.32.56]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:11:26 UTC*
