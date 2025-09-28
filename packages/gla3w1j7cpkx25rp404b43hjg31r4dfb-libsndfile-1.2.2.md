---
aliases:
  - libsndfile
tags:
  - license/unknown
  - maintainers/lovek323
  - outputs/bin
  - outputs/dev
  - outputs/doc
  - outputs/man
  - outputs/out
---

# libsndfile

## 📝 Description

Libsndfile is a C library for reading and writing files containing
sampled sound (such as MS Windows WAV and the Apple/SGI AIFF format)
through one standard library interface.  It is released in source
code format under the GNU Lesser General Public License.

The library was written to compile and run on a Linux system but
should compile and run on just about any Unix (including macOS).
There are also pre-compiled binaries available for 32 and 64 bit
windows.

It was designed to handle both little-endian (such as WAV) and
big-endian (such as AIFF) data, and to compile and run correctly on
little-endian (such as Intel and DEC/Compaq Alpha) processor systems
as well as big-endian processor systems such as Motorola 68k, Power
PC, MIPS and SPARC.  Hopefully the design of the library will also
make it easy to extend for reading and writing new sound file
formats.


## 📋 Package Information

- **Name**: `libsndfile`
- **Version**: `1.2.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: C library for reading and writing files containing sampled sound
- **Homepage**: [https://libsndfile.github.io/libsndfile/](https://libsndfile.github.io/libsndfile/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @lovek323


## 🔧 Build Information

- **Derivation Path**: `/nix/store/gla3w1j7cpkx25rp404b43hjg31r4dfb-libsndfile-1.2.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/libsndfile/package.nix:99`
- **Outputs**:
  - `bin`:  `/nix/store/gla3w1j7cpkx25rp404b43hjg31r4dfb-libsndfile-1.2.2`
  - `dev`:  `/nix/store/gla3w1j7cpkx25rp404b43hjg31r4dfb-libsndfile-1.2.2`
  - `doc`:  `/nix/store/gla3w1j7cpkx25rp404b43hjg31r4dfb-libsndfile-1.2.2`
  - `man`:  `/nix/store/gla3w1j7cpkx25rp404b43hjg31r4dfb-libsndfile-1.2.2`
  - `out`:  `/nix/store/gla3w1j7cpkx25rp404b43hjg31r4dfb-libsndfile-1.2.2`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[345q8xwbazzksaiaydm8kd6p5zb1ymr5-libvorbis-1.3.7]]
- [[39jlnb9vgammhav2skbf3dvkbciqsh14-libopus-1.5.2]]
- [[4z3zy54ips5245rgfb0d6z7pmracjaiy-libogg-1.3.6]]
- [[8f4dz87rkzinrp8k2xdb1gm37xpixnjy-flac-1.5.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[fvy2dpx8zbgmax6cvfpfyzb2cxzadfsd-lame-3.100]]
- [[hin2wllxzjcvbxvk31dmgv4bf18y3p4n-libmpg123-1.33.2]]
- [[if30dvb18877vhsf1yhq7bzsgw20xlby-alsa-lib-1.2.14]]
- [[iyg6gnbxnhcrj5c0a9nmq493298ppjm3-source]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[nvg55ys5w0hcvxzsxab9ja6wh3a2g1d5-autogen-5.18.16]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:02:02 UTC*
