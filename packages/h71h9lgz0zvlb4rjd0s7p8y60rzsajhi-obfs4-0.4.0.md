---
aliases:
  - obfs4
tags:
  - license/unknown
  - maintainers/thoughtpolice
  - outputs/out
---

# obfs4

## 📝 Description

Obfs4proxy is a tool that attempts to circumvent censorship by
transforming the Tor traffic between the client and the bridge.
This way censors, who usually monitor traffic between the client
and the bridge, will see innocent-looking transformed traffic
instead of the actual Tor traffic.  obfs4proxy implements the
obfsucation protocols obfs2, obfs3, and obfs4.  It is written in
Go and is compliant with the Tor pluggable transports
specification, and its modular architecture allows it to support
multiple pluggable transports.


## 📋 Package Information

- **Name**: `obfs4`
- **Version**: `0.4.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Circumvents censorship by transforming Tor traffic between clients and bridges
- **Homepage**: [https://gitlab.torproject.org/tpo/anti-censorship/pluggable-transports/lyrebird](https://gitlab.torproject.org/tpo/anti-censorship/pluggable-transports/lyrebird)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @thoughtpolice


## 🔧 Build Information

- **Derivation Path**: `/nix/store/h71h9lgz0zvlb4rjd0s7p8y60rzsajhi-obfs4-0.4.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ob/obfs4/package.nix:40`
- **Outputs**:
  - `out`:  `/nix/store/h71h9lgz0zvlb4rjd0s7p8y60rzsajhi-obfs4-0.4.0`

## 🔗 Dependencies

- [[3kfik1hxdnc9s7r5d4dfrs93p6vacvd0-source]]
- [[6amgss400jhqksycp3yzrxhxgl512mmw-obfs4-0.4.0-go-modules]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:30:08 UTC*
