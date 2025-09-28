---
aliases:
  - python312Packages.python3-gnutls
tags:
  - license/unknown
  - maintainers/charlieshanley
  - outputs/dist
  - outputs/out
---

# python312Packages.python3-gnutls

## 📝 Description

This package provides a high level object oriented wrapper around libgnutls,
as well as low level bindings to the GnuTLS types and functions via ctypes.
The high level wrapper hides the details of accessing the GnuTLS library via
ctypes behind a set of classes that encapsulate GnuTLS sessions, certificates
and credentials and expose them to python applications using a simple API.

The package also includes a Twisted interface that has seamless intergration
with Twisted, providing connectTLS and listenTLS methods on the Twisted
reactor once imported (the methods are automatically attached to the reactor
by simply importing the GnuTLS Twisted interface module).

The high level wrapper is written using the GnuTLS library bindings that are
made available via ctypes. This makes the wrapper very powerful and flexible
as it has direct access to all the GnuTLS internals and is also very easy to
extend without any need to write C code or recompile anything.



## 📋 Package Information

- **Name**: `python312Packages.python3-gnutls`
- **Version**: `3.1.10`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Python wrapper for the GnuTLS library
- **Homepage**: [https://github.com/AGProjects/python3-gnutls](https://github.com/AGProjects/python3-gnutls)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @charlieshanley


## 🔧 Build Information

- **Derivation Path**: `/nix/store/bjnyjw3brd46b1lj2wib31kgfsizfgbd-python3.12-python3-gnutls-3.1.10.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/python-modules/python3-gnutls/default.nix:45`
- **Outputs**:
  - `dist`:  `/nix/store/bjnyjw3brd46b1lj2wib31kgfsizfgbd-python3.12-python3-gnutls-3.1.10`
  - `out`:  `/nix/store/bjnyjw3brd46b1lj2wib31kgfsizfgbd-python3.12-python3-gnutls-3.1.10`

## 🔗 Dependencies

- [[5vsffdi0kgla24ca4l9bv0fxzc7s2qyk-pypa-build-hook.sh]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[9n6ilj22rdmwywgdlyqsbbkdlxdq525w-python3.12-service-identity-24.2.0]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bki4kxsbvd13sz5a2bqr2b9y7vvgpmiy-python-runtime-deps-check-hook.sh]]
- [[di2np59yg9yf560yms5ff9188a5gnlbb-python-imports-check-hook.sh]]
- [[dkqa3dj2k1vqrmlyd6hrdf8dww0f5dr9-python-remove-tests-dir-hook]]
- [[fhrpbbzpqw4bvsy4ixq1fb9k2aaslnw0-python-catch-conflicts-hook]]
- [[fz0k8m7chhichwdj1h1g54hjfh80g3nm-python3-3.12.11]]
- [[g9bcdx47nd5qfi29d66nbxbwckd5g99m-python-namespaces-hook.sh]]
- [[j45jmjf6mwz46p7f0f8hjpnzi9pz2pzv-wrap-python-hook]]
- [[kh0627w4wff8syd1iis567224170xw3l-pypa-install-hook]]
- [[p4pzbm45n9azl7lkbmcpq1443vjprndj-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pjysml02i1kii8xqlnir3bkc08z7byl8-libgnutls-path.patch]]
- [[xj97f4d4d468fjvhhx214ma7zh4l2wyc-python3.12-setuptools-80.9.0]]
- [[z1z8hhwp9iridwshz4vz9pzz7fnpdpph-python3.12-twisted-25.5.0]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]
- [[zb3ry0sj3wchsarjp9g5vy96gjfg81lp-python3.12-pyopenssl-25.1.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:06:49 UTC*
