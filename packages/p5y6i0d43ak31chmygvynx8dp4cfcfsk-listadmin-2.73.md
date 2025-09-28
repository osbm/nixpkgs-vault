---
aliases:
  - listadmin
tags:
  - license/unknown
  - maintainers/nomeata
  - outputs/out
---

# listadmin

## 📝 Description

listadmin is a command line tool to manipulate the queues of messages
held for moderator approval by mailman. It is designed to keep user
interaction to a minimum, in theory you could run it from cron to prune
the queue. It can use the score from a header added by SpamAssassin to
filter, or it can match specific senders, subjects, or reasons.


## 📋 Package Information

- **Name**: `listadmin`
- **Version**: `2.73`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Command line mailman moderator queue manipulation
- **Homepage**: [https://sourceforge.net/projects/listadmin/](https://sourceforge.net/projects/listadmin/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @nomeata


## 🔧 Build Information

- **Derivation Path**: `/nix/store/p5y6i0d43ak31chmygvynx8dp4cfcfsk-listadmin-2.73.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/listadmin/package.nix:50`
- **Outputs**:
  - `out`:  `/nix/store/p5y6i0d43ak31chmygvynx8dp4cfcfsk-listadmin-2.73`

## 🔗 Dependencies

- [[03s7c3xk0cmlqc17zll4199xvj7gl1sx-perl5.40.0-Net-INET6Glue-0.604]]
- [[19h9aidban2f7d930fsf9jiwiwf90s0s-perl5.40.0-libwww-perl-6.72]]
- [[1nrxibs30119flwnrds4wbfkmmsrxqw1-perl5.40.0-File-Listing-6.16]]
- [[1ww1xr211c4c5aqzgzsk8p7258mi6qx3-perl5.40.0-Mozilla-CA-20230821]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[4bi6scsk9zihlvzwkvz7h7yg5r92c97j-perl5.40.0-Clone-0.46]]
- [[4ggmmaz96iznkln4990pdfigsnsi5vl7-perl5.40.0-HTML-Tagset-3.20]]
- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[75a4kav1hsxmg1sja8sjsmh75scv6r4h-perl5.40.0-HTTP-Cookies-6.10]]
- [[7xxwyy45phx4y8i57f0s1ayxvqci0jvv-perl5.40.0-URI-5.21]]
- [[97xq1z09p82q73ysw05b6yb49vcnvmf2-perl5.40.0-Net-SSLeay-1.92]]
- [[9mb6g46hns9himibbyjav0q9bkpknc0d-perl5.40.0-IO-Socket-SSL-2.083]]
- [[bjgc9p4wffirvgp0wj2s6wxb4jlvvld1-listadmin-2.73.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gcsmpda2x5wmh0z494756sf0shk2qd71-perl5.40.0-LWP-Protocol-https-6.11]]
- [[j7gxy3359pbnn9sgds98qfa8v84lxfrh-perl5.40.0-HTTP-Date-6.06]]
- [[jg44bq1nkj2jw4jksqlvpbip55z4d59r-perl5.40.0-WWW-RobotRules-6.02]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lwl0b9gy8l7r0afvb5j9lzvr69vkqbal-perl5.40.0-HTML-Parser-3.81]]
- [[mf7flvnaw64a73m4d0cs7qy42qapdq2r-perl5.40.0-Text-Reform-1.20]]
- [[n5lii7y4b1nk1xh65dg4lvw5d92y4j9m-perl5.40.0-TimeDate-2.33]]
- [[pmqrfw6g8vn1jlyb184xxsazg3cmp84q-perl5.40.0-Net-HTTP-6.23]]
- [[qfl1wjxrcshqcbv5i0zhbs1bpay9ivck-perl5.40.0-HTTP-Negotiate-6.01]]
- [[sk7hsnfadb0z6zry6j6afbbkhmag5k3s-perl5.40.0-HTTP-CookieJar-0.014]]
- [[v7fq90f3gm3bqaj7ynsdij4wm5g9ac81-perl5.40.0-Try-Tiny-0.31]]
- [[vbk5sg0cbm5p2dngrnqjs7d50d171qj8-perl5.40.0-IO-HTML-1.004]]
- [[vcj5qkzdn6nky17xscc6qmax9grgp1vk-perl5.40.0-LWP-MediaTypes-6.04]]
- [[vqd433c35v8x4k6dwzklcsmpixmrqsa4-perl5.40.0-Encode-Locale-1.05]]
- [[z4f1zlj7r2571kc76gfm4ysi29082mcq-perl5.40.0-HTTP-Message-6.45]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:13:00 UTC*
