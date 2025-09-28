---
aliases:
  - smc-fuzzer
tags:
  - not-available
  - license/unknown
  - maintainers/hraban
  - outputs/out
---

# smc-fuzzer

## 📝 Description

smc-fuzzer uses the AppleSMC IOKit interface and a userland API for
interacting with the System Management Controller (Mac embedded
controllers). The tool focuses on the SMC key/value API.

smc-fuzzer is not just useful for fuzzing the SMC itself: it can also be
used to explicitly control or query the SMC.  That makes it useful in
system management, e.g. controlling and querying the charge status of an
Apple laptop.


## 📋 Package Information

- **Name**: `smc-fuzzer`
- **Version**: `0-unstable-2020-12-23`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Apple SMC (System Management Controller) API fuzzer
- **Homepage**: [https://github.com/theopolis/smc-fuzzer](https://github.com/theopolis/smc-fuzzer)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`
## 👥 Maintainers

- @hraban


## 🔧 Build Information

- **Derivation Path**: `/nix/store/zk5hjwrrma1m0hljk0w3iapjbvkf2j77-smc-fuzzer-0-unstable-2020-12-23.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sm/smc-fuzzer/package.nix:28`
- **Outputs**:
  - `out`:  `/nix/store/zk5hjwrrma1m0hljk0w3iapjbvkf2j77-smc-fuzzer-0-unstable-2020-12-23`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pcy25f557lbsaki3kk2pk0m8w02a59hy-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:13:15 UTC*
