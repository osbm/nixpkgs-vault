---
aliases:
  - signing-party
tags:
  - license/unknown
  - outputs/out
---

# signing-party

## 📝 Description

This is a collection of several projects relating to OpenPGP.

* caff: CA - Fire and Forget signs and mails a key
* pgp-clean: removes all non-self signatures from key
* pgp-fixkey: removes broken packets from keys
* gpg-mailkeys: simply mail out a signed key to its owner
* gpg-key2ps: generate PostScript file with fingerprint paper slips
* gpgdir: recursive directory encryption tool
* gpglist: show who signed which of your UIDs
* gpgsigs: annotates list of GnuPG keys with already done signatures
* gpgparticipants: create list of party participants for the organiser
* gpgwrap: a passphrase wrapper
* keyanalyze: minimum signing distance (MSD) analysis on keyrings
* keylookup: ncurses wrapper around gpg --search
* sig2dot: converts a list of GnuPG signatures to a .dot file
* springgraph: creates a graph from a .dot file
* keyart: creates a random ASCII art of a PGP key file
* gpg-key2latex: generate LaTeX file with fingerprint paper slips


## 📋 Package Information

- **Name**: `signing-party`
- **Version**: `2.12`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Collection of several projects relating to OpenPGP
- **Homepage**: [https://salsa.debian.org/signing-party-team/signing-party](https://salsa.debian.org/signing-party-team/signing-party)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/p1vsxdyzc2z7sz9imldl8cz2290dzlii-signing-party-2.12.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/si/signing-party/package.nix:282`
- **Outputs**:
  - `out`:  `/nix/store/p1vsxdyzc2z7sz9imldl8cz2290dzlii-signing-party-2.12`

## 🔗 Dependencies

- [[1d4p5lghpjz9qk6khrd5y82mlrsbyjd4-perl5.40.0-Type-Tiny-2.004000]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[3rs33xr70id093hd7dbvbjq5kzy3ynw1-perl5.40.0-MooX-HandlesVia-0.001009]]
- [[3s2y47nkgsj8z2fvpf2qp8j5rsmcrbl0-perl5.40.0-Moo-2.005005]]
- [[4f9j67x7cgs2hzjgyyzm8q6z1w2vgy41-which-2.23]]
- [[4s4hsciaii84dybkks7197r4abbz4002-perl5.40.0-List-MoreUtils-0.430]]
- [[4xny87xg674as6n4kbvwxpxx6ndlghsw-perl5.40.0-Role-Tiny-2.002004]]
- [[53rax8gkbd6wdahk7qj29yf5p29xlqr0-perl5.40.0-strictures-2.000006]]
- [[59n9fvf3a6qiws86ln6qdn4kjvcpwz5k-perl5.40.0-Exporter-Tiny-1.006002]]
- [[5srjrlnf3jgp3xg6gwrxb6ffdcj2s41q-libmd-1.1.0]]
- [[6i2jic85krpll6jsyclwwsh617n61m3d-gnupg-2.4.8]]
- [[7ys6vrd29swy0hb42rbhrc1sbsk4cq1g-autoconf-2.72]]
- [[82mw0nl5kb1zw36l4s4d0pdlfiadwlss-automake-1.18.1]]
- [[8qnbzfzx02j770il3g1smvq4rxp4jnb9-libpaper-1.1.29]]
- [[8r2n82xj8b05nck29haqd625r4p2kc9h-perl5.40.0-Sub-HandlesVia-0.050002]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[csk1qxzhy8scvc130x53mdf9x8kd8wbw-perl5.40.0-MooX-late-0.100]]
- [[dcybgxh4sds246fbng8fv7awjzpd26xh-perl5.40.0-TermReadKey-2.38]]
- [[fna1p0p5wr0ppjnshbmm8jgjardziiy7-perl5.40.0-Net-IDN-Encode-2.500]]
- [[gi5izcpszaxq8y1rkkzn00kyx2rc2fnq-net-tools-2.10]]
- [[hdi5xgpykksz4k7pnhcpyslfr0398wrh-perl5.40.0-Data-Perl-0.002011]]
- [[hg8wsz2fdfqpkm2i9il87a2cyv210rc2-perl5.40.0-Sub-Quote-2.006008]]
- [[hgsh06x9zdac32x8f363qkdl07b6nrws-perl5.40.0-GD-2.78]]
- [[isw1asi5gp2jx21hfmgwrcbn6v4mc9ma-perl5.40.0-Module-Runtime-0.016]]
- [[jzq86186295dpzc1kla8kcnf3q8zh4gf-perl5.40.0-Devel-GlobalDestruction-0.14]]
- [[knsk3jqy3103rdvf42mzphb791sjxj2x-perl5.40.0-MIME-tools-5.509]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lsnzp611jmq3v6nidm8kdlf5kz2yjrwa-perl5.40.0-Sub-Exporter-Progressive-0.001013]]
- [[n5lii7y4b1nk1xh65dg4lvw5d92y4j9m-perl5.40.0-TimeDate-2.33]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q6r8nhgmx37s1vk3580hn9q1illlh9n2-getopt-1.1.6]]
- [[r0qxr4sy92jcla5cnhmvf54qrhy309yz-perl5.40.0-Class-Method-Modifiers-2.15]]
- [[s1nqf2zii8irfqcpdi41xv50sj0mi5si-source]]
- [[srn1q9vs249d62bcsq23rjldlazz826m-perl5.40.0-MailTools-2.21]]
- [[vnpb22cfkp6kwrjbsnbax644n443qqbi-perl5.40.0-GnuPG-Interface-1.03]]
- [[wakzvngavq71gljvrwdxj50arkfawi57-perl5.40.0-Text-Template-1.61]]
- [[y6rxbpi3z6ya4ririq1h4id0m9k1s53l-qprint-1.1]]

## 📁 Input Sources

- `/nix/store/a14g56fk4i8saf578pd9n0284vqdvgx9-gpgwrap_makefile.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:09:20 UTC*
