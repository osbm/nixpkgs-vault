---
aliases:
  - rwedid
tags:
  - license/unknown
  - outputs/out
---

# rwedid

## 📝 Description

To install udev rules, you also have to add `services.udev.packages = [ pkgs.rwedid ]` into your configuration.
Additionally you will also have to create the i2c group, on NixOS this can be done using `users.groups.i2c = {};`.
And you will have to load i2c-dev kernel module, for that add `boot.initrd.availableKernelModules = [ i2c-dev ] to your config.


## 📋 Package Information

- **Name**: `rwedid`
- **Version**: `0.3.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Read and write EDID data over an I2C bus
- **Homepage**: [https://codeberg.org/ral/rwedid](https://codeberg.org/ral/rwedid)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv6l-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv64-linux`, `s390x-linux`, `x86_64-linux`, `armv5tel-linux`, `armv7a-linux`, `m68k-linux`, `mips-linux`, `mips64-linux`, `mipsel-linux`, `mips64el-linux`, `riscv32-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/qkkv2hqawj99dgjm6csn02lzg71v3d57-rwedid-0.3.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/rw/rwedid/package.nix:41`
- **Outputs**:
  - `out`:  `/nix/store/qkkv2hqawj99dgjm6csn02lzg71v3d57-rwedid-0.3.2`

## 🔗 Dependencies

- [[02nvbmkaqzxp5jbnl7i1rcsj85r5cl5p-udev-check-hook]]
- [[0f5ann1sgwyp31vlfqqsnr95xzv3mzhf-cargo-1.89.0]]
- [[3bz4j2xzjl92yhiwfyhbz6gv4w1888bw-cargo-setup-hook.sh]]
- [[3ndchkhlxxw50k7nd48i9zdkhsr57mwh-cargo-install-hook.sh]]
- [[4bycw2rdgf33gmn1z26knv8grxxh06w5-rustc-wrapper-1.89.0]]
- [[4cc0y6syxyxvjx1lh8ix60vxkly149fh-auditable-cargo-1.89.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[iw7i7rklrzsglv5l2p8am46y9xa92s8r-xz-5.8.1]]
- [[km0irkn6gh11546z741l8w3l7gfk4nna-source]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qi6337yh29r9ppqm262bf6vz0g13451b-cargo-build-hook.sh]]
- [[xqxbqs6qgnhvpkcai046s94jfrx8wb62-cargo-check-hook.sh]]
- [[yb64b1ch29ihnr2s01dqm5faipa79vwf-rwedid-0.3.2-vendor]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:17:25 UTC*
