---
aliases:
  - grap
tags:
  - license/unknown
  - maintainers/s1341
  - outputs/out
---

# grap

## 📝 Description

grap takes patterns and binary files, uses a Casptone-based disassembler to obtain the control flow graphs from the binaries, then matches the patterns against them.

Patterns are user-defined graphs with instruction conditions ("opcode is xor and arg1 is eax") and repetition conditions (3 identical instructions, basic blocks...).


## 📋 Package Information

- **Name**: `grap`
- **Version**: `1.3.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Define and match graph patterns within binaries
- **Homepage**: [https://github.com/QuoSecGmbH/grap/](https://github.com/QuoSecGmbH/grap/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @s1341


## 🔧 Build Information

- **Derivation Path**: `/nix/store/a1nf26348z5xscjv2r5f7cg0z7iicazz-grap-1.3.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/gr/grap/package.nix:71`
- **Outputs**:
  - `out`:  `/nix/store/a1nf26348z5xscjv2r5f7cg0z7iicazz-grap-1.3.1`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[0y20y5glzrd67xskzh9vjindzjl1jiiv-bison-3.8.2]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[2y97hhlh6kk73xb67449m8406vymdp5q-swig-4.3.1]]
- [[3c6mwh608vh6hr56vgds5bg822vywia1-python3.13-capstone-5.0.6]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[8kddch1s9v0nnvgh3w84lcafrgdwqixs-source]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[jvk6w0wmh9f50wh0xr7mb7faz9ipbmzv-libseccomp-2.6.0]]
- [[p41b5q1rba7lsb41wfazs52fq0xgq67a-boost-1.83.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[wy61x67y125m36dp7l7xhzqbi30mxg1d-flex-2.6.4]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:56:13 UTC*
