---
aliases:
  - djview
tags:
  - license/unknown
  - maintainers/Anton-Latukha
  - maintainers/bryango
  - outputs/man
  - outputs/out
---

# djview

## 📝 Description

The portable DjVu viewer (Qt5) and browser (nsdejavu) plugin.

Djview highlights:
  - entirely based on the public DjVulibre api.
  - entirely written in portable Qt5.
  - works natively under Unix/X11, MS Windows, and macOS X.
  - continuous scrolling of pages
  - side-by-side display of pages
  - ability to specify a url to the djview command
  - all plugin and cgi options available from the command line
  - all silly annotations implemented
  - display thumbnails as a grid
  - display outlines
  - page names supported (see djvused command set-page-title)
  - metadata dialog (see djvused command set-meta)
  - implemented as reusable Qt widgets

nsdejavu: browser plugin for DjVu. It internally uses djview.
Has CGI-style arguments to configure the view of document (see man).


## 📋 Package Information

- **Name**: `djview`
- **Version**: `4.12.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Portable DjVu viewer (Qt5)
- **Homepage**: [https://djvu.sourceforge.net/djview4.html](https://djvu.sourceforge.net/djview4.html)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @Anton-Latukha
- @bryango


## 🔧 Build Information

- **Derivation Path**: `/nix/store/n15f7ml7k19mkgii64ry1ajf7jbypw4z-djview-4.12.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/dj/djview/package.nix:72`
- **Outputs**:
  - `man`:  `/nix/store/n15f7ml7k19mkgii64ry1ajf7jbypw4z-djview-4.12.3`
  - `out`:  `/nix/store/n15f7ml7k19mkgii64ry1ajf7jbypw4z-djview-4.12.3`

## 🔗 Dependencies

- [[0dyaxjhz2kj25fissh5yj32khwz8crrz-qtbase-5.15.17]]
- [[1l1lk431imzsf7jhqxqkf5kcj4p4da8p-libtiff-4.7.0]]
- [[4dhrk0y3h7f7qgs499ma30zl4y704ij6-qttools-5.15.17]]
- [[7ys6vrd29swy0hb42rbhrc1sbsk4cq1g-autoconf-2.72]]
- [[82mw0nl5kb1zw36l4s4d0pdlfiadwlss-automake-1.18.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[f2zlnw16484q5c9hi6fjnmbiimskrwsg-libxt-1.3.1]]
- [[h92afmr4a0b7r3lymjwm2p1qirl7n0mv-djview-4.12.3.tar.gz]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[r2db2qh3wxwmqd0615pzcixjcirgvj12-wrap-qt5-apps-hook]]
- [[sv8lxxb30bqw2b360ni6rsp89mg2dvbp-libtool-2.5.4]]
- [[vw603f6gg15b6ylpsr02v3zvgifk7lvr-djvulibre-3.5.29]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:47:11 UTC*
