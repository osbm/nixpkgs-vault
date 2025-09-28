---
aliases:
  - fsarchiver
tags:
  - license/unknown
  - outputs/out
---

# fsarchiver

## 📝 Description

FSArchiver is a system tool that allows you to save the contents of a
file-system to a compressed archive file. The file-system can be restored
on a partition which has a different size and it can be restored on a
different file-system. Unlike tar/dar, FSArchiver also creates the
file-system when it extracts the data to partitions. Everything is
checksummed in the archive in order to protect the data. If the archive is
corrupt, you just loose the current file, not the whole archive.


## 📋 Package Information

- **Name**: `fsarchiver`
- **Version**: `0.8.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: File system archiver for linux
- **Homepage**: [https://www.fsarchiver.org/](https://www.fsarchiver.org/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/x0pgc4j601d0mr18s611f1vd0qxn99j1-fsarchiver-0.8.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/fs/fsarchiver/package.nix:54`
- **Outputs**:
  - `out`:  `/nix/store/x0pgc4j601d0mr18s611f1vd0qxn99j1-fsarchiver-0.8.8`

## 🔗 Dependencies

- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[2l7vqm19y0hygh2sfrvzpaysmp5wz0z2-source]]
- [[3alcyn8pyj0qplmf8gcgw1pzlws575xa-libgcrypt-1.11.1]]
- [[8rgz3781yw1gmfkj3lg2z5pn1y5k855h-lz4-1.10.0]]
- [[9zshxf6kk537mzc627ynbj5lgp1qff15-util-linux-2.41.1]]
- [[ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[iw7i7rklrzsglv5l2p8am46y9xa92s8r-xz-5.8.1]]
- [[lcm255yygf2ynzhgspppj3p5a5xkmxnz-e2fsprogs-1.47.3]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[mhj2iw889jzcq7hnx57rpsz608bmcpkv-libgpg-error-1.55]]
- [[nfccfj86560vhr037if3bdxdm390apj6-lzo-2.10]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[y4lfwlviqzkdrk9973a02vpl0fk4h1vy-bzip2-1.0.8]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:51:37 UTC*
