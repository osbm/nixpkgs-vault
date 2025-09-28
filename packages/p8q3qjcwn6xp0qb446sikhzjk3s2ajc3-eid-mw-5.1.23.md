---
aliases:
  - eid-mw
tags:
  - license/unknown
  - maintainers/bfortz
  - maintainers/chvp
  - outputs/out
---

# eid-mw

## 📝 Description

Allows user authentication and digital signatures with Belgian ID cards.
Also requires a running pcscd service and compatible card reader.

eid-viewer is also installed.

This package only installs the libraries. To use eIDs in Firefox or
Chromium, the eID Belgium add-on must be installed.
This package only installs the libraries. To use eIDs in NSS-compatible
browsers like Chrom{e,ium} or Firefox, each user must first execute:
  ~$ eid-nssdb add
(Running the script once as root with the --system option enables eID
support for all users, but will *not* work when using Chrom{e,ium}!)
Before uninstalling this package, it is a very good idea to run
  ~$ eid-nssdb [--system] remove
and remove all ~/.pki and/or /etc/pki directories no longer needed.

The above procedure doesn't seem to work in Firefox. You can override the
firefox wrapper to add this derivation to the PKCS#11 modules, like so:

    firefox.override { pkcs11Modules = [ pkgs.eid-mw ]; }


## 📋 Package Information

- **Name**: `eid-mw`
- **Version**: `5.1.23`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Belgian electronic identity card (eID) middleware
- **Homepage**: [https://eid.belgium.be/en](https://eid.belgium.be/en)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @bfortz
- @chvp


## 🔧 Build Information

- **Derivation Path**: `/nix/store/p8q3qjcwn6xp0qb446sikhzjk3s2ajc3-eid-mw-5.1.23.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ei/eid-mw/package.nix:95`
- **Outputs**:
  - `out`:  `/nix/store/p8q3qjcwn6xp0qb446sikhzjk3s2ajc3-eid-mw-5.1.23`

## 🔗 Dependencies

- [[09czc2lmk3acnqc529fmhll3myrn5gb0-p11-kit-0.25.5]]
- [[1fzxi5zfzvgbj9j19wl9ihk41nhmjyw3-autoconf-archive-2024.10.16]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[39cjpzrja9nlwnz564n58qspjkrmk7ss-libbsd-0.12.2]]
- [[3h2pqwsp2izzlynp9gjar39hm70nnz89-libxml2-2.14.5]]
- [[40fdpdcsm5dijifk13lal5g506l8h8cf-libassuan-3.0.2]]
- [[474kivdzi525za8vzpgr0ils1k0qf8r3-wrap-gapps-hook]]
- [[4dq8np7c2mimniwl3if93g7ncz1cjr4r-gtk+3-3.24.49]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[94625q5v2zspqm7a29p50y11c0akr932-source]]
- [[b5d3liy3yp69xqchp26zm3y5gf36nzn2-libproxy-0.5.10]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[g1smgp5dhq2ii8np7vm7n5znki3ak1b1-curl-8.14.1]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pb2jv6x42drl1qasnh0z7w3dvnd4g0q3-nss-3.112.1]]
- [[r48wqvwdssqgvdmiak53raw5a193spbm-pcsclite-2.3.0]]
- [[vf0kgm8hi9pd22j8mhcg59jvny5gq6fs-eid-nssdb.in]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:58:32 UTC*
