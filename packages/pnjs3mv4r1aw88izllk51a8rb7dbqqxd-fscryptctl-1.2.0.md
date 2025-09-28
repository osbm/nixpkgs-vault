---
aliases:
  - fscryptctl
tags:
  - license/unknown
  - outputs/out
---

# fscryptctl

## 📝 Description

fscryptctl is a low-level tool written in C that handles raw keys and
manages policies for Linux filesystem encryption, specifically the
"fscrypt" kernel interface which is supported by the ext4, f2fs, and
UBIFS filesystems.
fscryptctl is mainly intended for embedded systems which can't use the
full-featured fscrypt tool, or for testing or experimenting with the
kernel interface to Linux filesystem encryption. fscryptctl does not
handle key generation, key stretching, key wrapping, or PAM integration.
Most users should use the fscrypt tool instead, which supports these
features and generally is much easier to use.
As fscryptctl is intended for advanced users, you should read the kernel
documentation for filesystem encryption before using fscryptctl.


## 📋 Package Information

- **Name**: `fscryptctl`
- **Version**: `1.2.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Small C tool for Linux filesystem encryption
- **Homepage**: [https://github.com/google/fscryptctl](https://github.com/google/fscryptctl)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/pnjs3mv4r1aw88izllk51a8rb7dbqqxd-fscryptctl-1.2.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/fs/fscryptctl/package.nix:26`
- **Outputs**:
  - `out`:  `/nix/store/pnjs3mv4r1aw88izllk51a8rb7dbqqxd-fscryptctl-1.2.0`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[sl39qjbk3m3sas27mz6x8y2i7il4pxwd-source]]
- [[zb5cj6gmxg0g561dg8vkmb4sb67z2b07-pandoc-cli-3.6]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:51:42 UTC*
