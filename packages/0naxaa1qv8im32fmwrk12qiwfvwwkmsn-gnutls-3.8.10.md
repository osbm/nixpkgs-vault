---
aliases:
  - gnutls
tags:
  - license/unknown
  - maintainers/vcunat
  - outputs/bin
  - outputs/dev
  - outputs/devdoc
  - outputs/man
  - outputs/out
---

# gnutls

## 📝 Description

GnuTLS is a project that aims to develop a library which
provides a secure layer, over a reliable transport
layer. Currently the GnuTLS library implements the proposed standards by
the IETF's TLS working group.

Quoting from the TLS protocol specification:

"The TLS protocol provides communications privacy over the
Internet. The protocol allows client/server applications to
communicate in a way that is designed to prevent eavesdropping,
tampering, or message forgery."


## 📋 Package Information

- **Name**: `gnutls`
- **Version**: `3.8.10`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GNU Transport Layer Security Library
- **Homepage**: [https://gnutls.org/](https://gnutls.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @vcunat


## 🔧 Build Information

- **Derivation Path**: `/nix/store/0naxaa1qv8im32fmwrk12qiwfvwwkmsn-gnutls-3.8.10.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/libraries/gnutls/default.nix:218`
- **Outputs**:
  - `bin`:  `/nix/store/0naxaa1qv8im32fmwrk12qiwfvwwkmsn-gnutls-3.8.10`
  - `dev`:  `/nix/store/0naxaa1qv8im32fmwrk12qiwfvwwkmsn-gnutls-3.8.10`
  - `devdoc`:  `/nix/store/0naxaa1qv8im32fmwrk12qiwfvwwkmsn-gnutls-3.8.10`
  - `man`:  `/nix/store/0naxaa1qv8im32fmwrk12qiwfvwwkmsn-gnutls-3.8.10`
  - `out`:  `/nix/store/0naxaa1qv8im32fmwrk12qiwfvwwkmsn-gnutls-3.8.10`

## 🔗 Dependencies

- [[09czc2lmk3acnqc529fmhll3myrn5gb0-p11-kit-0.25.5]]
- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[3z6dcp2i69nn7h8kwl6snf651i7ds14v-util-linux-minimal-2.41.1]]
- [[4f9j67x7cgs2hzjgyyzm8q6z1w2vgy41-which-2.23]]
- [[5fnl19ibazlhzcrmxg56s11v29rw1cqc-gmp-with-cxx-6.3.0]]
- [[82mw0nl5kb1zw36l4s4d0pdlfiadwlss-automake-1.18.1]]
- [[8465n962pxrspxpyjy7i47z3m31rv6p1-dns-root-data-2025-04-14]]
- [[9cgpw040lnrjd7568c3a9xxn2ikbwyag-gnutls-3.8.10.tar.xz]]
- [[9la9jbgqkqm3g8ys0wdb49klh7pb8j20-autoconf-2.69]]
- [[asabv7p1bly5ilbbwjwsmv4wx75iwfmg-libtasn1-4.20.0]]
- [[b4pa5k4if2jl33f1ynicjwz2nihy4z3c-texinfo-7.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gi5izcpszaxq8y1rkkzn00kyx2rc2fnq-net-tools-2.10]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[li9izjgls3p576wmy48549fpz5amc9dm-libunistring-1.3]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[lw9n65hjs29677xgdhsfjwvmg900lyb9-unbound-1.23.1]]
- [[m0h8vm7wnxqmzy77yph902p607lx7np5-gettext-0.25.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pasdgphxm21zciq62qw7bb0vwfdifmvn-glibc-iconv-2.40]]
- [[vg0fvkssl3inzs170dlp4c1mn9ky9mm1-libidn2-2.3.8]]
- [[zcqnvxxzciz32hjngdfybshixmx2lc8m-nettle-3.10.2]]

## 📁 Input Sources

- `/nix/store/05qv74pm6yz68igyyzkmb0w4cqsq9k56-nix-ssl-cert-file.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/wfnw2gdabjyr24qjwrwa9rs2p7da1mc8-dummy.crt`

---
*Generated on 2025-09-27 11:48:17 UTC*
