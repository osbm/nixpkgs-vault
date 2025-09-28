---
aliases:
  - meek
tags:
  - license/unknown
  - maintainers/doronbehar
  - outputs/out
---

# meek

## 📝 Description

meek is a blocking-resistant pluggable transport for Tor. It encodes a
data stream as a sequence of HTTPS requests and responses. Requests are
reflected through a hard-to-block third-party web server in order to
avoid talking directly to a Tor bridge. HTTPS encryption hides
fingerprintable byte patterns in Tor traffic.


## 📋 Package Information

- **Name**: `meek`
- **Version**: `0.38.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Blocking-resistant pluggable transport for Tor
- **Homepage**: [https://gitlab.torproject.org/tpo/anti-censorship/pluggable-transports/meek](https://gitlab.torproject.org/tpo/anti-censorship/pluggable-transports/meek)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @doronbehar


## 🔧 Build Information

- **Derivation Path**: `/nix/store/5rwhpqjm0hpqzd5lwx3d3alwqrlh9q4k-meek-0.38.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/me/meek/package.nix:36`
- **Outputs**:
  - `out`:  `/nix/store/5rwhpqjm0hpqzd5lwx3d3alwqrlh9q4k-meek-0.38.0`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[nh7frf7q72zf72qvjr47w244j05w839l-meek-0.38.0-go-modules]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[sjn60xkjskbj3ql1ndbxg041xqax98yp-source]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:17:34 UTC*
