---
aliases:
  - pies
tags:
  - license/unknown
  - outputs/out
---

# pies

## 📝 Description

The name Pies (pronounced "p-yes") stands for Program Invocation and
Execution Supervisor.  This utility starts and controls execution of
external programs, called components.  Each component is a
stand-alone program, which is executed in the foreground.  Upon
startup, pies reads the list of components from its configuration
file, starts them, and remains in the background, controlling their
execution.  If any of the components terminates, the default action
of Pies is to restart it.  However, it can also be programmed to
perform a variety of another actions such as, e.g., sending mail
notifications to the system administrator, invoking another external
program, etc.

Pies can be used for a wide variety of tasks.  Its most obious use
is to put in backgound a program which normally cannot detach itself
from the controlling terminal, such as, e.g., minicom.  It can
launch and control components of some complex system, such as
Jabberd or MeTA1 (and it offers much more control over them than the
native utilities).  Finally, it can replace the inetd utility!


## 📋 Package Information

- **Name**: `pies`
- **Version**: `1.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Program invocation and execution supervisor
- **Homepage**: [https://www.gnu.org/software/pies/](https://www.gnu.org/software/pies/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `powerpc64-linux`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/pcq5av345jhqzv5j2vixba3hh40kjam8-pies-1.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/pi/pies/package.nix:37`
- **Outputs**:
  - `out`:  `/nix/store/pcq5av345jhqzv5j2vixba3hh40kjam8-pies-1.8`

## 🔗 Dependencies

- [[3kgj31l4fhkbp0s74bzl7zvrr1v6aymc-libxcrypt-4.4.38]]
- [[ayjainkajdl0x1ngciw6nvghp7si5cp9-pies-1.8.tar.bz2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lzvy25g887aypn07ah8igv72z7b9jb88-version-check-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/sriq99w3q037zfqxidg5lc8g7iibxvf1-stdlib.patch`

---
*Generated on 2025-09-27 12:13:07 UTC*
