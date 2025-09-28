---
aliases:
  - autenticacao-gov-pt-bin
tags:
  - license/unknown
  - maintainers/vaavaav
  - outputs/out
---

# autenticacao-gov-pt-bin

## 📝 Description

This package provides the official Portuguese Citizen Card middleware (Autenticação.gov),
extracted from AMA’s Flatpak release. It enables authentication and digital signing using
the Portuguese eID system.

On NixOS, it works with a supported card reader and Citizen Card, as long as
`services.pcscd.enable = true` is set in the system configuration.

Notes:
  - Depends on xerces-c 3.2.3, which is no longer in nixpkgs. This package includes a version
    override to restore it for compatibility.

  - The application uses hardcoded paths for libraries and binaries. To accommodate this,
    `proot` is used at runtime to simulate a traditional filesystem layout. This allows the
    binary to run unmodified, though it may introduce minor latency.

  - A desktop entry is included for integration with graphical environments.

Building from source is possible, but upstream disables signing in source builds. Using the
official binary avoids this limitation and provides full functionality.


## 📋 Package Information

- **Name**: `autenticacao-gov-pt-bin`
- **Version**: `3.13.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Middleware for Electronic Identification in Portugal (with precompiled binaries by AMA)
- **Homepage**: [https://www.autenticacao.gov.pt/](https://www.autenticacao.gov.pt/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @vaavaav


## 🔧 Build Information

- **Derivation Path**: `/nix/store/5n8ksap058d7ky9jb2wx02g2wmv2w62m-autenticacao-gov-pt-bin-3.13.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/au/autenticacao-gov-pt-bin/package.nix:142`
- **Outputs**:
  - `out`:  `/nix/store/5n8ksap058d7ky9jb2wx02g2wmv2w62m-autenticacao-gov-pt-bin-3.13.3`

## 🔗 Dependencies

- [[0dyaxjhz2kj25fissh5yj32khwz8crrz-qtbase-5.15.17]]
- [[19dkqq6j7z6ahjqgj3pa5wkkj6rl3wdg-auto-patchelf-hook]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[4b4zc0cg1hj290r7v12a7s5fyx0lfzfz-doxygen-1.14.0]]
- [[4d2dyxg7w6li9j537zfwrs09nxvq51js-openjpeg-2.5.2]]
- [[4dhrk0y3h7f7qgs499ma30zl4y704ij6-qttools-5.15.17]]
- [[5bhijahsrd19wgz9ckpqfdfgq445pbns-poppler-qt5-25.07.0]]
- [[5lmnv4qikhycr4942lvjrw8sbygckqrc-libzip-1.11.4]]
- [[67pxqa8a03ilch7k7s8pcwszdizjzm6z-flatpak-1.16.1]]
- [[6r5cldhv0mdkwwia0zdchk4aar0azvrd-gcc-14.3.0]]
- [[761d6f8hhrvq2qrbqc6ygxr3x34img28-libglvnd-1.7.0]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[8061mlnwgxjgx5mfn6mhphwd8y43qpih-autenticacao-gov-pt-bin.desktop]]
- [[81xmwh6rh602i4129llcajwgd6skb1xi-cjson-1.7.18]]
- [[9cv4msvdfd9rj3y9j0ykxxq5q67l8i09-xml-security-c-3.0.0]]
- [[akqzidn6pn6znsa34aw03ggxman9bi79-ostree-2025.2]]
- [[aysc2ird9l52sk3ww54d0dmasxx2ilrg-qtquickcontrols-5.15.17]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dhzxfkzgahp5z5x8svlcrxj3r5x825rc-patchelf-0.15.2]]
- [[fq23lcwc1p6ww77gxriaa7n57wva6mag-copy-desktop-items-hook]]
- [[g1smgp5dhq2ii8np7vm7n5znki3ak1b1-curl-8.14.1]]
- [[i2ndnh73galf6sak2gdj3fbfr7ac6ych-qtgraphicaleffects-5.15.17]]
- [[i7jgss4ziswp61yzj8m4ghspc0akyl4q-qtquickcontrols2-5.15.17]]
- [[j8inxbb61qp8bmwlzndxm6xzkw2h4qd1-ccid-1.6.2]]
- [[kpyf3mrdbkzlyplx2647wlpzvs1771wm-pteid-mw-3.13.3.flatpak]]
- [[nij7b8m89lwnb5k4kai7ycxq7bj1ps37-xerces-c-3.2.3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[r2db2qh3wxwmqd0615pzcixjcirgvj12-wrap-qt5-apps-hook]]
- [[r48wqvwdssqgvdmiak53raw5a193spbm-pcsclite-2.3.0]]
- [[w8cxzcyldgaqw6gyxas1di7bfk5yvzni-proot-5.4.0]]
- [[xrijb0laqrcb6kjyh714f5889pjzxpfk-openpace-1.1.3]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:42:33 UTC*
