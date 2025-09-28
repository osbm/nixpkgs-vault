---
aliases:
  - prooftree
tags:
  - license/unknown
  - maintainers/jwiegley
  - outputs/out
---

# prooftree

## 📝 Description

Prooftree is a program for proof-tree visualization during interactive
proof development in a theorem prover. It is currently being developed
for Coq and Proof General. Prooftree helps against getting lost between
different subgoals in interactive proof development. It clearly shows
where the current subgoal comes from and thus helps in developing the
right plan for solving it.

Prooftree uses different colors for the already proven subgoals, the
current branch in the proof and the still open subgoals. Sequent texts
are not displayed in the proof tree itself, but they are shown as a
tool-tip when the mouse rests over a sequent symbol. Long proof commands
are abbreviated in the tree display, but show up in full length as
tool-tip. Both, sequents and proof commands, can be shown in the display
below the tree (on single click) or in a separate window (on double or
shift-click).


## 📋 Package Information

- **Name**: `prooftree`
- **Version**: `0.14`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Program for proof-tree visualization
- **Homepage**: [http://askra.de/software/prooftree](http://askra.de/software/prooftree)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @jwiegley


## 🔧 Build Information

- **Derivation Path**: `/nix/store/8sygpz79xi2vl8ks9drxj68dcbmgw9pm-prooftree-0.14.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/applications/science/logic/prooftree/default.nix:34`
- **Outputs**:
  - `out`:  `/nix/store/8sygpz79xi2vl8ks9drxj68dcbmgw9pm-prooftree-0.14`

## 🔗 Dependencies

- [[07ibz960h67sh75myg0327zwbh4b6zmq-ocaml4.12.1-camlp5-8.03.02]]
- [[18fgh5xv7jgwm76nhf5w26ap3isqm3mw-ocaml-4.12.1]]
- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[939rs7jw5wpw3qpg1i6qvqhy3rbb6m6w-prooftree-0.14.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[wdvdmnlg5f5mmm9qfz6rpphdqzdba669-ocaml4.12.1-findlib-1.9.8]]
- [[x62ngg63nx2fbbymzxpsfpd8pw9jjkl8-ocaml4.12.1-lablgtk-2.18.13]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:31:26 UTC*
