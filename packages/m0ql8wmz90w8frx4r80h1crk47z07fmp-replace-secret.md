---
aliases:
  - replace-secret
tags:
  - license/unknown
  - maintainers/talyz
  - outputs/out
---

# replace-secret

## 📝 Description

Replace a string in one file with a secret from a second file.

Since the secret is read from a file, it won't be leaked through
'/proc/<pid>/cmdline', unlike when 'sed' or 'replace' is used.


## 📋 Package Information

- **Name**: `replace-secret`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Replace a string in one file with a secret from a second file
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @talyz


## 🔧 Build Information

- **Derivation Path**: `/nix/store/m0ql8wmz90w8frx4r80h1crk47z07fmp-replace-secret.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/build-support/replace-secret/replace-secret.nix:32`
- **Outputs**:
  - `out`:  `/nix/store/m0ql8wmz90w8frx4r80h1crk47z07fmp-replace-secret`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/12wgl9xwwmwvlp70bjrda716al649w74-expected_long_output`
- `/nix/store/29rx41fh9hjrkbadiyz2cvc37hyjax42-expected_short_output`
- `/nix/store/2y7rvy0km2j4vrq1gm8a2bspy9qm3iyi-input_file`
- `/nix/store/9p4akjyrxycrw7vqqpknygzd7wp8991v-passwd`
- `/nix/store/ip2937ljng92w6ylvcvpr0bkbs91nyjj-rsa`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/rf1nfcgl8zlhn782r3ap440qq0bzk619-replace-secret.py`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:18:09 UTC*
