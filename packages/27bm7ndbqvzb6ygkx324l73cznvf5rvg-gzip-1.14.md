---
aliases:
  - gzip
tags:
  - license/unknown
  - outputs/info
  - outputs/man
  - outputs/out
---

# gzip

## 📝 Description

gzip (GNU zip) is a popular data compression program written by
Jean-loup Gailly for the GNU project.  Mark Adler wrote the
decompression part.

We developed this program as a replacement for compress because of
the Unisys and IBM patents covering the LZW algorithm used by
compress.  These patents made it impossible for us to use compress,
and we needed a replacement.  The superior compression ratio of gzip
is just a bonus.


## 📋 Package Information

- **Name**: `gzip`
- **Version**: `1.14`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GNU zip compression program
- **Homepage**: [https://www.gnu.org/software/gzip/](https://www.gnu.org/software/gzip/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/27bm7ndbqvzb6ygkx324l73cznvf5rvg-gzip-1.14.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/tools/compression/gzip/default.nix:65`
- **Outputs**:
  - `info`:  `/nix/store/27bm7ndbqvzb6ygkx324l73cznvf5rvg-gzip-1.14`
  - `man`:  `/nix/store/27bm7ndbqvzb6ygkx324l73cznvf5rvg-gzip-1.14`
  - `out`:  `/nix/store/27bm7ndbqvzb6ygkx324l73cznvf5rvg-gzip-1.14`

## 🔗 Dependencies

- [[05q48dcd4lgk4vh7wyk330gr2fr082i2-bootstrap-tools]]
- [[89a9mwmlb0jnpgdc8d1w2qmjvph8ng4a-make-shell-wrapper-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[d7ir44pmpq2y8lyyrniiflkw9cw0a5k3-bootstrap-stage4-stdenv-linux]]
- [[hxn5cn3r48d4css91508lgkd5vwnnqcr-update-autotools-gnu-config-scripts-hook]]
- [[mbfqb9y6ryn2axyvg797s3lw1w49liz5-gzip-1.14.tar.xz]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:02:53 UTC*
