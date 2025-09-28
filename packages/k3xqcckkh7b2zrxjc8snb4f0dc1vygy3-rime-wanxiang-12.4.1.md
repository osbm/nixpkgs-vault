---
aliases:
  - rime-wanxiang
tags:
  - license/unknown
  - maintainers/rc-zb
  - outputs/out
---

# rime-wanxiang

## 📝 Description

万象拼音基础版 is a basic quanpin and shuangpin input schema for Rime based on
[万象 dictionaries and grammar models](https://github.com/amzxyz/RIME-LMDG),
supporting traditional shuangpin as well as tonal schemata such as 自然龙 and
龙码.

The schema requires to work the grammar model `wanxiang-lts-zh-hans.gram`.
However, this file is
[released](https://github.com/amzxyz/RIME-LMDG/releases/tag/LTS) by
carelessly overriding the old versions
(see the [discussion](https://github.com/amzxyz/RIME-LMDG/issues/22)). So
we can't pack it into Nixpkgs, which demands reproducibility. You have to
download it yourself and place it in the user directory of Rime.

The upstream `default.yaml` is included as
`wanxiang_suggested_default.yaml`. To enable it, please modify your
`default.custom.yaml` as such:

```yaml
patch:
  __include: wanxiang_suggested_default:/
```


## 📋 Package Information

- **Name**: `rime-wanxiang`
- **Version**: `12.4.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Feature-rich pinyin schema for Rime, basic edition
- **Homepage**: [https://github.com/amzxyz/rime_wanxiang](https://github.com/amzxyz/rime_wanxiang)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @rc-zb


## 🔧 Build Information

- **Derivation Path**: `/nix/store/k3xqcckkh7b2zrxjc8snb4f0dc1vygy3-rime-wanxiang-12.4.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ri/rime-wanxiang/package.nix:35`
- **Outputs**:
  - `out`:  `/nix/store/k3xqcckkh7b2zrxjc8snb4f0dc1vygy3-rime-wanxiang-12.4.1`

## 🔗 Dependencies

- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[8rjbfjwiiyyyryhhn6ywyrvhfnpq2h2v-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:20:26 UTC*
