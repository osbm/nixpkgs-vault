---
aliases:
  - shorewall
tags:
  - license/unknown
  - outputs/out
---

# shorewall

## 📝 Description

Shorewall is a high-level tool for configuring Netfilter. You describe your
firewall/gateway requirements using entries in a set of configuration
files. Shorewall reads those configuration files and with the help of the
iptables, iptables-restore, ip and tc utilities, Shorewall configures
Netfilter and the Linux networking subsystem to match your requirements.
Shorewall can be used on a dedicated firewall system, a multi-function
gateway/router/server or on a standalone GNU/Linux system. Shorewall does
not use Netfilter's ipchains compatibility mode and can thus take
advantage of Netfilter's connection state tracking capabilities.


## 📋 Package Information

- **Name**: `shorewall`
- **Version**: `5.2.3.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: IP gateway/firewall configuration tool for GNU/Linux
- **Homepage**: [http://www.shorewall.net/](http://www.shorewall.net/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/lin0i8b8hbyqzfssyl6afb77rc1mrsqy-shorewall-5.2.3.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sh/shorewall/package.nix:111`
- **Outputs**:
  - `out`:  `/nix/store/lin0i8b8hbyqzfssyl6afb77rc1mrsqy-shorewall-5.2.3.3`

## 🔗 Dependencies

- [[28y8w2p8zpla09hp1m0a2q3p2j90287w-shorewall-core-5.2.3.3.tar.bz2]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[5phhm6xjhjfk6v0qp6ajw9g6082j5990-shorewall6-5.2.3.3.tar.bz2]]
- [[9qnjgd5vx73f8ibl1fpjhzvkyfawrwfj-iptables-1.8.11]]
- [[9zshxf6kk537mzc627ynbj5lgp1qff15-util-linux-2.41.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[c9h7xb44g181dq5z1r6bghn45d8lr9al-shorewall-5.2.3.3.tar.bz2]]
- [[cflrzgbglppcagf2jfix9hgq25126m9z-gnugrep-3.12]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[mc983csj0fvcg5gf5gwhvmi4a9v3jajq-iproute2-6.16.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[whmvyjphw10d78zfrb04kqjlc0dy68z3-gnused-4.9]]
- [[zqiiqljlybjxb4mnffiiv2qjkwsiw0q8-perl5.40.0-Digest-SHA1-2.13]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:08:16 UTC*
