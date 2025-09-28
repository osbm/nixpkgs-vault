---
aliases:
  - ankiAddons.local-audio-yomichan
tags:
  - license/unknown
  - maintainers/junestepp
  - outputs/out
---

# ankiAddons.local-audio-yomichan

## 📝 Description

This add-on must be configured with an audio collection.

Example:

```nix
pkgs.ankiAddons.local-audio-yomichan.withConfig {
  userFiles =
    let
      audio-collection =
        pkgs.runCommand "local-yomichan-audio-collection"
          {
            outputHashMode = "recursive";
            outputHash = "sha256-NxbcXh2SDPfCd+ZHAWT5JdxRecNbT4Xpo0pxX5/DOfo=";

            src = pkgs.requireFile {
              name = "local-yomichan-audio-collection-2023-06-11-opus.tar.xz";
              url = "https://github.com/yomidevs/local-audio-yomichan?tab=readme-ov-file#steps";
              sha256 = "1xsxp8iggklv77rj972mqaa1i8f9hvr3ir0r2mwfqcdz4q120hr1";
            };
          }
          ''
            mkdir -p $out
            cd $out
            tar -xf "$src"
          '';
    in
    "${audio-collection}/user_files";
}
```


## 📋 Package Information

- **Name**: `ankiAddons.local-audio-yomichan`
- **Version**: `0-unstable-2025-04-26`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Run a local audio server for Yomitan
- **Homepage**: [https://github.com/yomidevs/local-audio-yomichan](https://github.com/yomidevs/local-audio-yomichan)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @junestepp


## 🔧 Build Information

- **Derivation Path**: `/nix/store/7pkjh6syjw8f8bwpxd292jx51sm4n2qd-anki-addon-local-audio-yomichan-0-unstable-2025-04-26.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/games/anki/addons/local-audio-yomichan/default.nix:37`
- **Outputs**:
  - `out`:  `/nix/store/7pkjh6syjw8f8bwpxd292jx51sm4n2qd-anki-addon-local-audio-yomichan-0-unstable-2025-04-26`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[nwsrflvzid3mwvp1wq09i81s231hxqns-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:47:49 UTC*
