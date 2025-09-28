---
aliases:
  - govulncheck
tags:
  - license/unknown
  - maintainers/06kellyjac
  - maintainers/SuperSandro2000
  - outputs/out
---

# govulncheck

## 📝 Description

Govulncheck reports known vulnerabilities that affect Go code. It uses
static analysis of source code or a binary's symbol table to narrow down
reports to only those that could affect the application.

By default, govulncheck makes requests to the Go vulnerability database at
https://vuln.go.dev. Requests to the vulnerability database contain only
module paths, not code or other properties of your program. See
https://vuln.go.dev/privacy.html for more. Set the GOVULNDB environment
variable to specify a different database, which must implement the
specification at https://go.dev/security/vuln/database.

Govulncheck looks for vulnerabilities in Go programs using a specific
build configuration. For analyzing source code, that configuration is the
operating system, architecture, and Go version specified by GOOS, GOARCH,
and the “go” command found on the PATH. For binaries, the build
configuration is the one used to build the binary. Note that different
build configurations may have different known vulnerabilities. For
example, a dependency with a Windows-specific vulnerability will not be
reported for a Linux build.


## 📋 Package Information

- **Name**: `govulncheck`
- **Version**: `1.1.4`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Database client and tools for the Go vulnerability database, also known as vuln
- **Homepage**: [https://pkg.go.dev/golang.org/x/vuln/cmd/govulncheck](https://pkg.go.dev/golang.org/x/vuln/cmd/govulncheck)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @06kellyjac
- @SuperSandro2000


## 🔧 Build Information

- **Derivation Path**: `/nix/store/h56kyy6r12jjgqwab5nixw7vs6a1qy5v-govulncheck-1.1.4.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/go/govulncheck/package.nix:44`
- **Outputs**:
  - `out`:  `/nix/store/h56kyy6r12jjgqwab5nixw7vs6a1qy5v-govulncheck-1.1.4`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[kz5dw6ffjggva61i3x4ij5wgf17i5ynv-version.patch]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[shzysl9ggynp945wqvn14qaa8ymydxfv-source]]
- [[vwgw4aq20516l991x5l4rvijscr723gb-govulncheck-1.1.4-go-modules]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:53:26 UTC*
