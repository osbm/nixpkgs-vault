---
aliases:
  - tcb
tags:
  - license/unknown
  - maintainers/Izorkin
  - outputs/bin
  - outputs/dev
  - outputs/man
  - outputs/out
---

# tcb

## 📝 Description

The tcb package contains core components of our tcb suite implementing the alternative
password shadowing scheme on Openwall GNU Linux (Owl). It is being made available
separately from Owl primarily for use by other distributions.

The package consists of three components: pam_tcb, libnss_tcb, and libtcb.

pam_tcb is a PAM module which supersedes pam_unix. It also implements the tcb password
shadowing scheme. The tcb scheme allows many core system utilities (passwd(1) being
the primary example) to operate with little privilege. libnss_tcb is the accompanying
NSS module. libtcb contains code shared by the PAM and NSS modules and is also used
by user management tools on Owl due to our shadow suite patches.


## 📋 Package Information

- **Name**: `tcb`
- **Version**: `1.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Alternative password shadowing scheme
- **Homepage**: [https://www.openwall.com/tcb/](https://www.openwall.com/tcb/)
- **License**: `unknown`
## 👥 Maintainers

- @Izorkin


## 🔧 Build Information

- **Derivation Path**: `/nix/store/aii85bbf19ljim8dkm6jaajr1qyddfbg-tcb-1.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/tc/tcb/package.nix:48`
- **Outputs**:
  - `bin`:  `/nix/store/aii85bbf19ljim8dkm6jaajr1qyddfbg-tcb-1.2`
  - `dev`:  `/nix/store/aii85bbf19ljim8dkm6jaajr1qyddfbg-tcb-1.2`
  - `man`:  `/nix/store/aii85bbf19ljim8dkm6jaajr1qyddfbg-tcb-1.2`
  - `out`:  `/nix/store/aii85bbf19ljim8dkm6jaajr1qyddfbg-tcb-1.2`

## 🔗 Dependencies

- [[1fwhb9gn57lrzc3yq4c82hxjwi3rc2yp-source]]
- [[3kgj31l4fhkbp0s74bzl7zvrr1v6aymc-libxcrypt-4.4.38]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[jrpjbaj5dm8dnfcyvh4akyhfmq0cxbm9-linux-pam-1.7.1]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/a02c49gvnrgg0fs1cw2c62g2q1q338ad-fix-makefiles.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:04:23 UTC*
