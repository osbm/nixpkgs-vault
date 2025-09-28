---
aliases:
  - p910nd
tags:
  - license/unknown
  - maintainers/peterhoeg
  - outputs/out
---

# p910nd

## 📝 Description

p910nd is a small printer daemon intended for diskless platforms that
does not spool to disk but passes the job directly to the printer.
Normally a lpr daemon on a spooling host connects to it with a TCP
connection on port 910n (where n=0, 1, or 2 for lp0, 1 and 2
respectively). p910nd is particularly useful for diskless platforms.
Common Unix Printing System (CUPS) supports this protocol, it's called
the AppSocket protocol and has the scheme socket://. LPRng also supports
this protocol and the syntax is lp=remotehost%9100 in /etc/printcap.


## 📋 Package Information

- **Name**: `p910nd`
- **Version**: `0.97`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Small printer daemon passing jobs directly to the printer
- **Homepage**: [https://github.com/kenyapcomau/p910nd](https://github.com/kenyapcomau/p910nd)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @peterhoeg


## 🔧 Build Information

- **Derivation Path**: `/nix/store/yfb1ry1v3hv9v5hv04g8r18kja5cqxka-p910nd-0.97.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/p9/p910nd/package.nix:39`
- **Outputs**:
  - `out`:  `/nix/store/yfb1ry1v3hv9v5hv04g8r18kja5cqxka-p910nd-0.97`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gbkx4c3xaxcl93s84pgf5c821k2xka2p-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:05:51 UTC*
