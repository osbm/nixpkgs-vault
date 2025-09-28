---
aliases:
  - dhcping
tags:
  - license/unknown
  - outputs/out
---

# dhcping

## 📝 Description

dhcping sends either a DHCPREQUEST or DHCPINFORM packet to the server
and waits for an answer. Then, if a DHCPREQUEST was send, it will send
a DHCPRELEASE back to the server.

This program should be installed setuid root or ran by root only, as it
requires the privileges to bind itself to port 68 (bootpc). Root
privileges are dropped as soon as the program has bound itself to that
port.


## 📋 Package Information

- **Name**: `dhcping`
- **Version**: `1.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Send DHCP request to find out if a DHCP server is running
- **Homepage**: [http://www.mavetju.org/unix/general.php](http://www.mavetju.org/unix/general.php)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/3a081va3144lbfxmhl7mv0fbvxkcmj65-dhcping-1.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/dh/dhcping/package.nix:21`
- **Outputs**:
  - `out`:  `/nix/store/3a081va3144lbfxmhl7mv0fbvxkcmj65-dhcping-1.2`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[wj2rqx21j0nk427n5pzwbs86xvh1mgxx-dhcping-1.2.tar.gz]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:44:28 UTC*
