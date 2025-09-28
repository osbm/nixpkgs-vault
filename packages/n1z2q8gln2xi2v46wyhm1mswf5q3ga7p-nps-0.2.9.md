---
aliases:
  - nps
tags:
  - license/unknown
  - maintainers/OleMussmann
  - outputs/out
---

# nps

## 📝 Description

Find SEARCH_TERM in available nix packages and sort results by relevance.

List up to three columns, the latter two being optional:
PACKAGE_NAME  <PACKAGE_VERSION>  <PACKAGE_DESCRIPTION>

Matches are sorted by type. Show 'indirect' matches first, then 'direct' matches, and finally 'exact' matches.

  indirect  fooSEARCH_TERMbar (SEARCH_TERM appears in any column)
  direct    SEARCH_TERMbar (PACKAGE_NAME starts with SEARCH_TERM)
  exact     SEARCH_TERM (PACKAGE_NAME is exactly SEARCH_TERM)


## 📋 Package Information

- **Name**: `nps`
- **Version**: `0.2.9`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Cache the nix package list, query and sort results by relevance
- **Homepage**: [https://github.com/OleMussmann/nps](https://github.com/OleMussmann/nps)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv6l-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv64-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `powerpc-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `i686-windows`, `x86_64-windows`, `armv5tel-linux`, `armv7a-linux`, `m68k-linux`, `mips-linux`, `mips64-linux`, `mipsel-linux`, `mips64el-linux`, `riscv32-linux`, `armv6l-netbsd`, `mipsel-netbsd`, `riscv64-netbsd`, `x86_64-redox`, `wasm32-wasi`
## 👥 Maintainers

- @OleMussmann


## 🔧 Build Information

- **Derivation Path**: `/nix/store/n1z2q8gln2xi2v46wyhm1mswf5q3ga7p-nps-0.2.9.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/np/nps/package.nix:24`
- **Outputs**:
  - `out`:  `/nix/store/n1z2q8gln2xi2v46wyhm1mswf5q3ga7p-nps-0.2.9`

## 🔗 Dependencies

- [[0f5ann1sgwyp31vlfqqsnr95xzv3mzhf-cargo-1.89.0]]
- [[3bz4j2xzjl92yhiwfyhbz6gv4w1888bw-cargo-setup-hook.sh]]
- [[3ndchkhlxxw50k7nd48i9zdkhsr57mwh-cargo-install-hook.sh]]
- [[4bycw2rdgf33gmn1z26knv8grxxh06w5-rustc-wrapper-1.89.0]]
- [[4cc0y6syxyxvjx1lh8ix60vxkly149fh-auditable-cargo-1.89.0]]
- [[4givbpwpw36il7vvqb13cpan3r19jxnx-source]]
- [[9vzsndb5r52c1q344sm1gia2vr3j3xhj-nix-2.28.5]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[mkz16yyc0jaa9dkkjp0ymz5is4cghi0m-nps-0.2.9-vendor]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qi6337yh29r9ppqm262bf6vz0g13451b-cargo-build-hook.sh]]
- [[xqxbqs6qgnhvpkcai046s94jfrx8wb62-cargo-check-hook.sh]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:26:43 UTC*
