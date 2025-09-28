---
aliases:
  - tfk8s
tags:
  - license/unknown
  - maintainers/bryanasdev000
  - outputs/out
---

# tfk8s

## 📝 Description

tfk8s is a tool that makes it easier to work with the Terraform Kubernetes Provider.
If you want to copy examples from the Kubernetes documentation or migrate existing YAML manifests and use them with Terraform without having to convert YAML to HCL by hand, this tool is for you.
Features:
* Convert a YAML file containing multiple manifests.
* Strip out server side fields when piping kubectl get $R -o yaml | tfk8s --strip


## 📋 Package Information

- **Name**: `tfk8s`
- **Version**: `0.1.10`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Utility to convert Kubernetes YAML manifests to Terraform's HCL format
- **Homepage**: [https://github.com/jrhouston/tfk8s/](https://github.com/jrhouston/tfk8s/)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @bryanasdev000


## 🔧 Build Information

- **Derivation Path**: `/nix/store/816zg5hzdxbajcg9j0mjgdpkzhybf3iz-tfk8s-0.1.10.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/tf/tfk8s/package.nix:41`
- **Outputs**:
  - `out`:  `/nix/store/816zg5hzdxbajcg9j0mjgdpkzhybf3iz-tfk8s-0.1.10`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[br9iz1hn1h2d2ssn08fwfcx55zga4avi-tfk8s-0.1.10-go-modules]]
- [[dd49hw9ygcqkpx8330iwwky0ymfh3kh8-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:09:03 UTC*
