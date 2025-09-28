---
aliases:
  - ant
tags:
  - license/unknown
  - maintainers/chayleaf
  - maintainers/FliegendeWurst
  - maintainers/Infinidoge
  - maintainers/tomodachi94
  - outputs/out
---

# ant

## 📝 Description

Apache Ant is a Java-based build tool.  In theory, it is kind of like
Make, but without Make's wrinkles.

Why another build tool when there is already make, gnumake, nmake, jam,
and others? Because all those tools have limitations that Ant's
original author couldn't live with when developing software across
multiple platforms.  Make-like tools are inherently shell-based -- they
evaluate a set of dependencies, then execute commands not unlike what
you would issue in a shell.  This means that you can easily extend
these tools by using or writing any program for the OS that you are
working on.  However, this also means that you limit yourself to the
OS, or at least the OS type such as Unix, that you are working on.

Ant is different.  Instead of a model where it is extended with
shell-based commands, Ant is extended using Java classes.  Instead of
writing shell commands, the configuration files are XML-based, calling
out a target tree where various tasks get executed.  Each task is run
by an object that implements a particular Task interface.


## 📋 Package Information

- **Name**: `ant`
- **Version**: `1.10.15`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Java-based build tool
- **Homepage**: [https://ant.apache.org/](https://ant.apache.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @chayleaf
- @FliegendeWurst
- @Infinidoge
- @tomodachi94


## 🔧 Build Information

- **Derivation Path**: `/nix/store/s8s7v9kn0bxd51vqgxdhs8j407sc7155-ant-1.10.15.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/an/ant/package.nix:88`
- **Outputs**:
  - `out`:  `/nix/store/s8s7v9kn0bxd51vqgxdhs8j407sc7155-ant-1.10.15`

## 🔗 Dependencies

- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[sf5bn4526lzvyl1a8abxkwh0nriyy7v9-apache-ant-1.10.15-bin.tar.bz2]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:48:19 UTC*
