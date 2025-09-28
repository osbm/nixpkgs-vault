---
aliases:
  - git-crypt
tags:
  - license/unknown
  - maintainers/dochang
  - outputs/out
---

# git-crypt

## 📝 Description

git-crypt enables transparent encryption and decryption of files in a git
repository. Files which you choose to protect are encrypted when
committed, and decrypted when checked out. git-crypt lets you freely
share a repository containing a mix of public and private
content. git-crypt gracefully degrades, so developers without the secret
key can still clone and commit to a repository with encrypted files. This
lets you store your secret material (such as keys or passwords) in the
same repository as your code, without requiring you to lock down your
entire repository.


## 📋 Package Information

- **Name**: `git-crypt`
- **Version**: `0.7.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Transparent file encryption in git
- **Homepage**: [https://www.agwa.name/projects/git-crypt](https://www.agwa.name/projects/git-crypt)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @dochang


## 🔧 Build Information

- **Derivation Path**: `/nix/store/m5wzx8ivwlwwpmkrrlqhmh3qm3cr2s6i-git-crypt-0.7.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/gi/git-crypt/package.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/m5wzx8ivwlwwpmkrrlqhmh3qm3cr2s6i-git-crypt-0.7.0`

## 🔗 Dependencies

- [[04sxd1ncbv87d14flich8a6g06jbyw6c-docbook-xsl-nons-1.79.2]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[6i2jic85krpll6jsyclwwsh617n61m3d-gnupg-2.4.8]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i1kjvvwhzsz734j4gf52q3cp0zq997zn-source]]
- [[k2lm2qkl0haj7vph5sa2r97my0ah0q1b-libxslt-1.1.43]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[yyw6nzfcdckb36blm5mf5b5mss1m9asq-git-2.51.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:02:33 UTC*
