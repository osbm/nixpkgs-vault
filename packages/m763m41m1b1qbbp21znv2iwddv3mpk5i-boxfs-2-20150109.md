---
aliases:
  - boxfs
tags:
  - license/unknown
  - outputs/out
---

# boxfs

## 📝 Description

Store files on box.com (an account is required). The first time you run
boxfs, you will need to complete the authentication (oauth2) process and
grant access to your box.com account. Just follow the instructions on
the terminal and in your browser. When you've done using your files,
unmount the file system with `fusermount -u mountpoint`.


## 📋 Package Information

- **Name**: `boxfs`
- **Version**: `2-20150109`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: FUSE file system for box.com accounts
- **Homepage**: [https://github.com/drotiro/boxfs2](https://github.com/drotiro/boxfs2)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/m763m41m1b1qbbp21znv2iwddv3mpk5i-boxfs-2-20150109.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/bo/boxfs/package.nix:68`
- **Outputs**:
  - `out`:  `/nix/store/m763m41m1b1qbbp21znv2iwddv3mpk5i-boxfs-2-20150109`

## 🔗 Dependencies

- [[3h2pqwsp2izzlynp9gjar39hm70nnz89-libxml2-2.14.5]]
- [[9rp88wlcn5fxgfgbrwl1h4d0j20pzjsk-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[carjg4s0v53fq55l8cchck5j2k1l62j1-source]]
- [[g1smgp5dhq2ii8np7vm7n5znki3ak1b1-curl-8.14.1]]
- [[ji56v9i7bdf14w53nxy71cpr8rrrvmma-fuse-2.9.9]]
- [[kk4dvm80nkq7bq9knsjqmwqhj488phh3-source]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/95ih7gvi8594cnvc663q5plzk0m4mfb9-work-around-API-borkage.patch`
- `/nix/store/bvxrcxvwmlck13bnz7cjcq9s5axb3ng1-libapp-include-ctype.diff`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:46:04 UTC*
