---
aliases:
  - coccinelle
tags:
  - license/unknown
  - maintainers/thoughtpolice
  - outputs/out
---

# coccinelle

## 📝 Description

Coccinelle is a program matching and transformation engine which
provides the language SmPL (Semantic Patch Language) for
specifying desired matches and transformations in C code.
Coccinelle was initially targeted towards performing collateral
evolutions in Linux.  Such evolutions comprise the changes that
are needed in client code in response to evolutions in library
APIs, and may include modifications such as renaming a function,
adding a function argument whose value is somehow
context-dependent, and reorganizing a data structure.  Beyond
collateral evolutions, Coccinelle is successfully used (by us
and others) for finding and fixing bugs in systems code.


## 📋 Package Information

- **Name**: `coccinelle`
- **Version**: `1.3.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Program to apply semantic patches to C code
- **Homepage**: [https://coccinelle.gitlabpages.inria.fr/website/](https://coccinelle.gitlabpages.inria.fr/website/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @thoughtpolice


## 🔧 Build Information

- **Derivation Path**: `/nix/store/kgv3c69y08vwmy3bv04jv0nilcbrwxqn-coccinelle-1.3.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/tools/misc/coccinelle/default.nix:44`
- **Outputs**:
  - `out`:  `/nix/store/kgv3c69y08vwmy3bv04jv0nilcbrwxqn-coccinelle-1.3.0`

## 🔗 Dependencies

- [[4v4llz3ww50vf12hrqssdsmw7hqgmbxf-ocaml4.14.2-pcre-8.0.4]]
- [[552xrivny8mvq4qj0xp3agz75ch57mjg-ocaml4.14.2-parmap-1.2.5]]
- [[a4lyqx07bzqkqwsv1y7zxs449ix5p0gq-ocaml4.14.2-stdcompat-19]]
- [[a76sj857j4gsdr25kp3r0zjpigxyyr16-ocaml-4.14.2]]
- [[aqksm28fvmh4pz9905xv4kc59n3301pn-ocaml4.14.2-pyml-20231101]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[g78z4az4d34zyjpxk4qy7h53f9lb45fj-ocaml4.14.2-findlib-1.9.8]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qhwlpmvrafxr4fipc5skxmg7n5i8npll-ocaml4.14.2-menhir-20250903]]
- [[w49qfxv0yhidnpaifahv6lalrvb0vqgz-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:51:20 UTC*
