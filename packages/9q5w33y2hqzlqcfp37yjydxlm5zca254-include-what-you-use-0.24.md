---
aliases:
  - include-what-you-use
tags:
  - license/unknown
  - outputs/out
---

# include-what-you-use

## 📝 Description

For every symbol (type, function variable, or macro) that you use in
foo.cc, either foo.cc or foo.h should #include a .h file that exports the
declaration of that symbol.  The main goal of include-what-you-use is to
remove superfluous #includes, both by figuring out what #includes are not
actually needed for this file (for both .cc and .h files), and by
replacing #includes with forward-declares when possible.


## 📋 Package Information

- **Name**: `include-what-you-use`
- **Version**: `0.24`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Analyze #includes in C/C++ source files with clang
- **Homepage**: [https://include-what-you-use.org](https://include-what-you-use.org)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/9q5w33y2hqzlqcfp37yjydxlm5zca254-include-what-you-use-0.24.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/tools/analysis/include-what-you-use/default.nix:55`
- **Outputs**:
  - `out`:  `/nix/store/9q5w33y2hqzlqcfp37yjydxlm5zca254-include-what-you-use-0.24`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[4dkjkimimz305jklzp7rfnnd1ashzh44-clang-wrapper-20.1.8]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dg0a8xf2y78cdq21y7x4azvam72874a7-clang-20.1.8]]
- [[k0m6xbclli4ryzvyj58fg2i5i1yaxzyr-llvm-20.1.8]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vgdqpk6b63c7mmhmv0jlqfdchmchcwgj-include-what-you-use-0.24.src.tar.gz]]

## 📁 Input Sources

- `/nix/store/55l3irhqnfv815mmqkl4bg675iiiy0br-wrapper`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:10:48 UTC*
