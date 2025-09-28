---
aliases:
  - tcp_wrappers
tags:
  - license/unknown
  - outputs/out
---

# tcp_wrappers

## 📝 Description

Wietse Venema's network logger, also known as TCPD or LOG_TCP.
These programs log the client host name of incoming telnet, ftp,
rsh, rlogin, finger etc. requests.  Security options are: access
control per host, domain and/or service; detection of host name
spoofing or host address spoofing; booby traps to implement an
early-warning system.  The current version supports the System
V.4 TLI network programming interface (Solaris, DG/UX) in
addition to the traditional BSD sockets.


## 📋 Package Information

- **Name**: `tcp_wrappers`
- **Version**: `7.6.q-33`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: TCP Wrappers, a network logger, also known as TCPD or LOG_TCP
- **Homepage**: [ftp://ftp.porcupine.org/pub/security/index.html](ftp://ftp.porcupine.org/pub/security/index.html)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/ljmydk5jhqwsx4cza4db78rk0kcfpvmr-tcp-wrappers-7.6.q-33.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/tc/tcp_wrappers/package.nix:63`
- **Outputs**:
  - `out`:  `/nix/store/ljmydk5jhqwsx4cza4db78rk0kcfpvmr-tcp-wrappers-7.6.q-33`

## 🔗 Dependencies

- [[4v8qf669gm1gk6b8q48rp07brskz0m12-tcp-wrappers_7.6.q.orig.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[iysn6wi14lf181fpwaxfgx9micgjlc3w-tcp-wrappers_7.6.q-33.debian.tar.xz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[sd1wyhfmwdllqbjy5ksp0fzjqd17z97i-libnsl-2.0.1]]

## 📁 Input Sources

- `/nix/store/cnhjby1i1ss5avmqgmrrsgirbwxs0qpc-cdecls.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:04:41 UTC*
