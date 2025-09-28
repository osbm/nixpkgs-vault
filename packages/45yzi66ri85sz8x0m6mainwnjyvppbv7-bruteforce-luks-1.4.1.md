---
aliases:
  - bruteforce-luks
tags:
  - license/unknown
  - outputs/out
---

# bruteforce-luks

## 📝 Description

The program tries to decrypt at least one of the key slots by trying
all the possible passwords. It is especially useful if you know
something about the password (i.e. you forgot a part of your password but
still remember most of it). Finding the password of a volume without
knowing anything about it would take way too much time (unless the
password is really short and/or weak). It can also use a dictionary.


## 📋 Package Information

- **Name**: `bruteforce-luks`
- **Version**: `1.4.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Cracks passwords of LUKS encrypted volumes
- **Homepage**: [https://github.com/glv2/bruteforce-luks](https://github.com/glv2/bruteforce-luks)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/45yzi66ri85sz8x0m6mainwnjyvppbv7-bruteforce-luks-1.4.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/br/bruteforce-luks/package.nix:35`
- **Outputs**:
  - `out`:  `/nix/store/45yzi66ri85sz8x0m6mainwnjyvppbv7-bruteforce-luks-1.4.1`

## 🔗 Dependencies

- [[1cf30rqh1l6riqd4fvmdxb8djvz0pj8g-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[ldd4j97x2kbkkgfbcnwb4nks2sipw70j-cryptsetup-2.8.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:47:31 UTC*
