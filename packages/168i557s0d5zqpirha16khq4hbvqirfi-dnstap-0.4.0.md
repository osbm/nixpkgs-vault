---
aliases:
  - dnstap
tags:
  - license/unknown
  - maintainers/azahi
  - outputs/out
---

# dnstap

## 📝 Description

dnstap implements an encoding format for DNS server events. It uses a
lightweight framing on top of event payloads encoded using Protocol
Buffers and is transport neutral.

dnstap can represent internal state inside a DNS server that is difficult
to obtain using techniques based on traditional packet capture or
unstructured textual format logging.


## 📋 Package Information

- **Name**: `dnstap`
- **Version**: `0.4.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Structured DNS server events decoding utility
- **Homepage**: [https://dnstap.info](https://dnstap.info)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @azahi


## 🔧 Build Information

- **Derivation Path**: `/nix/store/168i557s0d5zqpirha16khq4hbvqirfi-dnstap-0.4.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/dn/dnstap/package.nix:30`
- **Outputs**:
  - `out`:  `/nix/store/168i557s0d5zqpirha16khq4hbvqirfi-dnstap-0.4.0`

## 🔗 Dependencies

- [[8jks70psgm9vhwigh7m0kkv89z71hq3v-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[xhbbd3dmb0cxplx06kc2vxg137wdj130-dnstap-0.4.0-go-modules]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:48:08 UTC*
