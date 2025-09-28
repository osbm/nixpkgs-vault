---
aliases:
  - ledger2beancount
tags:
  - license/unknown
  - maintainers/Pablo1107
  - outputs/out
---

# ledger2beancount

## 📝 Description

A script to automatically convert Ledger-based textual ledgers to Beancount ones.

Conversion is based on (concrete) syntax, so that information that is not meaningful for accounting reasons but still valuable (e.g., comments, formatting, etc.) can be preserved.


## 📋 Package Information

- **Name**: `ledger2beancount`
- **Version**: `2.7`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Ledger to Beancount text-based converter
- **Homepage**: [https://github.com/beancount/ledger2beancount](https://github.com/beancount/ledger2beancount)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @Pablo1107


## 🔧 Build Information

- **Derivation Path**: `/nix/store/lb6x106g68fdh3q0vpihzw1n7dhndjah-ledger2beancount-2.7.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/le/ledger2beancount/package.nix:58`
- **Outputs**:
  - `out`:  `/nix/store/lb6x106g68fdh3q0vpihzw1n7dhndjah-ledger2beancount-2.7`

## 🔗 Dependencies

- [[15yjpbdhks461r3jvngbl5izpbwl6blz-perl5.40.0-PadWalker-2.5]]
- [[1srnsyzxq5ifw5qwxfmxk4j7ngdq3kjx-perl5.40.0-Class-Singleton-1.6]]
- [[21p07dfm93wcs45k723winsa4f8lk567-perl5.40.0-DateTime-Format-Strptime-1.79]]
- [[24g4mfqp2szkllmg4ng0lpmnzkvmdnck-python3.13-beancount-3.2.0]]
- [[2gjh1kw1my9g614ar2yn1f94s95w6i3x-perl5.40.0-File-BaseDir-0.09]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[3xsfyx4bn8ig1rl29jfx24r3fx03qp7y-perl5.40.0-Sub-Identify-0.14]]
- [[3zwaws2lirkxcqfjvjjg2jm1dadqm7gh-perl5.40.0-YAML-LibYAML-0.89]]
- [[4s4hsciaii84dybkks7197r4abbz4002-perl5.40.0-List-MoreUtils-0.430]]
- [[4xny87xg674as6n4kbvwxpxx6ndlghsw-perl5.40.0-Role-Tiny-2.002004]]
- [[59n9fvf3a6qiws86ln6qdn4kjvcpwz5k-perl5.40.0-Exporter-Tiny-1.006002]]
- [[6zwsy24a5m773k849yzzcqn3xvvfyrn9-perl5.40.0-Getopt-Long-Descriptive-0.114]]
- [[7sw3v8zjv3578ms389d4ccl6830gi1fa-perl5.40.0-namespace-autoclean-0.29]]
- [[8km3643kn1749shnin4l8qd2ap9gchh5-perl5.40.0-namespace-clean-0.27]]
- [[8w7r5yihhlwxvxzliibn2hliypcwkhrj-perl5.40.0-String-Interpolate-0.33]]
- [[9aabqqf8an901x1vwp2qyw31p72gxk0i-perl5.40.0-enum-1.12]]
- [[a756ihd7qarhwy2d13vh1al1yvx9zx6b-perl5.40.0-Class-Data-Inheritable-0.09]]
- [[b3p5gkqn1az66y1qpdkb5sia6ryhvn33-perl5.40.0-MRO-Compat-0.15]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bnhn5bg9v7xmincmhshpllijbjp0290y-perl5.40.0-Sub-Install-0.929]]
- [[cahqjwhpc6xpc4v7s224cicb3xl61jcc-perl5.40.0-Params-Validate-1.31]]
- [[d24zfg02c62i3fsfl1x43ag34sghyykd-perl5.40.0-Date-Calc-6.4]]
- [[digxz0vz4vm39n1932flga1yg1by0hfq-perl5.40.0-Getopt-Long-2.58]]
- [[f8qzj9ihl577ih4hpv6zclnb1mm0kk03-perl5.40.0-DateTime-Locale-1.39]]
- [[f8yvkv8k0zax40dbaahgzrvw4gvp0b3l-perl5.40.0-Package-Stash-0.40]]
- [[fi2j9s3z1f0p8dalbvzvq275bbdfl7p9-perl5.40.0-Sub-Exporter-0.990]]
- [[gcr20q077sqxvbcrsj524fjykk23alkq-perl5.40.0-Module-Implementation-0.09]]
- [[gqa85b9khwr9g2qzv6qgaxm0k8q03nwk-perl5.40.0-Devel-StackTrace-2.04]]
- [[hg8wsz2fdfqpkm2i9il87a2cyv210rc2-perl5.40.0-Sub-Quote-2.006008]]
- [[isw1asi5gp2jx21hfmgwrcbn6v4mc9ma-perl5.40.0-Module-Runtime-0.016]]
- [[jwqmmyz2hrpa9mc0bq74sldsy1ha3adx-perl5.40.0-Params-Util-1.102]]
- [[k0z0z9ml6hv61d4bfp2znh59jig6frhh-perl5.40.0-File-ShareDir-1.118]]
- [[k6n57vvzp03f124g2lv6wwz7pjzs0dd9-perl5.40.0-Eval-Closure-0.14]]
- [[kgjcksrrqpjw3k6x16vqkz3vph89dq9c-perl5.40.0-Regexp-Common-2017060201]]
- [[ksanv8syrsdg32xfykqr3wpv83rfgc50-perl5.40.0-DateTime-TimeZone-2.60]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lkrcpjjn2iwlp2nq8gzy7cn8fpa1vs79-perl5.40.0-Data-OptList-0.114]]
- [[lsnzp611jmq3v6nidm8kdlf5kz2yjrwa-perl5.40.0-Sub-Exporter-Progressive-0.001013]]
- [[m0as1slabi35zar7c8scjb33s0lpg32b-perl5.40.0-Exception-Class-1.45]]
- [[mbhgsb9v81agz6m717ird050wq5nlwdp-perl5.40.0-Params-ValidationCompiler-0.31]]
- [[ml4v0md5236xn61k5vrsmlnyh7l5r2nq-perl5.40.0-IPC-System-Simple-1.30]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qzyda1ayzmgp45rv0k1chlmqydblsng6-perl5.40.0-Safe-Hole-0.14]]
- [[rmy5vk6mq615p5357r45jv2aicvik1sx-perl5.40.0-DateTime-1.59]]
- [[rr790a5lq8jsr301rajfs20hli67z1lr-source]]
- [[v7fq90f3gm3bqaj7ynsdij4wm5g9ac81-perl5.40.0-Try-Tiny-0.31]]
- [[vhndky27iy6jjirbvz0whicwrp9c2m7c-perl5.40.0-Bit-Vector-7.4]]
- [[w8m8avn49ibq8f687pg23bncgh5k6jpy-perl5.40.0-B-Hooks-EndOfScope-0.26]]
- [[yg8x1c84dwlfx4wdi0ndd6lfbd1q58dq-perl5.40.0-Carp-Clan-6.08]]
- [[yqhdvdklbhj7hgy2yb79aqq3s8zbyfk0-perl5.40.0-Dist-CheckConflicts-0.11]]
- [[zj7zkz4jzyqzx87j29rmdj4c8f5jkm5j-perl5.40.0-List-MoreUtils-XS-0.430]]
- [[zvbp0mbjgan5nrzk32ch5x319h2hxd96-perl5.40.0-Class-Inspector-1.36]]
- [[zxxjhxc0xx8gxbzxl9yg5ldc1bzsr287-perl5.40.0-Specio-0.48]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:14:30 UTC*
