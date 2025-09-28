---
aliases:
  - openvswitch-dpdk
tags:
  - license/unknown
  - maintainers/adamcstephens
  - maintainers/booxter
  - maintainers/kmcopper
  - maintainers/netixx
  - maintainers/xddxdd
  - outputs/dev
  - outputs/lib
  - outputs/man
  - outputs/out
  - outputs/tools
---

# openvswitch-dpdk

## 📝 Description

Open vSwitch is a production quality, multilayer virtual switch
licensed under the open source Apache 2.0 license. It is
designed to enable massive network automation through
programmatic extension, while still supporting standard
management interfaces and protocols (e.g. NetFlow, sFlow, SPAN,
RSPAN, CLI, LACP, 802.1ag). In addition, it is designed to
support distribution across multiple physical servers similar
to VMware's vNetwork distributed vswitch or Cisco's Nexus 1000V.


## 📋 Package Information

- **Name**: `openvswitch-dpdk`
- **Version**: `3.6.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Multilayer virtual switch
- **Homepage**: [https://www.openvswitch.org/](https://www.openvswitch.org/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @adamcstephens
- @booxter
- @kmcopper
- @netixx
- @xddxdd


## 🔧 Build Information

- **Derivation Path**: `/nix/store/8vci9nkp40nil9k0j9dw2d54sqvjz78q-openvswitch-dpdk-3.6.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/op/openvswitch/package.nix:151`
- **Outputs**:
  - `dev`:  `/nix/store/8vci9nkp40nil9k0j9dw2d54sqvjz78q-openvswitch-dpdk-3.6.0`
  - `lib`:  `/nix/store/8vci9nkp40nil9k0j9dw2d54sqvjz78q-openvswitch-dpdk-3.6.0`
  - `man`:  `/nix/store/8vci9nkp40nil9k0j9dw2d54sqvjz78q-openvswitch-dpdk-3.6.0`
  - `out`:  `/nix/store/8vci9nkp40nil9k0j9dw2d54sqvjz78q-openvswitch-dpdk-3.6.0`
  - `tools`:  `/nix/store/8vci9nkp40nil9k0j9dw2d54sqvjz78q-openvswitch-dpdk-3.6.0`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[39sdjla4f1v8rqy8mxi2661928hl1vz6-source]]
- [[3hbl5ag5pybhrfl1gyim2fsamin25dnh-python3.13-netaddr-1.3.0]]
- [[4f9j67x7cgs2hzjgyyzm8q6z1w2vgy41-which-2.23]]
- [[7395sqanx3w55cy8k3y50f8i69ik8wci-libpcap-1.10.5]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[7ys6vrd29swy0hb42rbhrc1sbsk4cq1g-autoconf-2.72]]
- [[82mw0nl5kb1zw36l4s4d0pdlfiadwlss-automake-1.18.1]]
- [[9zshxf6kk537mzc627ynbj5lgp1qff15-util-linux-2.41.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gqx5l9y57nlgwaga9066jfvjbpz0bbmx-numactl-2.0.18]]
- [[i98vckc6y07sqfy14pf63d03x1ghnszv-dpdk-25.07]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lrbclcph1hpv5j144lgma5lmswj2c48l-python3.13-pytest-8.4.1]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[lxw1zfs9v3nm19mpqbllvcl3s2hkpbjq-procps-4.0.4]]
- [[mc983csj0fvcg5gf5gwhvmi4a9v3jajq-iproute2-6.16.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[p7vh0rxmwc51dr5d88mlsnsdd6211wy9-libcap-ng-0.8.5]]
- [[q0iwgclmal0ii5k8r5q8lwaqlz5z7s0c-python3.13-pyparsing-3.2.3]]
- [[sv8lxxb30bqw2b360ni6rsp89mg2dvbp-libtool-2.5.4]]
- [[v6p3j564ighp6zrdana0axf4xi3z6kh1-tcpdump-4.99.5]]
- [[xgw1wk640brg0fcp4943df77gk4qkj3p-python3.13-sphinx-hook]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/0mj5g80zk46qhk8jhfdqilw5mar2128a-disable-bash-arg-completion-test.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:01:08 UTC*
