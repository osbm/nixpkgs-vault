---
aliases:
  - pdsh
tags:
  - license/unknown
  - outputs/out
---

# pdsh

## 📝 Description

Pdsh is a high-performance, parallel remote shell utility. It has
built-in, thread-safe clients for Berkeley and Kerberos V4 rsh and
can call SSH externally (though with reduced performance). Pdsh
uses a "sliding window" parallel algorithm to conserve socket
resources on the initiating node and to allow progress to continue
while timeouts occur on some connections.


## 📋 Package Information

- **Name**: `pdsh`
- **Version**: `2.35`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: High-performance, parallel remote shell utility
- **Homepage**: [https://github.com/chaos/pdsh](https://github.com/chaos/pdsh)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/829i9r0mfqyiyfpj0hipjz2547wp9dhh-pdsh-2.35.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/tools/networking/pdsh/default.nix:55`
- **Outputs**:
  - `out`:  `/nix/store/829i9r0mfqyiyfpj0hipjz2547wp9dhh-pdsh-2.35`

## 🔗 Dependencies

- [[285jpsfl65fbd3w5qz2za3gijhjbb7ay-openssh-10.0p2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pp99kqhfn7z3a58pjkv4kiyrs62k0bj4-readline-8.3p1]]
- [[y7d75ssxxg62pk1i3qnx4006cgcf64ql-pdsh-2.35.tar.gz]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:10:40 UTC*
