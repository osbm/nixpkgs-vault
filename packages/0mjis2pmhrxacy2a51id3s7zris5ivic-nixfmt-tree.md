---
aliases:
  - nixfmt-tree
tags:
  - license/unknown
  - maintainers/piegamesde
  - maintainers/infinisil
  - maintainers/dasJ
  - maintainers/0x4A6F
  - maintainers/MattSturgeon
  - maintainers/jfly
  - outputs/out
---

# nixfmt-tree

## 📝 Description

A zero-setup [treefmt](https://treefmt.com/) starter to get started using the [official Nix formatter](https://github.com/NixOS/nixfmt).

- For `nix fmt` to format all Nix files, add this to the `flake.nix` outputs:

  ```nix
  formatter.${system} = nixpkgs.legacyPackages.${system}.nixfmt-tree;
  ```

- The same can be done more efficiently with the `treefmt` command,
  which you can get in `nix-shell`/`nix develop` by extending `mkShell` using

  ```nix
  mkShell {
    packages = [ pkgs.nixfmt-tree ];
  }
  ```

  You can then also use `treefmt` in a pre-commit/pre-push [Git hook](https://git-scm.com/docs/githooks)
  and with your editor's format-on-save feature.

- To check formatting in CI, run the following in a checkout of your Git repository:
  ```
  treefmt --ci
  ```

For more flexibility, you can customise this package using
```nix
pkgs.nixfmt-tree.override {
  settings = { /* additional treefmt config */ };
  runtimeInputs = [ /* additional formatter packages */ ];
}
```

You can achieve similar results by manually configuring `treefmt`:
```nix
pkgs.treefmt.withConfig {
  runtimeInputs = [ pkgs.nixfmt-rfc-style ];

  settings = {
    # Log level for files treefmt won't format
    on-unmatched = "info";

    # Configure nixfmt for .nix files
    formatter.nixfmt = {
      command = "nixfmt";
      includes = [ "*.nix" ];
    };
  };
}
```

Alternatively you can switch to the more fully-featured [treefmt-nix](https://github.com/numtide/treefmt-nix).


## 📋 Package Information

- **Name**: `nixfmt-tree`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Official Nix formatter zero-setup starter using treefmt
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @piegamesde
- @infinisil
- @dasJ
- @0x4A6F
- @MattSturgeon
- @jfly


## 🔧 Build Information

- **Derivation Path**: `/nix/store/0mjis2pmhrxacy2a51id3s7zris5ivic-nixfmt-tree.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ni/nixfmt-tree/package.nix:60`
- **Outputs**:
  - `out`:  `/nix/store/0mjis2pmhrxacy2a51id3s7zris5ivic-nixfmt-tree`

## 🔗 Dependencies

- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[mmvg0a0h410x2b9yz03ml8j4rcszyadx-treefmt-2.3.1]]
- [[nx6niln8zwnp9d292105p3b47ib4pj89-nixfmt-1.0.1]]
- [[pn03b9dijjmykv1k5sfjm4h990h4k25f-make-binary-wrapper-hook]]
- [[zappdp8379zwq9wh8lyhd5gzihw18qsf-treefmt.toml]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:23:09 UTC*
