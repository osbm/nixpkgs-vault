---
aliases:
  - frr
tags:
  - license/unknown
  - maintainers/woffs
  - maintainers/thillux
  - outputs/out
---

# frr

## 📝 Description

FRRouting (FRR) is a free and open source Internet routing protocol suite
for Linux and Unix platforms. It implements BGP, OSPF, RIP, IS-IS, PIM,
LDP, BFD, Babel, PBR, OpenFabric and VRRP, with alpha support for EIGRP
and NHRP.

FRR’s seamless integration with native Linux/Unix IP networking stacks
makes it a general purpose routing stack applicable to a wide variety of
use cases including connecting hosts/VMs/containers to the network,
advertising network services, LAN switching and routing, Internet access
routers, and Internet peering.

FRR has its roots in the Quagga project. In fact, it was started by many
long-time Quagga developers who combined their efforts to improve on
Quagga’s well-established foundation in order to create the best routing
protocol stack available. We invite you to participate in the FRRouting
community and help shape the future of networking.

Join the ranks of network architects using FRR for ISPs, SaaS
infrastructure, web 2.0 businesses, hyperscale services, and Fortune 500
private clouds.


## 📋 Package Information

- **Name**: `frr`
- **Version**: `10.4.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: FRR BGP/OSPF/ISIS/RIP/RIPNG routing daemon suite
- **Homepage**: [https://frrouting.org/](https://frrouting.org/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`
## 👥 Maintainers

- @woffs
- @thillux


## 🔧 Build Information

- **Derivation Path**: `/nix/store/8ym2zbsmgmhlvb84pzy8m91vlcqnbiyb-frr-10.4.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/fr/frr/package.nix:226`
- **Outputs**:
  - `out`:  `/nix/store/8ym2zbsmgmhlvb84pzy8m91vlcqnbiyb-frr-10.4.1`

## 🔗 Dependencies

- [[0y20y5glzrd67xskzh9vjindzjl1jiiv-bison-3.8.2]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[4yskzh19ypsp1j8nad948a4cz8yf0gx2-rtrlib-0.8.0]]
- [[65b700yjvj1li2wr21ihbyqv9dibwyp3-net-snmp-5.9.4]]
- [[778k2csi3cc3hcfa4rn5x94fprhrj7vd-libcap-2.76]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[96vv66p4biczw55qf9jhwqn7awwn861h-elfutils-0.193]]
- [[b4pa5k4if2jl33f1ynicjwz2nihy4z3c-texinfo-7.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bsdfb2xa35m8s4g8fc3brby8xcrlr0n5-libunwind-1.8.2]]
- [[bz10m8i89jczfpr5r9wzmn91h685c771-source]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[gi5izcpszaxq8y1rkkzn00kyx2rc2fnq-net-tools-2.10]]
- [[iqixdf5yqz4523nj00sna002f2rpgdlk-c-ares-1.34.5]]
- [[izjrwizjx9aif73k8wmnxbnwl8p11jfh-pcre2-10.44]]
- [[jck0dxj37g3s35g1b1rmfpk5xas10ydj-json-c-0.18]]
- [[jrpjbaj5dm8dnfcyvh4akyhfmq0cxbm9-linux-pam-1.7.1]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lrbclcph1hpv5j144lgma5lmswj2c48l-python3.13-pytest-8.4.1]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[mxniklnk1kcl8j655vnk3wcw1zd2hykj-python3.13-sphinx-8.2.3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pp99kqhfn7z3a58pjkv4kiyrs62k0bj4-readline-8.3p1]]
- [[qw4hj6w126bkmichrjrizwa6cqfaavbi-protobuf-c-1.5.2]]
- [[s52hi1zgglc4ly2nxl4lvqyaxma9ii2w-libyang-3.13.5]]
- [[wy61x67y125m36dp7l7xhzqbi30mxg1d-flex-2.6.4]]
- [[x9inmp90rwc9n6sg3s1lvfhbxh9lqcv6-frr-clippy-helper-10.4.1]]
- [[zjvcv40pq35s9hsjag9kbg9n896914d3-zeromq-4.3.5]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:51:35 UTC*
