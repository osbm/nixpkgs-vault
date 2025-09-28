---
aliases:
  - pari
tags:
  - license/unknown
  - maintainers/timokau
  - maintainers/7c6f434c
  - maintainers/collares
  - outputs/out
---

# pari

## 📝 Description

PARI/GP is a widely used computer algebra system designed for fast
computations in number theory (factorizations, algebraic number theory,
elliptic curves...), but also contains a large number of other useful
functions to compute with mathematical entities such as matrices,
polynomials, power series, algebraic numbers etc., and a lot of
transcendental functions. PARI is also available as a C library to allow
for faster computations.

Originally developed by Henri Cohen and his co-workers (Université
Bordeaux I, France), PARI is now under the GPL and maintained by Karim
Belabas with the help of many volunteer contributors.

- PARI is a C library, allowing fast computations.
- gp is an easy-to-use interactive shell giving access to the PARI
  functions.
- GP is the name of gp's scripting language.
- gp2c, the GP-to-C compiler, combines the best of both worlds by
  compiling GP scripts to the C language and transparently loading the
  resulting functions into gp. (gp2c-compiled scripts will typically run
  3 or 4 times faster.) gp2c currently only understands a subset of the
  GP language.


## 📋 Package Information

- **Name**: `pari`
- **Version**: `2.17.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Computer algebra system for high-performance number theory computations
- **Homepage**: [http://pari.math.u-bordeaux.fr](http://pari.math.u-bordeaux.fr)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`
## 👥 Maintainers

- @timokau
- @7c6f434c
- @collares


## 🔧 Build Information

- **Derivation Path**: `/nix/store/g50yz3wdy1hg5vy36a7r81jwvifs4acg-pari-2.17.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/pa/pari/package.nix:55`
- **Outputs**:
  - `out`:  `/nix/store/g50yz3wdy1hg5vy36a7r81jwvifs4acg-pari-2.17.2`

## 🔗 Dependencies

- [[5fnl19ibazlhzcrmxg56s11v29rw1cqc-gmp-with-cxx-6.3.0]]
- [[6cgbpl3cspg2qm292xd3phnvj19f1mgg-pari-2.17.2.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gv9xbvn8lh8dqh8sa0ddf135kramc0h4-texlive-2025-env]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[nncd4f9vl1alqwmiff6a138ppbsgbp5l-libx11-1.8.12]]
- [[nxxwbr9r6d0lmdinjlwnxcx15sh4sdh2-libpthread-stubs-0.5]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pp99kqhfn7z3a58pjkv4kiyrs62k0bj4-readline-8.3p1]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:11:57 UTC*
