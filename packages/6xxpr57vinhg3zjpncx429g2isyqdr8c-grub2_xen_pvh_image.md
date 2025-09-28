---
aliases:
  - grub2_pvhgrub_image
tags:
  - license/unknown
  - maintainers/hehongbo
  - maintainers/CertainLach
  - maintainers/SigmaSquadron
  - maintainers/digitalrane
  - outputs/out
---

# grub2_pvhgrub_image

## 📝 Description

This package provides a prebuilt PvGrub2 image for booting PVH Xen
guests (also commonly referred to as PvhGrub2), which searches for
`grub.cfg` on the guest disk and interprets it to load the kernel,
eliminating the need to copy the guest kernel to the Dom0.

You will need `pkgs.grub2_xen_pvh` to build a customized PvhGrub2
image. See [PvGrub2](https://wiki.xenproject.org/wiki/PvGrub2) for
more explanations.


## 📋 Package Information

- **Name**: `grub2_pvhgrub_image`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: PvGrub2 image for booting PVH Xen guests
- **License**: `unknown`
- **Platforms**: `i686-linux`, `x86_64-linux`
## 👥 Maintainers

- @hehongbo
- @CertainLach
- @SigmaSquadron
- @digitalrane


## 🔧 Build Information

- **Derivation Path**: `/nix/store/6xxpr57vinhg3zjpncx429g2isyqdr8c-grub2_xen_pvh_image.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/gr/grub2_pvhgrub_image/package.nix:52`
- **Outputs**:
  - `out`:  `/nix/store/6xxpr57vinhg3zjpncx429g2isyqdr8c-grub2_xen_pvh_image`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[g570p5xz4jzddpqaxy885v1y8gvqb3fy-grub-2.12]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/fizwvvidr2h3d2yc7li4v0y3l1ndn0ly-configs`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:58:15 UTC*
