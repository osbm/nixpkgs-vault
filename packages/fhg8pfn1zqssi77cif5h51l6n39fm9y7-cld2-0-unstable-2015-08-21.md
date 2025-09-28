---
aliases:
  - cld2
tags:
  - license/unknown
  - maintainers/chvp
  - outputs/out
---

# cld2

## 📝 Description

CLD2 probabilistically detects over 80 languages in Unicode UTF-8 text,
either plain text or HTML/XML. Legacy encodings must be converted to valid
UTF-8 by the caller. For mixed-language input, CLD2 returns the top three
languages found and their approximate percentages of the total text bytes
(e.g. 80% English and 20% French out of 1000 bytes of text means about 800
bytes of English and 200 bytes of French). Optionally, it also returns a
vector of text spans with the language of each identified. This may be
useful for applying different spelling-correction dictionaries or
different machine translation requests to each span. The design target is
web pages of at least 200 characters (about two sentences); CLD2 is not
designed to do well on very short text, lists of proper names, part
numbers, etc.


## 📋 Package Information

- **Name**: `cld2`
- **Version**: `0-unstable-2015-08-21`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Compact Language Detector 2
- **Homepage**: [https://github.com/CLD2Owners/cld2](https://github.com/CLD2Owners/cld2)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @chvp


## 🔧 Build Information

- **Derivation Path**: `/nix/store/fhg8pfn1zqssi77cif5h51l6n39fm9y7-cld2-0-unstable-2015-08-21.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/cl/cld2/package.nix:32`
- **Outputs**:
  - `out`:  `/nix/store/fhg8pfn1zqssi77cif5h51l6n39fm9y7-cld2-0-unstable-2015-08-21`

## 🔗 Dependencies

- [[14sdzja3424imiyf820lzwcl928hhsva-source]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cb88z7gdil469lrklqp1jcjflisw2hqj-add-cmakelists.txt]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:48:32 UTC*
