---
aliases:
  - keychain
tags:
  - license/unknown
  - maintainers/sigma
  - outputs/out
---

# keychain

## 📝 Description

Keychain helps you to manage SSH and GPG keys in a convenient and secure
manner. It acts as a frontend to ssh-agent and ssh-add, but allows you
to easily have one long running ssh-agent process per system, rather
than the norm of one ssh-agent per login session.

This dramatically reduces the number of times you need to enter your
passphrase. With keychain, you only need to enter a passphrase once
every time your local machine is rebooted. Keychain also makes it easy
for remote cron jobs to securely "hook in" to a long-running ssh-agent
process, allowing your scripts to take advantage of key-based logins.


## 📋 Package Information

- **Name**: `keychain`
- **Version**: `2.9.6`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Manage SSH and GPG keys in a convenient and secure manner
- **Homepage**: [https://www.funtoo.org/Keychain](https://www.funtoo.org/Keychain)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @sigma


## 🔧 Build Information

- **Derivation Path**: `/nix/store/432hvpyq5923989jrz6xhykxb0wcwkq9-keychain-2.9.6.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ke/keychain/package.nix:55`
- **Outputs**:
  - `out`:  `/nix/store/432hvpyq5923989jrz6xhykxb0wcwkq9-keychain-2.9.6`

## 🔗 Dependencies

- [[285jpsfl65fbd3w5qz2za3gijhjbb7ay-openssh-10.0p2]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[6i2jic85krpll6jsyclwwsh617n61m3d-gnupg-2.4.8]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cflrzgbglppcagf2jfix9hgq25126m9z-gnugrep-3.12]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lxw1zfs9v3nm19mpqbllvcl3s2hkpbjq-procps-4.0.4]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q331wl66bksvjp5qq0b3dhbcw3fx09x2-gawk-5.3.2]]
- [[sl3ibba3ad7ipf41rfzy6v8h4s0cgdci-findutils-4.10.0]]
- [[snv88gx99xy63cs66mv3b6cq56vs4g92-source]]
- [[whmvyjphw10d78zfrb04kqjlc0dy68z3-gnused-4.9]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:08:59 UTC*
