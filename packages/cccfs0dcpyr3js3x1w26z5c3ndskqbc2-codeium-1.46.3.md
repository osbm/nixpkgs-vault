---
aliases:
  - codeium
tags:
  - not-available
  - license/unknown
  - maintainers/anpin
  - outputs/out
---

# codeium

## 📝 Description

Codeium proprietary language server, patched for Nix(OS) compatibility.
bin/language_server_x must be symlinked into the plugin directory, replacing the existing binary.
For example:
```shell
ln -s "$(which codeium_language_server)" /home/a/.local/share/JetBrains/Rider2023.1/codeium/662505c9b23342478d971f66a530cd102ae35df7/language_server_linux_x64
```


## 📋 Package Information

- **Name**: `codeium`
- **Version**: `1.46.3`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Codeium language server
- **Homepage**: [https://codeium.com/](https://codeium.com/)
- **License**: `unknown`
- **Platforms**: `aarch64-darwin`, `aarch64-linux`, `x86_64-linux`, `x86_64-darwin`
## 👥 Maintainers

- @anpin


## 🔧 Build Information

- **Derivation Path**: `/nix/store/cccfs0dcpyr3js3x1w26z5c3ndskqbc2-codeium-1.46.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/co/codeium/package.nix:69`
- **Outputs**:
  - `out`:  `/nix/store/cccfs0dcpyr3js3x1w26z5c3ndskqbc2-codeium-1.46.3`

## 🔗 Dependencies

- [[19dkqq6j7z6ahjqgj3pa5wkkj6rl3wdg-auto-patchelf-hook]]
- [[27bm7ndbqvzb6ygkx324l73cznvf5rvg-gzip-1.14]]
- [[bdhqnjcs1r1dphh1wadmcz61k435hpyk-codeium-1.46.3.gz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lzvy25g887aypn07ah8igv72z7b9jb88-version-check-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:03 UTC*
