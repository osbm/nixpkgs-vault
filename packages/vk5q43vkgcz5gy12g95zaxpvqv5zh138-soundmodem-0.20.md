---
aliases:
  - soundmodem
tags:
  - license/unknown
  - maintainers/ymarkus
  - outputs/out
---

# soundmodem

## 📝 Description

This software allows a standard PC soundcard to be used as a packet radio "modem". The whole processing is done on the main processor CPU.
Unlike previous packet radio modem software, this new release offers several new benefits:
  - Now uses standard operating system sound drivers (OSS/Free under Linux, /dev/audio under Solaris and DirectSound under Windows), thus runs on all soundcards for which drivers for the desired operating system are available.
  - No fixed relationship between bitrate, sampling rate, and modem parameters. Modems may be parametrized, and multiple modems may even run on the same audio channel!
  - Usermode solution allows the use of MMX, VIS, Floating point and other media instruction sets to speed up computation.
  - Cross platform builds from a single source code provides ubiquitous availability.


## 📋 Package Information

- **Name**: `soundmodem`
- **Version**: `0.20`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Audio based modem for ham radio supporting ax.25
- **Homepage**: [http://soundmodem.vk4msl.id.au/](http://soundmodem.vk4msl.id.au/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @ymarkus


## 🔧 Build Information

- **Derivation Path**: `/nix/store/vk5q43vkgcz5gy12g95zaxpvqv5zh138-soundmodem-0.20.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/so/soundmodem/package.nix:49`
- **Outputs**:
  - `out`:  `/nix/store/vk5q43vkgcz5gy12g95zaxpvqv5zh138-soundmodem-0.20`

## 🔗 Dependencies

- [[3h2pqwsp2izzlynp9gjar39hm70nnz89-libxml2-2.14.5]]
- [[6bf92nwypqw5hdy3z5fj4kmv39phlfii-soundmodem-0.20.tar.gz]]
- [[8np1czscddzfmi7vmm44smvpjxshlidi-gtk+-2.24.33]]
- [[ak6sfkva7159cv3csybhpqw45qk3bk6a-SoundmodemConfig.desktop]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fq23lcwc1p6ww77gxriaa7n57wva6mag-copy-desktop-items-hook]]
- [[if30dvb18877vhsf1yhq7bzsgw20xlby-alsa-lib-1.2.14]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[zqvbr8c8pr82jip25j79ac98z19p4yah-audiofile-0.3.6]]

## 📁 Input Sources

- `/nix/store/5g7v89vqgqaqwphf613g5wbl6cl2d9af-matFix.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:13:13 UTC*
