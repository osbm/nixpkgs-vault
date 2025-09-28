---
aliases:
  - mtrace
tags:
  - license/unknown
  - maintainers/Ma27
  - maintainers/ConnorBaker
  - outputs/out
---

# mtrace

## 📝 Description

Any Unix-like operating system needs a C library: the library which
defines the "system calls" and other basic facilities such as
open, malloc, printf, exit...

The GNU C library is used as the C library in the GNU system and
most systems with the Linux kernel.


## 📋 Package Information

- **Name**: `mtrace`
- **Version**: `2.40-66`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Perl script used to interpret and provide human readable output of the trace log contained in the file mtracedata, whose contents were produced by mtrace(3)
- **Homepage**: [https://www.gnu.org/software/libc/](https://www.gnu.org/software/libc/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @Ma27
- @ConnorBaker


## 🔧 Build Information

- **Derivation Path**: `/nix/store/hk3p5sc6g0wk3amq79k0iyvrbppnpxy2-glibc-mtrace-2.40-66.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/libraries/glibc/mtrace.nix:38`
- **Outputs**:
  - `out`:  `/nix/store/hk3p5sc6g0wk3amq79k0iyvrbppnpxy2-glibc-mtrace-2.40-66`

## 🔗 Dependencies

- [[05q48dcd4lgk4vh7wyk330gr2fr082i2-bootstrap-tools]]
- [[4g9df6a0v0g5c2j5x23vv0i89aw2pd7l-bootstrap-stage2-stdenv-linux]]
- [[5fia0s7sl13hsqbhcmgmjpq84i0rqczs-glibc-2.40.tar.xz]]
- [[bgkb3y8qyl0xv9m1rmr8734h6l9nhnr3-libidn2-2.3.8]]
- [[d22d84b84air380f116svsg6hcpy0hch-bison-3.8.2]]
- [[dzfhk2dh9vhlyzfj4iwkhmkd95c1iz90-python3-minimal-3.13.7]]
- [[gwl30dsq8qq0zhk6i79ljgr76mwkydbd-linux-headers-6.16]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[q231p73p2r7j3bkly9d8rihi29iq03jw-bootstrap-stage2-gcc-wrapper-14.3.0]]
- [[r4ymr0qa6vi193b9d72xqy2g7zypak2p-xgcc-14.3.0]]
- [[swcark68dhh8qx8jnq6xjs2siakw5ggz-bootstrap-stage0-glibc-bootstrapFiles]]
- [[w6shw8brmkd5b4i52944hxwvy20y1b98-binutils-2.44]]

## 📁 Input Sources

- `/nix/store/001gp43bjqzx60cg345n2slzg7131za8-nix-nss-open-files.patch`
- `/nix/store/2wlbvj13lm5rln4i71b3972lcfd91hzs-2.40-master.patch`
- `/nix/store/7kw224hdyxd7115lrqh9a4dv2x8msq2s-fix-x64-abi.patch`
- `/nix/store/b1w7zbvm39ff1i52iyjggyvw2rdxz104-dont-use-system-ld-so-cache.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/mnglr8rr7nl444h7p50ysyq8qd0fm1lm-dont-use-system-ld-so-preload.patch`
- `/nix/store/nc5hqqizlj7042vvhvx121kzf4nwh35p-nix-locale-archive.patch`
- `/nix/store/pcpx2ayccijipfl32zchx0mg7rzvj6zx-0001-Revert-Remove-all-usage-of-BASH-or-BASH-in-installed.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/sj0qllprnrmk1cqnnk57vvn2cqgjynbx-reenable_DT_HASH.patch`
- `/nix/store/za0pg7fmysrcwrqcal26fnmzw6vycgdn-fix_path_attribute_in_getconf.patch`

---
*Generated on 2025-09-27 12:11:35 UTC*
