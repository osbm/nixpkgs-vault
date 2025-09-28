---
aliases:
  - libtirpc
tags:
  - license/unknown
  - outputs/dev
  - outputs/out
---

# libtirpc

## 📝 Description

Currently, NFS commands use the SunRPC routines provided by the
glibc.  These routines do not support IPv6 addresses.  Ulrich
Drepper, who is the maintainer of the glibc, refuses any change in
the glibc concerning the RPC.  He wants the RPC to become a separate
library.  Other OS (NetBSD, FreeBSD, Solarix, HP-UX, AIX) have
migrated their SunRPC library to a TI-RPC (Transport Independent
RPC) implementation.  This implementation allows the support of
other transports than UDP and TCP over IPv4.  FreeBSD provides a
TI-RPC library ported from NetBSD with improvements.  This library
already supports IPv6.  So, the FreeBSD release 5.2.1 TI-RPC has
been ported to replace the SunRPC of the glibc.


## 📋 Package Information

- **Name**: `libtirpc`
- **Version**: `1.3.6`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Transport-independent Sun RPC implementation (TI-RPC)
- **Homepage**: [https://sourceforge.net/projects/libtirpc/](https://sourceforge.net/projects/libtirpc/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/kd70yhxsscpb21f13h35vfnav448gr49-libtirpc-1.3.6.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libtirpc/package.nix:49`
- **Outputs**:
  - `dev`:  `/nix/store/kd70yhxsscpb21f13h35vfnav448gr49-libtirpc-1.3.6`
  - `out`:  `/nix/store/kd70yhxsscpb21f13h35vfnav448gr49-libtirpc-1.3.6`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qy3jk16bbdpn9kikcmkf24x0hry64nqi-libtirpc-1.3.6.tar.gz]]
- [[wnzrwrpjmgimdq9m4galpniq3lsxcspz-krb5-1.22.1]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:02:45 UTC*
