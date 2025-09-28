---
aliases:
  - komodo
tags:
  - license/unknown
  - maintainers/r17x
  - outputs/out
---

# komodo

## 📝 Description

Komodo is a web app to provide structure for managing your servers, builds, deployments, and automated procedures.

With Komodo you can:
* Connect all of your servers, and alert on CPU usage, memory usage, and disk usage.
* Create, start, stop, and restart Docker containers on the connected servers, and view their status and logs.
* Deploy docker compose stacks. The file can be defined in UI, or in a git repo, with auto deploy on git push.
* Build application source into auto-versioned Docker images, auto built on webhook. Deploy single-use AWS instances for infinite capacity.
* Manage repositories on connected servers, which can perform automation via scripting / webhooks.
* Manage all your configuration / environment variables, with shared global variable and secret interpolation.
* Keep a record of all the actions that are performed and by whom.

Komodo is composed of a single core and any amount of connected servers running the periphery application.


## 📋 Package Information

- **Name**: `komodo`
- **Version**: `1.19.4`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tool to build and deploy software on many servers
- **Homepage**: [https://komo.do](https://komo.do)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv6l-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv64-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `powerpc-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `i686-windows`, `x86_64-windows`, `armv5tel-linux`, `armv7a-linux`, `m68k-linux`, `mips-linux`, `mips64-linux`, `mipsel-linux`, `mips64el-linux`, `riscv32-linux`, `armv6l-netbsd`, `mipsel-netbsd`, `riscv64-netbsd`, `x86_64-redox`, `wasm32-wasi`
## 👥 Maintainers

- @r17x


## 🔧 Build Information

- **Derivation Path**: `/nix/store/l25593pjjnv8z7fxjyxkhly1mjzm87dg-komodo-1.19.4.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ko/komodo/package.nix:28`
- **Outputs**:
  - `out`:  `/nix/store/l25593pjjnv8z7fxjyxkhly1mjzm87dg-komodo-1.19.4`

## 🔗 Dependencies

- [[0f5ann1sgwyp31vlfqqsnr95xzv3mzhf-cargo-1.89.0]]
- [[3bz4j2xzjl92yhiwfyhbz6gv4w1888bw-cargo-setup-hook.sh]]
- [[3chm95cnym9qmwxf4n5bgv6lnl1x950i-source]]
- [[3ndchkhlxxw50k7nd48i9zdkhsr57mwh-cargo-install-hook.sh]]
- [[4bycw2rdgf33gmn1z26knv8grxxh06w5-rustc-wrapper-1.89.0]]
- [[4cc0y6syxyxvjx1lh8ix60vxkly149fh-auditable-cargo-1.89.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[kmdiy73ss0xzq5yifg077wjj6fj8jjn1-komodo-1.19.4-vendor]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qi6337yh29r9ppqm262bf6vz0g13451b-cargo-build-hook.sh]]
- [[xqxbqs6qgnhvpkcai046s94jfrx8wb62-cargo-check-hook.sh]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:14:37 UTC*
