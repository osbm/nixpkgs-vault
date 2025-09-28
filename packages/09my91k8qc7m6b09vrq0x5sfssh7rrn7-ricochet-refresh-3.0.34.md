---
aliases:
  - ricochet-refresh
tags:
  - license/unknown
  - outputs/out
---

# ricochet-refresh

## 📝 Description

Ricochet Refresh is a peer-to-peer messenger app that uses Tor
to connect clients.

When you start Ricochet Refresh it creates a Tor hidden
service on your computer.  The address of this hidden service
is your anonymous identity on the Tor network and how others
will be able to communicate with you.  When you start a chat
with one of your contacts a Tor circuit is created between
your machine and the your contact's machine.

The original Ricochet uses onion "v2" hashed-RSA addresses,
which are no longer supported by the Tor network.  Ricochet
Refresh upgrades the original Ricochet protocol to use the
current onion "v3" ed25519 addresses.


## 📋 Package Information

- **Name**: `ricochet-refresh`
- **Version**: `3.0.34`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Secure chat without DNS or WebPKI
- **Homepage**: [https://www.ricochetrefresh.net/](https://www.ricochetrefresh.net/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/09my91k8qc7m6b09vrq0x5sfssh7rrn7-ricochet-refresh-3.0.34.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ri/ricochet-refresh/package.nix:59`
- **Outputs**:
  - `out`:  `/nix/store/09my91k8qc7m6b09vrq0x5sfssh7rrn7-ricochet-refresh-3.0.34`

## 🔗 Dependencies

- [[0dyaxjhz2kj25fissh5yj32khwz8crrz-qtbase-5.15.17]]
- [[33c36rmhc2gvhrdcznlniklbyv27qs1y-source]]
- [[4dhrk0y3h7f7qgs499ma30zl4y704ij6-qttools-5.15.17]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i7jgss4ziswp61yzj8m4ghspc0akyl4q-qtquickcontrols2-5.15.17]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[r2db2qh3wxwmqd0615pzcixjcirgvj12-wrap-qt5-apps-hook]]
- [[xpy9pxxcdadsj0vnvqnkfq5sd77r04jg-qtmultimedia-5.15.17]]
- [[yvvzdlh598z18dp73b7b76y5i8mrp4mv-protobuf-21.12]]
- [[z2hyyq1isiny6dmhrwvsmd9f6k2xwd9b-qtwayland-5.15.17]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:20:08 UTC*
