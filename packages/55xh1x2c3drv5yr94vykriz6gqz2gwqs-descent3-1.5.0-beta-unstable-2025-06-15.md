---
aliases:
  - descent3
tags:
  - license/unknown
  - maintainers/Jayman2000
  - outputs/out
---

# descent3

## 📝 Description

Playing Descent 3 using the Nix package manager is a little bit awkward
at the moment. This wrapper makes it slightly less awkward. Here’s how
you use this wrapper:

1. Install the `descent3` package, or start an ephemeral shell with the
`descent3` package.

2. Find the documentation folder for `descent3-unwrapped` by running this
command:

    ```bash
    nix-instantiate --eval --expr '(import <nixpkgs> { }).descent3-unwrapped + "/share/doc/Descent3"'
    ```

3. Open `<descent3-unwrapped-doc-folder>/USAGE.md`.

4. Follow steps 1–6 of Descent 3’s usage instructions.

5. Change directory into the `D3-open-source` folder:

  ```bash
  cd <path-to-D3-open-source>
  ```

6. Start Descent 3 by running this command:

    ```bash
    Descent3
    ```


## 📋 Package Information

- **Name**: `descent3`
- **Version**: `1.5.0-beta-unstable-2025-06-15`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Game engine for a 6DOF first-person shooter
- **Homepage**: [https://github.com/DescentDevelopers/Descent3](https://github.com/DescentDevelopers/Descent3)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @Jayman2000


## 🔧 Build Information

- **Derivation Path**: `/nix/store/55xh1x2c3drv5yr94vykriz6gqz2gwqs-descent3-1.5.0-beta-unstable-2025-06-15.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/de/descent3-unwrapped/package.nix:133`
- **Outputs**:
  - `out`:  `/nix/store/55xh1x2c3drv5yr94vykriz6gqz2gwqs-descent3-1.5.0-beta-unstable-2025-06-15`

## 🔗 Dependencies

- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[k6zfw7vl7v48d4w214ng0lbyfyzrw454-descent3-unwrapped-1.5.0-beta-unstable-2025-06-15]]
- [[pn03b9dijjmykv1k5sfjm4h990h4k25f-make-binary-wrapper-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:42:49 UTC*
