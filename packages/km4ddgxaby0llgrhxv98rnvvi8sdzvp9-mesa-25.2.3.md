---
aliases:
  - mesa
tags:
  - license/unknown
  - maintainers/K900
  - maintainers/vcunat
  - outputs/cross_tools
  - outputs/debug
  - outputs/opencl
  - outputs/out
  - outputs/spirv2dxil
---

# mesa

## 📝 Description

The Mesa project began as an open-source implementation of the OpenGL
specification - a system for rendering interactive 3D graphics. Over the
years the project has grown to implement more graphics APIs, including
OpenGL ES (versions 1, 2, 3), OpenCL, OpenMAX, VDPAU, VA API, XvMC, and
Vulkan.  A variety of device drivers allows the Mesa libraries to be used
in many different environments ranging from software emulation to
complete hardware acceleration for modern GPUs.


## 📋 Package Information

- **Name**: `mesa`
- **Version**: `25.2.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Open source 3D graphics library
- **Homepage**: [https://www.mesa3d.org/](https://www.mesa3d.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @K900
- @vcunat


## 🔧 Build Information

- **Derivation Path**: `/nix/store/km4ddgxaby0llgrhxv98rnvvi8sdzvp9-mesa-25.2.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/libraries/mesa/common.nix:19`
- **Outputs**:
  - `cross_tools`:  `/nix/store/km4ddgxaby0llgrhxv98rnvvi8sdzvp9-mesa-25.2.3`
  - `debug`:  `/nix/store/km4ddgxaby0llgrhxv98rnvvi8sdzvp9-mesa-25.2.3`
  - `opencl`:  `/nix/store/km4ddgxaby0llgrhxv98rnvvi8sdzvp9-mesa-25.2.3`
  - `out`:  `/nix/store/km4ddgxaby0llgrhxv98rnvvi8sdzvp9-mesa-25.2.3`
  - `spirv2dxil`:  `/nix/store/km4ddgxaby0llgrhxv98rnvvi8sdzvp9-mesa-25.2.3`

## 🔗 Dependencies

- [[02l2mwk9x35ww8hq6m836yrcy0ma7js8-wayland-1.24.0]]
- [[0y20y5glzrd67xskzh9vjindzjl1jiiv-bison-3.8.2]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[26chxy5flgiklyms9f6j4cfwr1pgdjb7-libvdpau-1.5]]
- [[2fbx94cnniix1a6h9b265icc5syn829m-libxfixes-6.0.1]]
- [[2nf9x9f81s47xi0g4pzqqhvwzqxz3k4r-mesa-libgbm-25.1.0]]
- [[3aflm58fw2kw8nkcnns7h4lgmrdf5hp8-xorgproto-2024.1]]
- [[3x5bmlv641xm5s1hk1nj4ffr0nk7vw2p-wayland-protocols-1.45]]
- [[3zc6j1j1qgis43ig9m9gl11iqf058s76-systemd-minimal-libs-257.8]]
- [[4bycw2rdgf33gmn1z26knv8grxxh06w5-rustc-wrapper-1.89.0]]
- [[5h6ng7076xwc5ckiy5m6bqhnh6r7ylqr-clang-wrapper-19.1.7]]
- [[6b5cgp72v8vd6812ysrwb3kj4ijakaq3-llvm-19.1.7]]
- [[761d6f8hhrvq2qrbqc6ygxr3x34img28-libglvnd-1.7.0]]
- [[77fx3zgcfw9vhnkr9qhjrmh2krq307i7-clang-19.1.7]]
- [[78dsyck3j6f9za4mq0dcsv93xkbdp7qm-libxcb-keysyms-0.4.1]]
- [[96vv66p4biczw55qf9jhwqn7awwn861h-elfutils-0.193]]
- [[a1c87x457x2ihr4w5gv1ib3g33m5gyyc-vulkan-loader-1.4.321.0]]
- [[a8lks340bd5pdbnh7cwcq6fmyhrdxsai-file-5.45]]
- [[aj35hmramjk714nr632xb68wadb8xlh1-rust-bindgen-hook]]
- [[ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7]]
- [[b1bwyigh5a5hcplrjjl5lk9627mcslqh-python3.13-ply-3.11]]
- [[bbss0z43bnyiyj0agndriw9jckcnnmnv-glslang-15.4.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bsdfb2xa35m8s4g8fc3brby8xcrlr0n5-libunwind-1.8.2]]
- [[cclxcnnzf8vhj305xkaw53mrc0rlbllz-mesa-rust-package-cache]]
- [[cd56a322lpm3b87vrakh19zilzc7xr43-lm-sensors-3.6.2]]
- [[cv9zjk6dmhybvxdx0k17z0gk7fc6q03b-python3.13-pycparser-2.22]]
- [[d99f4z55b6p4hx1wfl4r6d6i0zi5bh7m-libxext-1.3.6]]
- [[dirkc1gc5niy49dn25d8kgj6r6gp1iqr-valgrind-3.25.1]]
- [[f368fizl82c6krd1a5gcxp0m6m4zd474-intltool-0.51.0]]
- [[g3hqzmvacvl22hag8qr8q3pm4k1kmj48-SPIRV-LLVM-Translator-19.1.10]]
- [[ghg8rgqmnrnx9xfawhji55a5sdgszgpa-libclc-19.1.7]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[i9kj1nhzkg91xsq8ny4z4hipl0b42kad-gcc-wrapper-14.3.0]]
- [[jj8qhy2syshyn6kh6zms8n84rq15iqyf-jdupes-1.29.0]]
- [[jzqrar4nr92a8yixlffrihmlnwrfkhqx-spirv-tools-1.4.321.0]]
- [[kgdq9f42qlk24s461xvbqi12gcl3krry-libxcb-1.17.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[lwn2d0w4fz7nssair94d5y8kgaz9qjcf-libva-minimal-2.22.0]]
- [[m386d08apkwq70xz2jr4ykc1c19y6gp1-libxshmfence-1.3.3]]
- [[mbx1ynqv3fp2905hd931c5vfai1aa7nz-libxxf86vm-1.1.6]]
- [[mzg1vkyzabv01ja719b3zj9hzwkzhyk2-libpng-apng-1.6.49]]
- [[nlpmfx8yjpxg73b8rlbc1hljs5m4gmqc-rust-bindgen-0.72.0]]
- [[nncd4f9vl1alqwmiff6a138ppbsgbp5l-libx11-1.8.12]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q8a0b0p3mkzxkf76mhzy1qmk50zsknxn-source]]
- [[qlprvz2a7x7m36jbj77rc0n634ifvh4w-rust-cbindgen-0.29.0]]
- [[qygi1zn1hf1x0k551m6fj8pnw4l9zvpl-mesa-gl-headers-25.1.0]]
- [[qzl8kni5a4xh81ampjh16cj72gkw4j4b-expat-2.7.1]]
- [[rbjsvyngabldcxkvh1bqis3jaiy29x2j-wayland-scanner-1.24.0]]
- [[rvsgycjzldbgg1l9f6bxrdncx02va128-libxrandr-1.5.4]]
- [[snbfinsd48w01hi51bzzpdl7m5n1cwif-libdrm-2.4.125]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]
- [[wg5y3m50pr5mjw7r51dlayap4rq4zlqx-python3.13-packaging-25.0]]
- [[wxpbqgs01rjnbca1lwnva0xc4vkb7181-python3.13-mako-1.3.10]]
- [[wy61x67y125m36dp7l7xhzqbi30mxg1d-flex-2.6.4]]
- [[yx9ag0icz7v1fbkq3an2658q40b7cgd2-python3.13-pyyaml-6.0.2]]
- [[zq83iiy92h5kpvqw0ysspkq260xxzahj-directx-headers-1.616.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/r989dk196nl9frhnfsa1lb7knhbyjxw6-separate-debug-info.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/yvb6nas9kf8p74aal4bq4nk4kdlws5sd-opencl.patch`

---
*Generated on 2025-09-27 12:18:59 UTC*
