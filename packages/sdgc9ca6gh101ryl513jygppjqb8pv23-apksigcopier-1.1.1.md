---
aliases:
  - apksigcopier
tags:
  - license/unknown
  - maintainers/obfusk
  - outputs/dist
  - outputs/out
---

# apksigcopier

## 📝 Description

apksigcopier is a tool for copying android APK signatures from a signed
APK to an unsigned one (in order to verify reproducible builds).
It can also be used to compare two APKs with different signatures.
Its command-line tool offers four operations:

* copy signatures directly from a signed to an unsigned APK
* extract signatures from a signed APK to a directory
* patch previously extracted signatures onto an unsigned APK
* compare two APKs with different signatures (requires apksigner)


## 📋 Package Information

- **Name**: `apksigcopier`
- **Version**: `1.1.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Copy/extract/patch android apk signatures & compare APKs
- **Homepage**: [https://github.com/obfusk/apksigcopier](https://github.com/obfusk/apksigcopier)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @obfusk


## 🔧 Build Information

- **Derivation Path**: `/nix/store/sdgc9ca6gh101ryl513jygppjqb8pv23-apksigcopier-1.1.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ap/apksigcopier/package.nix:65`
- **Outputs**:
  - `dist`:  `/nix/store/sdgc9ca6gh101ryl513jygppjqb8pv23-apksigcopier-1.1.1`
  - `out`:  `/nix/store/sdgc9ca6gh101ryl513jygppjqb8pv23-apksigcopier-1.1.1`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[6ijpnbfpx4f261l8bsdk19n2jvgdzhwk-python3.13-click-8.1.8]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[dnbzpphxbd6h31n44gfwbg1qf9q03wcr-pypa-build-hook.sh]]
- [[fmgak3lvqw3ff8wym1v40kgi0b5i1iza-python-runtime-deps-check-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[iynj9ds54c4wd9k0qp8228n6dyqqhidy-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[v28sdl3535sxb6a71z5faqdzbns9pv0h-bash-interactive-5.3p3]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]
- [[zb5cj6gmxg0g561dg8vkmb4sb67z2b07-pandoc-cli-3.6]]
- [[zrbsw1zi6njaj1m14vmzr42n8x7ig46r-apksigner-35.0.6]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:50:33 UTC*
