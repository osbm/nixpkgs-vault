---
aliases:
  - linuxKernel.packages.linux_5_15.kvmfr
tags:
  - license/unknown
  - maintainers/j-brn
  - outputs/out
---

# linuxKernel.packages.linux_5_15.kvmfr

## 📝 Description

This kernel module implements a basic interface to the IVSHMEM device for LookingGlass when using LookingGlass in VM->VM mode
Additionally, in VM->host mode, it can be used to generate a shared memory device on the host machine that supports dmabuf


## 📋 Package Information

- **Name**: `linuxKernel.packages.linux_5_15.kvmfr`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Optional kernel module for LookingGlass
- **Homepage**: [https://github.com/gnif/LookingGlass](https://github.com/gnif/LookingGlass)
- **License**: `unknown`
- **Platforms**: `x86_64-linux`
## 👥 Maintainers

- @j-brn


## 🔧 Build Information

- **Derivation Path**: `/nix/store/j852b5hqs44m4gs1v4fzxclzxc0dlmp1-kvmfr-B7.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/kvmfr/default.nix:31`
- **Outputs**:
  - `out`:  `/nix/store/j852b5hqs44m4gs1v4fzxclzxc0dlmp1-kvmfr-B7`

## 🔗 Dependencies

- [[0i6l8h1ds9dkr1ivc77hzsdl51mfahm0-pahole-1.30]]
- [[1arldm9b7al3nimanggan91gsjxql1yb-linux-5.15.193]]
- [[3zmkarn19nr1njibrysbgry6vck5497b-uname]]
- [[4h4kxaqs9khj2qy8dmcpwva546rmh83j-source]]
- [[6r5cldhv0mdkwwia0zdchk4aar0azvrd-gcc-14.3.0]]
- [[8qvzhry004aybdbrb9y8c387ah9k0mps-binutils-2.44]]
- [[96vv66p4biczw55qf9jhwqn7awwn861h-elfutils-0.193]]
- [[ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i9kj1nhzkg91xsq8ny4z4hipl0b42kad-gcc-wrapper-14.3.0]]
- [[kvysay8plzjaxgvj64sxz0b4d9xc25n0-binutils-wrapper-2.44]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:10:47 UTC*
