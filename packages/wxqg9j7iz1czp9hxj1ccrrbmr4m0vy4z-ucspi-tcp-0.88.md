---
aliases:
  - ucspi-tcp
tags:
  - license/unknown
  - maintainers/bjornfor
  - outputs/out
---

# ucspi-tcp

## 📝 Description

tcpserver waits for incoming connections and, for each connection, runs a
program of your choice. Your program receives environment variables
showing the local and remote host names, IP addresses, and port numbers.

tcpserver offers a concurrency limit to protect you from running out of
processes and memory. When you are handling 40 (by default) simultaneous
connections, tcpserver smoothly defers acceptance of new connections.

tcpserver also provides TCP access control features, similar to
tcp-wrappers/tcpd's hosts.allow but much faster. Its access control rules
are compiled into a hashed format with cdb, so it can easily deal with
thousands of different hosts.

This package includes a recordio tool that monitors all the input and
output of a server.

tcpclient makes a TCP connection and runs a program of your choice. It
sets up the same environment variables as tcpserver.

This package includes several sample clients built on top of tcpclient:
who@, date@, finger@, http@, tcpcat, and mconnect.

tcpserver and tcpclient conform to UCSPI, the UNIX Client-Server Program
Interface, using the TCP protocol. UCSPI tools are available for several
different networks.


## 📋 Package Information

- **Name**: `ucspi-tcp`
- **Version**: `0.88`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Command-line tools for building TCP client-server applications
- **Homepage**: [http://cr.yp.to/ucspi-tcp.html](http://cr.yp.to/ucspi-tcp.html)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @bjornfor


## 🔧 Build Information

- **Derivation Path**: `/nix/store/wxqg9j7iz1czp9hxj1ccrrbmr4m0vy4z-ucspi-tcp-0.88.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/uc/ucspi-tcp/package.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/wxqg9j7iz1czp9hxj1ccrrbmr4m0vy4z-ucspi-tcp-0.88`

## 🔗 Dependencies

- [[0w7alw45rrq5cxn6m8p02cwnsvridfvi-ucspi-tcp-0.88.tar.gz]]
- [[6wlib91hn64wl2a782ykbb24pn9ny0ja-quilt-0.69]]
- [[8fhfy2zrfn6q749h3x819pvmygw1wsy6-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/mjpf8by850500yiix6w19dw26b7paz49-remove-setuid.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:17:55 UTC*
