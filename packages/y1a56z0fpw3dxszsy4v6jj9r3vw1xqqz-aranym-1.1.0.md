---
aliases:
  - aranym
tags:
  - license/unknown
  - outputs/out
---

# aranym

## 📝 Description

ARAnyM is a software virtual machine (similar to VirtualBox or Bochs)
designed and developed for running 32-bit Atari ST/TT/Falcon operating
systems (TOS, FreeMiNT, MagiC and Linux-m68k) and TOS/GEM applications on
any kind of hardware - be it an IBM clone (read it as "PC" :-), an Apple,
an Unix server, a graphics workstation or even a portable computer.

ARAnyM is not meant as an emulator of Atari Falcon (even though it has a
rather high Falcon software compatibility and includes most of Falcon
custom chips including VIDEL and DSP). ARAnyM is better in the sense that
it's not tied to specification of an existing Atari machine so we were
free to select the most complete CPU (68040 with MMU) and FPU (68882), add
loads of RAM (up to 4 GB), host accelerated graphics (even with OpenGL)
and direct access to various host resources including sound, disk drives,
optical storage devices (CD/DVD-ROMs), parallel port and more.


## 📋 Package Information

- **Name**: `aranym`
- **Version**: `1.1.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Atari Running on Any Machine
- **Homepage**: [https://aranym.github.io](https://aranym.github.io)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/y1a56z0fpw3dxszsy4v6jj9r3vw1xqqz-aranym-1.1.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ar/aranym/package.nix:38`
- **Outputs**:
  - `out`:  `/nix/store/y1a56z0fpw3dxszsy4v6jj9r3vw1xqqz-aranym-1.1.0`

## 🔗 Dependencies

- [[3wl257xhgal4shqwng9p90jalhrc4bnc-glu-9.0.3]]
- [[bghw4ajik18x5k3snmp3r6b58x3jyapp-sdl2-compat-2.32.56]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cih8hdf5nzfgg0jp2p0nqdkfzljshsf6-source]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[nncd4f9vl1alqwmiff6a138ppbsgbp5l-libx11-1.8.12]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:16 UTC*
