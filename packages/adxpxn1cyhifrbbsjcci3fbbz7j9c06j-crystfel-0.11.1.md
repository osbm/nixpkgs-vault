---
aliases:
  - crystfel-headless
tags:
  - license/unknown
  - maintainers/pmiddend
  - outputs/out
---

# crystfel-headless

## 📝 Description

CrystFEL is a suite of programs for processing (and simulating) Bragg diffraction data from "serial crystallography" experiments, often (but not always) performed using an X-ray Free-Electron Laser. Compared to rotation data, some of the particular characteristics of such data which call for a specialised software suite are:

- The sliced, rather than integrated, measurement of intensity data. Many, if not all reflections are partially integrated.
- Many patterns (thousands) are required - high throughput is needed.
- The crystal orientations in each pattern are random and uncorrelated.
- Merging into lower symmetry point groups may require the resolution of indexing ambiguities.

## 📋 Package Information

- **Name**: `crystfel-headless`
- **Version**: `0.11.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Data processing for serial crystallography
- **Homepage**: [https://www.desy.de/~twhite/crystfel/](https://www.desy.de/~twhite/crystfel/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @pmiddend


## 🔧 Build Information

- **Derivation Path**: `/nix/store/adxpxn1cyhifrbbsjcci3fbbz7j9c06j-crystfel-0.11.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/applications/science/physics/crystfel/default.nix:280`
- **Outputs**:
  - `out`:  `/nix/store/adxpxn1cyhifrbbsjcci3fbbz7j9c06j-crystfel-0.11.1`

## 🔗 Dependencies

- [[04w0i6q9ancv4lpw6l8vmjwr2liffkp0-hdf5-cpp-1.14.6]]
- [[085xlrjn483h686si07j1k4s89hakmgz-fftw-double-3.3.10]]
- [[0y20y5glzrd67xskzh9vjindzjl1jiiv-bison-3.8.2]]
- [[1wxqpa87qfwq8ds171xvdr1yd3p2djfg-HDF5-External-Filter-Plugins-0.1.0]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[2w9nraa280rkaaqsc7ypj8qazw6mqial-xgandalf-c6c5003ff1086e8c0fb5313660b4f02f3a3aab7b]]
- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[400lmk874s7nnlc8wb9xib57skqb8phm-millepede-ii-04-13-06]]
- [[4b4zc0cg1hj290r7v12a7s5fyx0lfzfz-doxygen-1.14.0]]
- [[571bsf4j7cn27yis3c26q79a2jqgdimh-gsl-2.8]]
- [[7n2pz0nkmgkblaspivmmsjv26m4bf9gd-crystfel-0.11.1.tar.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[jh2a9ln938r8fv0vicy0f71snzq4hv48-msgpack-3.3.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[p8nqd9184zyxw9b6hwj6jw003fxvwrc3-fdip-5628fedddd79323b4b26df9b85e9543d83286d4c]]
- [[sahgidh7y72va070agyk3fl6icrf171i-libccp4-8.0.0]]
- [[sqpads7mr48rxqrxvxjkg8rsymk1m3bw-ocl-icd-2.3.3]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]
- [[vp8qbxr2glranp70rdxnkxbh80di5rqi-mosflm-7.4.0]]
- [[wy61x67y125m36dp7l7xhzqbi30mxg1d-flex-2.6.4]]
- [[xdyid0ccd5zj7s88mclgmhbaiglghawa-pinkindexer-15caa21191e27e989b750b29566e4379bc5cd21a]]
- [[ysiwz2c63w8r2azy7bl2zgfnvmqi849i-opencl-headers-2025.07.22]]
- [[zb5cj6gmxg0g561dg8vkmb4sb67z2b07-pandoc-cli-3.6]]
- [[zjvcv40pq35s9hsjag9kbg9n896914d3-zeromq-4.3.5]]

## 📁 Input Sources

- `/nix/store/fcxspmmy06w07jg81mrp68zxnl21p1ry-link-to-argp-standalone-if-needed.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:59:14 UTC*
