---
aliases:
  - go-away
tags:
  - license/unknown
  - maintainers/mweinelt
  - outputs/out
---

# go-away

## 📝 Description

go-away sits in between your site and the Internet / upstream proxy.

Incoming requests can be selected by rules to be actioned or challenged to filter suspicious requests.

The tool is designed highly flexible so the operator can minimize impact to legit users, while surgically targeting heavy endpoints or scrapers.

Challenges can be transparent (not shown to user, depends on backend or other logic), non-JavaScript (challenges common browser properties), or custom JavaScript (from Proof of Work to fingerprinting or Captcha is supported)


## 📋 Package Information

- **Name**: `go-away`
- **Version**: `0.7.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Self-hosted abuse detection and rule enforcement against low-effort mass AI scraping and bots
- **Homepage**: [https://git.gammaspectra.live/git/go-away](https://git.gammaspectra.live/git/go-away)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @mweinelt


## 🔧 Build Information

- **Derivation Path**: `/nix/store/rg42777idy66w1806lsr7d8gh69ss8n7-go-away-0.7.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/go/go-away/package.nix:62`
- **Outputs**:
  - `out`:  `/nix/store/rg42777idy66w1806lsr7d8gh69ss8n7-go-away-0.7.0`

## 🔗 Dependencies

- [[5h6ng7076xwc5ckiy5m6bqhnh6r7ylqr-clang-wrapper-19.1.7]]
- [[8sbm9b7jcixx5881vhblz8nkrbgy9024-tinygo-0.39.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[ilky15hn83zp9cxkh8bq41ph6nn2j61n-brotli-1.1.0]]
- [[md31lb2awhva1ikiccapgqb998kya44z-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[qk9crvcniq2xbmg73rzflywrw22pra5y-zopfli-1.0.3]]
- [[zsdh424r6i3am9b9339ycn7z1xph6z9z-go-away-0.7.0-go-modules]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:48:27 UTC*
