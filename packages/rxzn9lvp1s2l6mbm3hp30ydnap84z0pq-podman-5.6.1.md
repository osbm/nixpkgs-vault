---
aliases:
  - podman
tags:
  - license/unknown
  - maintainers/saschagrunert
  - maintainers/vdemeester
  - outputs/man
  - outputs/out
---

# podman

## 📝 Description

Podman (the POD MANager) is a tool for managing containers and images, volumes mounted into those containers, and pods made from groups of containers. Podman runs containers on Linux, but can also be used on Mac and Windows systems using a Podman-managed virtual machine. Podman is based on libpod, a library for container lifecycle management that is also contained in this repository. The libpod library provides APIs for managing containers, pods, container images, and volumes.

To install on NixOS, please use the option `virtualisation.podman.enable = true`.


## 📋 Package Information

- **Name**: `podman`
- **Version**: `5.6.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Program for managing pods, containers and container images
- **Homepage**: [https://podman.io/](https://podman.io/)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @saschagrunert
- @vdemeester


## 🔧 Build Information

- **Derivation Path**: `/nix/store/rxzn9lvp1s2l6mbm3hp30ydnap84z0pq-podman-5.6.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/po/podman/package.nix:191`
- **Outputs**:
  - `man`:  `/nix/store/rxzn9lvp1s2l6mbm3hp30ydnap84z0pq-podman-5.6.1`
  - `out`:  `/nix/store/rxzn9lvp1s2l6mbm3hp30ydnap84z0pq-podman-5.6.1`

## 🔗 Dependencies

- [[1mxyv5wmnq0srsx19piaadpqdd21p07r-writable-tmpdir-as-home-hook]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[2qc1404yli6scnns5c56l6v3810nxr98-gpgme-1.24.3]]
- [[3sbg89qzpa2lvjl41qjyvdna5hap16hm-btrfs-progs-6.16]]
- [[3z6dcp2i69nn7h8kwl6snf651i7ds14v-util-linux-minimal-2.41.1]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[7vdbddkdp8216ybjl871clyphzgw8la1-hardcode-paths.patch]]
- [[81p9r489wji8jl1kh2pabf4x0vx6qq8k-fuse-overlayfs-1.15]]
- [[8bk0s9hp267kv3khm8zkx9xmn0l74zls-lvm2-2.03.33]]
- [[9qnjgd5vx73f8ibl1fpjhzvkyfawrwfj-iptables-1.8.11]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bn7fmval2g8p40ly3wqkfnmd8xn6aafh-nftables-1.1.4]]
- [[dzynf7h9bw2qvzwkzm5kmjbgqzpsxj00-systemd-257.8]]
- [[ihs4zi9b9qjbzi2f4bc5wp5qi03ihjcq-podman-helper-binary-wrapper]]
- [[jvk6w0wmh9f50wh0xr7mb7faz9ipbmzv-libseccomp-2.6.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[lzvy25g887aypn07ah8igv72z7b9jb88-version-check-hook]]
- [[m5a42w4y0ln730pba8bv7yszr85lwvy8-go-md2man-2.0.7]]
- [[mc983csj0fvcg5gf5gwhvmi4a9v3jajq-iproute2-6.16.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[w330p370yzw3c5icrdm7n0jspcicv7qv-libselinux-3.8.1]]
- [[yaqjighs4lfc4bvdjk6jp6b7g9n2drdw-source]]
- [[ylw29jpaama2xqrbyfzpgnmwjxc6mynj-libapparmor-4.1.1]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/bjzcwsag5vk5imzs480mnd6xzwn2y4ff-rm-podman-mac-helper-msg.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:18:16 UTC*
