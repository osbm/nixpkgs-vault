---
aliases:
  - chrony
tags:
  - license/unknown
  - maintainers/thoughtpolice
  - maintainers/vifino
  - outputs/man
  - outputs/out
---

# chrony

## 📝 Description

Chronyd is a daemon which runs in background on the system. It obtains
measurements via the network of the system clock’s offset relative to
time servers on other systems and adjusts the system time accordingly.
For isolated systems, the user can periodically enter the correct time by
hand (using Chronyc). In either case, Chronyd determines the rate at
which the computer gains or loses time, and compensates for this. Chronyd
implements the NTP protocol and can act as either a client or a server.

Chronyc provides a user interface to Chronyd for monitoring its
performance and configuring various settings. It can do so while running
on the same computer as the Chronyd instance it is controlling or a
different computer.


## 📋 Package Information

- **Name**: `chrony`
- **Version**: `4.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Sets your computer's clock from time servers on the Net
- **Homepage**: [https://chrony-project.org/](https://chrony-project.org/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `x86_64-darwin`, `aarch64-darwin`, `x86_64-solaris`
## 👥 Maintainers

- @thoughtpolice
- @vifino


## 🔧 Build Information

- **Derivation Path**: `/nix/store/x9kyx9xcvjx3k8z0qfp7pdz06ba5yy08-chrony-4.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ch/chrony/package.nix:72`
- **Outputs**:
  - `man`:  `/nix/store/x9kyx9xcvjx3k8z0qfp7pdz06ba5yy08-chrony-4.8`
  - `out`:  `/nix/store/x9kyx9xcvjx3k8z0qfp7pdz06ba5yy08-chrony-4.8`

## 🔗 Dependencies

- [[0naxaa1qv8im32fmwrk12qiwfvwwkmsn-gnutls-3.8.10]]
- [[42bjg3xqii9468v58mlazl33c030mgj9-chrony-4.8.tar.gz]]
- [[778k2csi3cc3hcfa4rn5x94fprhrj7vd-libcap-2.76]]
- [[b4pa5k4if2jl33f1ynicjwz2nihy4z3c-texinfo-7.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[jvk6w0wmh9f50wh0xr7mb7faz9ipbmzv-libseccomp-2.6.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[wdsywa1x3n3s43zcsa0l29bnn5f37s88-libedit-20250104-3.1]]
- [[z2xr6i42j3h3p1r1y59ycrczccjx9zf3-pps-tools-1.0.3]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/vb47k50zqgf7p6xzmr872crd19161p3f-makefile.patch`

---
*Generated on 2025-09-27 11:45:59 UTC*
