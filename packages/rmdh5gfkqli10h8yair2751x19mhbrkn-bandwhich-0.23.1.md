---
aliases:
  - bandwhich
tags:
  - license/unknown
  - maintainers/Br1ght0ne
  - maintainers/figsoda
  - outputs/out
---

# bandwhich

## 📝 Description

bandwhich sniffs a given network interface and records IP packet size, cross
referencing it with the /proc filesystem on linux or lsof on MacOS. It is
responsive to the terminal window size, displaying less info if there is
no room for it. It will also attempt to resolve ips to their host name in
the background using reverse DNS on a best effort basis.


## 📋 Package Information

- **Name**: `bandwhich`
- **Version**: `0.23.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: CLI utility for displaying current network utilization
- **Homepage**: [https://github.com/imsnif/bandwhich](https://github.com/imsnif/bandwhich)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv6l-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv64-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `powerpc-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `armv5tel-linux`, `armv7a-linux`, `m68k-linux`, `mips-linux`, `mips64-linux`, `mipsel-linux`, `mips64el-linux`, `riscv32-linux`, `armv6l-netbsd`, `mipsel-netbsd`, `riscv64-netbsd`, `x86_64-redox`
## 👥 Maintainers

- @Br1ght0ne
- @figsoda


## 🔧 Build Information

- **Derivation Path**: `/nix/store/rmdh5gfkqli10h8yair2751x19mhbrkn-bandwhich-0.23.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ba/bandwhich/package.nix:40`
- **Outputs**:
  - `out`:  `/nix/store/rmdh5gfkqli10h8yair2751x19mhbrkn-bandwhich-0.23.1`

## 🔗 Dependencies

- [[0f5ann1sgwyp31vlfqqsnr95xzv3mzhf-cargo-1.89.0]]
- [[3bz4j2xzjl92yhiwfyhbz6gv4w1888bw-cargo-setup-hook.sh]]
- [[3ndchkhlxxw50k7nd48i9zdkhsr57mwh-cargo-install-hook.sh]]
- [[4bycw2rdgf33gmn1z26knv8grxxh06w5-rustc-wrapper-1.89.0]]
- [[4cc0y6syxyxvjx1lh8ix60vxkly149fh-auditable-cargo-1.89.0]]
- [[9rdz2my8na9yc8f2z502ly5f0ylcqhh5-bandwhich-0.23.1-vendor]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qi6337yh29r9ppqm262bf6vz0g13451b-cargo-build-hook.sh]]
- [[wjmzmx970mqijs1l0k3f3m0rj10wwl05-source]]
- [[xqxbqs6qgnhvpkcai046s94jfrx8wb62-cargo-check-hook.sh]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:48:13 UTC*
