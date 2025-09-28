---
aliases:
  - ulogd
tags:
  - license/unknown
  - maintainers/p-h
  - outputs/doc
  - outputs/man
  - outputs/out
---

# ulogd

## 📝 Description

Logging daemon that reads event messages coming from the Netfilter
connection tracking, the Netfilter packet logging subsystem and from the
Netfilter accounting subsystem. You have to enable support for connection
tracking event delivery; ctnetlink and the NFLOG target in your Linux
kernel 2.6.x or load their respective modules. The deprecated ULOG target
(which has been superseded by NFLOG) is also supported.

The received messages can be logged into files or into a MySQL, SQLite3
or PostgreSQL database. IPFIX and Graphite output are also supported.


## 📋 Package Information

- **Name**: `ulogd`
- **Version**: `2.0.9`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Userspace logging daemon for netfilter/iptables
- **Homepage**: [https://www.netfilter.org/projects/ulogd/index.html](https://www.netfilter.org/projects/ulogd/index.html)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @p-h


## 🔧 Build Information

- **Derivation Path**: `/nix/store/qsbmm8jb4dmccszfzbcryfzxy7fyps24-ulogd-2.0.9.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ul/ulogd/package.nix:81`
- **Outputs**:
  - `doc`:  `/nix/store/qsbmm8jb4dmccszfzbcryfzxy7fyps24-ulogd-2.0.9`
  - `man`:  `/nix/store/qsbmm8jb4dmccszfzbcryfzxy7fyps24-ulogd-2.0.9`
  - `out`:  `/nix/store/qsbmm8jb4dmccszfzbcryfzxy7fyps24-ulogd-2.0.9`

## 🔗 Dependencies

- [[4ikqf2l4p1q7n6qypj454k476ql2h631-libnfnetlink-1.0.2]]
- [[6f2psfx7f4xqqwq4cr5gs6mz7m3p9x3m-sqlite-3.50.2]]
- [[7395sqanx3w55cy8k3y50f8i69ik8wci-libpcap-1.10.5]]
- [[7ndjwhwwbfmd2xg148zlr9i7hij2ahxa-libnetfilter_conntrack-1.1.0]]
- [[7ys6vrd29swy0hb42rbhrc1sbsk4cq1g-autoconf-2.72]]
- [[82mw0nl5kb1zw36l4s4d0pdlfiadwlss-automake-1.18.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cvwg8c4cdplr2jx9xwz65ixw7s0axqwd-mariadb-connector-c-3.3.5]]
- [[df66czicnrzsfs71c0a60lbxqyd6gfi4-libpq-17.6]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[g24i7wanr55z54qcxym2gs0y8xdc93hm-libnetfilter_acct-1.0.3]]
- [[jzpv1pwlyv0g8fq1ylgzilmip3f7v9s6-libnetfilter_log-1.0.2]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[nvg55ys5w0hcvxzsxab9ja6wh3a2g1d5-autogen-5.18.16]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[p9b4k89i63ff1nnpj7j5js131kvaxvjv-libmnl-1.0.5]]
- [[sd6j0s05x50sg7xmkk5z91gs53vns5ss-linuxdoc-tools-0.9.86]]
- [[sv8lxxb30bqw2b360ni6rsp89mg2dvbp-libtool-2.5.4]]
- [[zf1n3k5m1czc3i58l6advr5q69kmcpxi-ulogd-2.0.9.tar.xz]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:17:57 UTC*
