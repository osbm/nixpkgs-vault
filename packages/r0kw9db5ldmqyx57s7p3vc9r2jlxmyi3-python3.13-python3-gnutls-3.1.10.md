---
aliases:
  - python313Packages.python3-gnutls
tags:
  - license/unknown
  - maintainers/charlieshanley
  - outputs/dist
  - outputs/out
---

# python313Packages.python3-gnutls

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

- **Name**: `python313Packages.python3-gnutls`
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

- **Derivation Path**: `/nix/store/r0kw9db5ldmqyx57s7p3vc9r2jlxmyi3-python3.13-python3-gnutls-3.1.10.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/python-modules/python3-gnutls/default.nix:45`
- **Outputs**:
  - `dist`:  `/nix/store/r0kw9db5ldmqyx57s7p3vc9r2jlxmyi3-python3.13-python3-gnutls-3.1.10`
  - `out`:  `/nix/store/r0kw9db5ldmqyx57s7p3vc9r2jlxmyi3-python3.13-python3-gnutls-3.1.10`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[4saqrrp0xw9kw1pzwl6n08dbkl5s4y5n-python3.13-pyopenssl-25.1.0]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[c0z5lcjv8axwrbk8j2snfyyvf9f2ykxf-python3.13-service-identity-24.2.0]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[dnbzpphxbd6h31n44gfwbg1qf9q03wcr-pypa-build-hook.sh]]
- [[fmgak3lvqw3ff8wym1v40kgi0b5i1iza-python-runtime-deps-check-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[p4pzbm45n9azl7lkbmcpq1443vjprndj-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pjysml02i1kii8xqlnir3bkc08z7byl8-libgnutls-path.patch]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[r75s0fm9h644vnwxa0b736h38a9mfz4x-python3.13-twisted-25.5.0]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:26:36 UTC*
