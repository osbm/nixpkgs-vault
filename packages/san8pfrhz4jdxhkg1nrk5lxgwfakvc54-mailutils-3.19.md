---
aliases:
  - mailutils
tags:
  - license/unknown
  - maintainers/orivej
  - outputs/debug
  - outputs/out
---

# mailutils

## 📝 Description

GNU Mailutils is a rich and powerful protocol-independent mail
framework.  It contains a series of useful mail libraries, clients, and
servers.  These are the primary mail utilities for the GNU system.  The
central library is capable of handling electronic mail in various
mailbox formats and protocols, both local and remote.  Specifically,
this project contains a POP3 server, an IMAP4 server, and a Sieve mail
filter.  It also provides a POSIX `mailx' client, and a collection of
other handy tools.

The GNU Mailutils libraries supply an ample set of primitives for
handling electronic mail in programs written in C, C++, Python or
Scheme.

The utilities provided by Mailutils include imap4d and pop3d mail
servers, mail reporting utility comsatd, mail filtering program sieve,
and an implementation of MH message handling system.


## 📋 Package Information

- **Name**: `mailutils`
- **Version**: `3.19`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Rich and powerful protocol-independent mail framework
- **Homepage**: [https://www.gnu.org/software/mailutils/](https://www.gnu.org/software/mailutils/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `powerpc64-linux`, `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @orivej


## 🔧 Build Information

- **Derivation Path**: `/nix/store/san8pfrhz4jdxhkg1nrk5lxgwfakvc54-mailutils-3.19.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ma/mailutils/package.nix:118`
- **Outputs**:
  - `debug`:  `/nix/store/san8pfrhz4jdxhkg1nrk5lxgwfakvc54-mailutils-3.19`
  - `out`:  `/nix/store/san8pfrhz4jdxhkg1nrk5lxgwfakvc54-mailutils-3.19`

## 🔗 Dependencies

- [[0naxaa1qv8im32fmwrk12qiwfvwwkmsn-gnutls-3.8.10]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2bbbf4kb612sdcxn5cwyx6b4ip23j0qw-fribidi-1.0.16]]
- [[3kgj31l4fhkbp0s74bzl7zvrr1v6aymc-libxcrypt-4.4.38]]
- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[a1mhws14d6nmmdhqqn2spmd87ibi254p-guile-3.0.10]]
- [[b4pa5k4if2jl33f1ynicjwz2nihy4z3c-texinfo-7.2]]
- [[bi5rxahazla8m6zv2bfq324wbak5pdkp-gsasl-2.2.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[c0xq4jfvgj5f7qnd63z8669g1nw2qqfk-gdbm-1.25]]
- [[cvwg8c4cdplr2jx9xwz65ixw7s0axqwd-mariadb-connector-c-3.3.5]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[fgn3ha82549zbm96ayhpwbq7hl8hxddb-?id=9379ec9e25ae6bdbd3d6f5ef9930ac2176d2efe7]]
- [[gi5izcpszaxq8y1rkkzn00kyx2rc2fnq-net-tools-2.10]]
- [[im8fj9igzansl8lzczcfcsrjfh5r07v3-txtiNjqcNpqOk.txt]]
- [[jrpjbaj5dm8dnfcyvh4akyhfmq0cxbm9-linux-pam-1.7.1]]
- [[k0q02j3w786a1y9cgrmycwl5ba4jz77w-mkpasswd-5.6.4]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[m0h8vm7wnxqmzy77yph902p607lx7np5-gettext-0.25.1]]
- [[m2xy0nqw9hfd4jxfnm3h80pk1jhznjab-gss-1.0.4]]
- [[nrj82imavn1b49qghphlk8qj6qm9jc5p-mailcap-2.1.54]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pp99kqhfn7z3a58pjkv4kiyrs62k0bj4-readline-8.3p1]]
- [[sp2vq01660i7gmsgddk4x9di14gwny4m-gnum4-1.4.20]]
- [[v4dbfbxcdcywcfqmns3lfklh26b35s48-dejagnu-1.6.3]]
- [[vv691ijrffczd9qdk00q7akv8g16yw35-system-sendmail-1.0]]
- [[wxriqcbz5yznmlvp5b8klflag5837q8v-mailutils-3.19.tar.xz]]

## 📁 Input Sources

- `/nix/store/3jg0gccvzihqyc2b7nsz9bk1cnsndnjy-don-t-use-descrypt-password-in-the-test-suite.patch`
- `/nix/store/9dvfqpgiiv9vq63lhnsw3hmb1jilc3r4-path-to-cat.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/r989dk196nl9frhnfsa1lb7knhbyjxw6-separate-debug-info.sh`
- `/nix/store/s91n0h9y9lmyrlazsn17q516pvalhnzz-fix-build-mb-len-max.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:09:38 UTC*
