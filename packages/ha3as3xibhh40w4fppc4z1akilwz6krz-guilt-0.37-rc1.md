---
aliases:
  - guilt
tags:
  - license/unknown
  - maintainers/JaviMerino
  - outputs/out
---

# guilt

## 📝 Description

Andrew Morton originally developed a set of scripts for
maintaining kernel patches outside of any SCM tool. Others
extended these into a suite called quilt]. The basic idea behind
quilt is to maintain patches instead of maintaining source
files. Patches can be added, removed or reordered, and they can
be refreshed as you fix bugs or update to a new base
revision. quilt is very powerful, but it is not integrated with
the underlying SCM tools. This makes it difficult to visualize
your changes.

Guilt allows one to use quilt functionality on top of a Git
repository. Changes are maintained as patches which are
committed into Git. Commits can be removed or reordered, and the
underlying patch can be refreshed based on changes made in the
working directory. The patch directory can also be placed under
revision control, so you can have a separate history of changes
made to your patches.


## 📋 Package Information

- **Name**: `guilt`
- **Version**: `0.37-rc1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Manage patches like quilt, on top of a git repository
- **Homepage**: [https://github.com/jeffpc/guilt](https://github.com/jeffpc/guilt)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @JaviMerino


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ha3as3xibhh40w4fppc4z1akilwz6krz-guilt-0.37-rc1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/gu/guilt/package.nix:69`
- **Outputs**:
  - `out`:  `/nix/store/ha3as3xibhh40w4fppc4z1akilwz6krz-guilt-0.37-rc1`

## 🔗 Dependencies

- [[04sxd1ncbv87d14flich8a6g06jbyw6c-docbook-xsl-nons-1.79.2]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dil6p2zn6xgiwrbd252ck5bl9cc2x3gc-docbook-xml-4.5]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[mfjhdh9n1vnbh1ap03wwqrk51dxlc49d-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q331wl66bksvjp5qq0b3dhbcw3fx09x2-gawk-5.3.2]]
- [[whmvyjphw10d78zfrb04kqjlc0dy68z3-gnused-4.9]]
- [[yvzr26fvdmxmb2pwmq6c0qv771pjpvmz-asciidoc-10.2.1]]
- [[yyw6nzfcdckb36blm5mf5b5mss1m9asq-git-2.51.0]]
- [[zplsmx347bxzf7lb50gzykw5fsqfd5yj-xmlto-0.0.29]]

## 📁 Input Sources

- `/nix/store/23xjqwcff0rq0jwzi1i6rg8xd8b0zzcz-darwin-fix.patch`
- `/nix/store/anlfi5g4nbkjz3dqzfdqd32g33y72n59-guilt-help-mandir.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:01:54 UTC*
