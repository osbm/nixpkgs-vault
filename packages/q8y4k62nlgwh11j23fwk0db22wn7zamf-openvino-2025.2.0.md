---
aliases:
  - openvino
tags:
  - license/unknown
  - maintainers/tfmoraes
  - outputs/out
  - outputs/python
---

# openvino

## 📝 Description

This toolkit allows developers to deploy pre-trained deep learning models through a high-level C++ Inference Engine API integrated with application logic.

This open source version includes several components: namely Model Optimizer, nGraph and Inference Engine, as well as CPU, GPU, MYRIAD,
multi device and heterogeneous plugins to accelerate deep learning inferencing on Intel® CPUs and Intel® Processor Graphics.
It supports pre-trained models from the Open Model Zoo, along with 100+ open source and public models in popular formats such as Caffe*, TensorFlow*, MXNet* and ONNX*.


## 📋 Package Information

- **Name**: `openvino`
- **Version**: `2025.2.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Open-source toolkit for optimizing and deploying AI inference
- **Homepage**: [https://docs.openvinotoolkit.org/](https://docs.openvinotoolkit.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @tfmoraes


## 🔧 Build Information

- **Derivation Path**: `/nix/store/q8y4k62nlgwh11j23fwk0db22wn7zamf-openvino-2025.2.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/op/openvino/package.nix:182`
- **Outputs**:
  - `out`:  `/nix/store/q8y4k62nlgwh11j23fwk0db22wn7zamf-openvino-2025.2.0`
  - `python`:  `/nix/store/q8y4k62nlgwh11j23fwk0db22wn7zamf-openvino-2025.2.0`

## 🔗 Dependencies

- [[19dkqq6j7z6ahjqgj3pa5wkkj6rl3wdg-auto-patchelf-hook]]
- [[1xj4n96lxln8xknngqrl1bqmdkyvfjpz-pugixml-1.15]]
- [[3h2pqwsp2izzlynp9gjar39hm70nnz89-libxml2-2.14.5]]
- [[41s84g5y48afa0w1df9rjz6sny3k464r-protobuf-32.0]]
- [[8g5wg89i6f6lkwg96qnzy471hhsd14b3-flatbuffers-25.2.10]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[ca06pjvdmc5ckxnmppbz2f82l2q5bxn9-scons-4.7.0]]
- [[dhzxfkzgahp5z5x8svlcrxj3r5x825rc-patchelf-0.15.2]]
- [[f3px4g3z55abqdk56d18cfgh7a7gfc0n-python3-3.13.7-env]]
- [[fcmb190sh4glwkjmww12ibdakqdqs4j6-add-driver-runpath]]
- [[fy9wjrqf0pzd5x3rvy665v50ff747wfd-libusb-1.0.29]]
- [[kygr48kczkaybgr07cdr733hxz105xza-level-zero-1.24.2]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[nbs4s89xwvhfw78i1k44qn1w084264dy-libarchive-3.8.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qsm8q9gyyhacv5p8p042kk6rg8nyjlxk-gflags-2.2.2]]
- [[s03113vgzz1kmhzl74nq55k2gzp9s1v5-snappy-1.2.2]]
- [[sqpads7mr48rxqrxvxjkg8rsymk1m3bw-ocl-icd-2.3.3]]
- [[sv4sbm2qf07z0s9f05mkx8wj5czxh4hb-tbb-2022.2.0]]
- [[vwhc7pjh7shcbgc2qgda5b0hrx9frq66-opencv-4.12.0]]
- [[w07r84zv4l2r6qpa587ia91rgs9zjksj-source]]
- [[w4mzg3m4675p901k75nqindlq2f54xc2-tbbbind_2_5_static_lin_v4.tgz]]
- [[w8ak9a7r519g5zb7mvcr4cfw0f1w2rrs-shellcheck-0.10.0]]
- [[yyw6nzfcdckb36blm5mf5b5mss1m9asq-git-2.51.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:00:56 UTC*
