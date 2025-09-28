---
aliases:
  - libredirect
tags:
  - license/unknown
  - outputs/hook
  - outputs/out
---

# libredirect

## 📝 Description

libredirect is an LD_PRELOAD library to intercept and rewrite the paths in
glibc calls based on the value of $NIX_REDIRECTS, a colon-separated list
of path prefixes to be rewritten, e.g. "/src=/dst:/usr/=/nix/store/".


## 📋 Package Information

- **Name**: `libredirect`
- **Version**: `0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: LD_PRELOAD library to intercept and rewrite the paths in glibc calls
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/dfaq0sryvfw931fdf7f2cayf9wqyxig1-libredirect-0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libredirect/package.nix:133`
- **Outputs**:
  - `hook`:  `/nix/store/dfaq0sryvfw931fdf7f2cayf9wqyxig1-libredirect-0`
  - `out`:  `/nix/store/dfaq0sryvfw931fdf7f2cayf9wqyxig1-libredirect-0`

## 🔗 Dependencies

- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/0vk273pa0kcr2n852flnaqbqlv65scrq-libredirect.c`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/v0ddcdspxrvky5ggv5s6nv1c27bjic3v-test.c`

---
*Generated on 2025-09-27 11:51:24 UTC*
