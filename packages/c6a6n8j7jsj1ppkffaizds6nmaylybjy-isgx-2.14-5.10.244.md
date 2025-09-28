---
aliases:
  - linuxKernel.packages.linux_5_10.isgx
tags:
  - license/unknown
  - outputs/out
---

# linuxKernel.packages.linux_5_10.isgx

## 📝 Description

The linux-sgx-driver project (isgx) hosts an out-of-tree driver
for the Linux* Intel(R) SGX software stack, which would be used
until the driver upstreaming process is complete (before 5.11.0).

It is used to support Enhanced Privacy Identification (EPID)
based attestation on the platforms without Flexible Launch Control.


## 📋 Package Information

- **Name**: `linuxKernel.packages.linux_5_10.isgx`
- **Version**: `2.14-5.10.244`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Intel SGX Linux Driver
- **Homepage**: [https://github.com/intel/linux-sgx-driver](https://github.com/intel/linux-sgx-driver)
- **License**: `unknown`
- **Platforms**: `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/c6a6n8j7jsj1ppkffaizds6nmaylybjy-isgx-2.14-5.10.244.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/isgx/default.nix:36`
- **Outputs**:
  - `out`:  `/nix/store/c6a6n8j7jsj1ppkffaizds6nmaylybjy-isgx-2.14-5.10.244`

## 🔗 Dependencies

- [[0i6l8h1ds9dkr1ivc77hzsdl51mfahm0-pahole-1.30]]
- [[96vv66p4biczw55qf9jhwqn7awwn861h-elfutils-0.193]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[i52hspb5kjvv64r3vvrakkxpxbnm427h-uname]]
- [[k7m71npibz03269ks6whdcqv3dch849q-source]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[nqmkpnqndz61y4yr6yxbm1byyi854vwj-linux-5.10.244]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:08:06 UTC*
