---
aliases:
  - linuxKernel.packages.linux_5_15.isgx
tags:
  - license/unknown
  - outputs/out
---

# linuxKernel.packages.linux_5_15.isgx

## 📝 Description

The linux-sgx-driver project (isgx) hosts an out-of-tree driver
for the Linux* Intel(R) SGX software stack, which would be used
until the driver upstreaming process is complete (before 5.11.0).

It is used to support Enhanced Privacy Identification (EPID)
based attestation on the platforms without Flexible Launch Control.


## 📋 Package Information

- **Name**: `linuxKernel.packages.linux_5_15.isgx`
- **Version**: `2.14-5.15.193`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Intel SGX Linux Driver
- **Homepage**: [https://github.com/intel/linux-sgx-driver](https://github.com/intel/linux-sgx-driver)
- **License**: `unknown`
- **Platforms**: `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/7ab2idzy0nfyc46nh2k7l4swwy6hdbjw-isgx-2.14-5.15.193.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/isgx/default.nix:36`
- **Outputs**:
  - `out`:  `/nix/store/7ab2idzy0nfyc46nh2k7l4swwy6hdbjw-isgx-2.14-5.15.193`

## 🔗 Dependencies

- [[0i6l8h1ds9dkr1ivc77hzsdl51mfahm0-pahole-1.30]]
- [[1arldm9b7al3nimanggan91gsjxql1yb-linux-5.15.193]]
- [[3zmkarn19nr1njibrysbgry6vck5497b-uname]]
- [[96vv66p4biczw55qf9jhwqn7awwn861h-elfutils-0.193]]
- [[ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[k7m71npibz03269ks6whdcqv3dch849q-source]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:10:41 UTC*
