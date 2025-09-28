---
aliases:
  - m1n1
tags:
  - not-available
  - license/unknown
  - maintainers/normalcea
  - outputs/out
---

# m1n1

## 📝 Description

m1n1 is the bootloader developed by the Asahi Linux project to
bridge the Apple (XNU) boot ecosystem to the Linux boot ecosystem.

What it does:

- Initializes hardware
- Puts up a pretty Nix logo
- Loads embedded (appended) payloads, which can be:
   - Device Trees (FDTs), with automatic selection based on the platform
   - Initramfs images (compressed CPIO archives)
   - Kernel images in Linux ARM64 boot format (optionally compressed)
   - Configuration statements


## 📋 Package Information

- **Name**: `m1n1`
- **Version**: `1.5.0`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Bootloader to bridge the Apple (XNU) boot to Linux boot
- **Homepage**: [https://github.com/AsahiLinux/m1n1](https://github.com/AsahiLinux/m1n1)
- **License**: `unknown`
- **Platforms**: `aarch64-darwin`, `aarch64-freebsd`, `aarch64-genode`, `aarch64-linux`, `aarch64-netbsd`, `aarch64_be-none`, `aarch64-none`, `aarch64-windows`
## 👥 Maintainers

- @normalcea


## 🔧 Build Information

- **Derivation Path**: `/nix/store/cll2x9ny2y00m9k943m92drcz36pj49s-m1n1-1.5.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/m1/m1n1/package.nix:83`
- **Outputs**:
  - `out`:  `/nix/store/cll2x9ny2y00m9k943m92drcz36pj49s-m1n1-1.5.0`

## 🔗 Dependencies

- [[16b2bc785nxd884yh4rjd1i580g4za9k-nixos-icons-0-unstable-2024-04-10]]
- [[5nnhidqdxck81ybxrn66wf6aplb679dk-python3.13-construct-2.10.70]]
- [[bb3afapc6lwrgr09s5nf5aswbmm1s25v-source-code-pro-2.042]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gq1x7r7fl6r3w50rrwba6y26xg1nqw70-imagemagick-7.1.2-3]]
- [[ldz1sfmijgwp2n7lj5wdmj57zkynlw87-source]]
- [[lrbclcph1hpv5j144lgma5lmswj2c48l-python3.13-pytest-8.4.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pldfa9xafzpqfs0xkxw6sqir28lvsb1r-python3.13-pyserial-3.5]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:07:50 UTC*
