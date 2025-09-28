---
aliases:
  - ext4magic
tags:
  - license/unknown
  - maintainers/rkoe
  - outputs/out
---

# ext4magic

## 📝 Description

ext4magic can recover/undelete files from ext3 or ext4 partitions
by retrieving file-information from the filesystem journal.

If the information in the journal are sufficient, ext4magic can
recover the most file types, with original filename, owner and group,
file mode bits and also the old atime/mtime stamps.

It's much more effective and works much better than extundelete.


## 📋 Package Information

- **Name**: `ext4magic`
- **Version**: `0.3.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Recover / undelete files from ext3 or ext4 partitions
- **Homepage**: [https://ext4magic.sourceforge.net/ext4magic_en.html](https://ext4magic.sourceforge.net/ext4magic_en.html)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @rkoe


## 🔧 Build Information

- **Derivation Path**: `/nix/store/83ncs3fjvjwnglgyk134f676amvprk3j-ext4magic-0.3.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ex/ext4magic/package.nix:44`
- **Outputs**:
  - `out`:  `/nix/store/83ncs3fjvjwnglgyk134f676amvprk3j-ext4magic-0.3.2`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[3z6dcp2i69nn7h8kwl6snf651i7ds14v-util-linux-minimal-2.41.1]]
- [[68316cxk20h95lwivj1mggkdfp00qphj-ext4magic-0.3.2-i_dir_acl.patch]]
- [[a8lks340bd5pdbnh7cwcq6fmyhrdxsai-file-5.45]]
- [[ab8z09795d87sqxn82fd98yaijhnxqrj-fix-segfault-extent-free.patch]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lcm255yygf2ynzhgspppj3p5a5xkmxnz-e2fsprogs-1.47.3]]
- [[lis19ll4vqlap4mzxd0mlzk2xnqx1jzl-ext4magic-0.3.2.tar.gz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[y4lfwlviqzkdrk9973a02vpl0fk4h1vy-bzip2-1.0.8]]

## 📁 Input Sources

- `/nix/store/ijqs4bmzr061rvc4dr4j1in4lian5x7s-glibc-fix.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:56:35 UTC*
