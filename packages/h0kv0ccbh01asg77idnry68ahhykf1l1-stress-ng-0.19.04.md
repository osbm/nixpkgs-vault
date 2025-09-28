---
aliases:
  - stress-ng
tags:
  - license/unknown
  - maintainers/c0bw3b
  - outputs/out
---

# stress-ng

## 📝 Description

stress-ng will stress test a computer system in various selectable ways. It
was designed to exercise various physical subsystems of a computer as well as
the various operating system kernel interfaces. Stress-ng features:

  * over 210 stress tests
  * over 50 CPU specific stress tests that exercise floating point, integer,
    bit manipulation and control flow
  * over 20 virtual memory stress tests
  * portable: builds on Linux, Solaris, *BSD, Minix, Android, MacOS X,
    Debian Hurd, Haiku, Windows Subsystem for Linux and SunOs/Dilos with
    gcc, clang, tcc and pcc.

stress-ng was originally intended to make a machine work hard and trip hardware
issues such as thermal overruns as well as operating system bugs that only
occur when a system is being thrashed hard. Use stress-ng with caution as some
of the tests can make a system run hot on poorly designed hardware and also can
cause excessive system thrashing which may be difficult to stop.

stress-ng can also measure test throughput rates; this can be useful to observe
performance changes across different operating system releases or types of
hardware. However, it has never been intended to be used as a precise benchmark
test suite, so do NOT use it in this manner.


## 📋 Package Information

- **Name**: `stress-ng`
- **Version**: `0.19.04`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Stress test a computer system
- **Homepage**: [https://github.com/ColinIanKing/stress-ng](https://github.com/ColinIanKing/stress-ng)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @c0bw3b


## 🔧 Build Information

- **Derivation Path**: `/nix/store/h0kv0ccbh01asg77idnry68ahhykf1l1-stress-ng-0.19.04.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/st/stress-ng/package.nix:68`
- **Outputs**:
  - `out`:  `/nix/store/h0kv0ccbh01asg77idnry68ahhykf1l1-stress-ng-0.19.04`

## 🔗 Dependencies

- [[0vksqqpjr9cbz18vw0fkb9kibrkbb2kv-libaio-0.3.113]]
- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[2nf9x9f81s47xi0g4pzqqhvwzqxz3k4r-mesa-libgbm-25.1.0]]
- [[39cjpzrja9nlwnz564n58qspjkrmk7ss-libbsd-0.12.2]]
- [[3alcyn8pyj0qplmf8gcgw1pzlws575xa-libgcrypt-1.11.1]]
- [[5q13i7fxgggsrgd666cr07a14l57zc6n-attr-2.5.2]]
- [[761d6f8hhrvq2qrbqc6ygxr3x34img28-libglvnd-1.7.0]]
- [[778k2csi3cc3hcfa4rn5x94fprhrj7vd-libcap-2.76]]
- [[923gfjqz63dyhwi634pdx0jigsyagwag-lksctp-tools-1.0.21]]
- [[ajjl874grisxsnd58mv6l0f0hs816xr4-keyutils-1.6.3]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fhaycpr5nmvh3vakycyy3c9vw7gfx6s2-judy-1.0.5]]
- [[l32gx2bqblr5gw4dqa5kv7a2n8f9qgqf-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[ylw29jpaama2xqrbyfzpgnmwjxc6mynj-libapparmor-4.1.1]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:54:56 UTC*
