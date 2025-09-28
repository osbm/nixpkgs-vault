---
aliases:
  - hello-go
tags:
  - license/unknown
  - maintainers/Aleksanaa
  - outputs/out
---

# hello-go

## 📝 Description

hello-go is a simple program printing "Hello, world!" written in Go,
aiming at testing programs that involves analyzing executables or
emulating foreign architectures, without pulling in a heavy cross
toolchain.

Specify target platform by setting GOOS and GOARCH:

```nix
hello-go.overrideAttrs (previousAttrs: {
  env = previousAttrs.env or { } // {
    GOOS = "linux";
    GOARCH = "arm64";
  };
})
```

See https://pkg.go.dev/internal/platform#pkg-variables for a list
of available platforms.


## 📋 Package Information

- **Name**: `hello-go`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Simple program printing hello world in Go
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @Aleksanaa


## 🔧 Build Information

- **Derivation Path**: `/nix/store/m6yy73ihg96w966z1ahpq88s7p4y5a0n-hello-go.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/he/hello-go/package.nix:21`
- **Outputs**:
  - `out`:  `/nix/store/m6yy73ihg96w966z1ahpq88s7p4y5a0n-hello-go`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/rc3zjs48pnl9a76i9s1wa48smv4q64pj-src`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:11:15 UTC*
