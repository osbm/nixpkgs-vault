---
aliases:
  - sshlatex
tags:
  - license/unknown
  - maintainers/iblech
  - outputs/out
---

# sshlatex

## 📝 Description

sshlatex is a tool which uploads LaTeX source files to a remote, runs
LaTeX there, and streams the resulting PDF file to the local host.
Because sshlatex prestarts LaTeX with the previous run's preamble,
thereby preloading the required LaTeX packages, it is also useful in a
purely local setting.


## 📋 Package Information

- **Name**: `sshlatex`
- **Version**: `0.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Collection of hacks to efficiently run LaTeX via ssh
- **Homepage**: [https://github.com/iblech/sshlatex](https://github.com/iblech/sshlatex)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @iblech


## 🔧 Build Information

- **Derivation Path**: `/nix/store/jki3akry18s79ffafwgnnzgd8gpx6wsv-sshlatex-0.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ss/sshlatex/package.nix:43`
- **Outputs**:
  - `out`:  `/nix/store/jki3akry18s79ffafwgnnzgd8gpx6wsv-sshlatex-0.8`

## 🔗 Dependencies

- [[285jpsfl65fbd3w5qz2za3gijhjbb7ay-openssh-10.0p2]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[3fsp9xqfr83bgpp3b0v81qk2qkdbzy84-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[by779xx7waywsnj4bn9vnwyg6a2b59mj-inotify-tools-4.23.9.0]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[rrn4zjbhvfmi5asxn3cjgddfzjkvpz8y-gnutar-1.35]]
- [[v28sdl3535sxb6a71z5faqdzbns9pv0h-bash-interactive-5.3p3]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:51:39 UTC*
