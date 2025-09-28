---
aliases:
  - babashka
tags:
  - license/unknown
  - maintainers/bennyandresen
  - maintainers/bhougland18
  - maintainers/DerGuteMoritz
  - maintainers/jlesquembre
  - outputs/out
---

# babashka

## 📝 Description

The main idea behind babashka is to leverage Clojure in places where you
would be using bash otherwise.

As one user described it:

    I’m quite at home in Bash most of the time, but there’s a substantial
    grey area of things that are too complicated to be simple in bash, but
    too simple to be worth writing a clj/s script for. Babashka really
    seems to hit the sweet spot for those cases.

Goals:

- Low latency Clojure scripting alternative to JVM Clojure.
- Easy installation: grab the self-contained binary and run. No JVM needed.
- Familiarity and portability:
  - Scripts should be compatible with JVM Clojure as much as possible
  - Scripts should be platform-independent as much as possible. Babashka
    offers support for linux, macOS and Windows.
- Allow interop with commonly used classes like java.io.File and System
- Multi-threading support (pmap, future, core.async)
- Batteries included (tools.cli, cheshire, ...)
- Library support via popular tools like the clojure CLI


## 📋 Package Information

- **Name**: `babashka`
- **Version**: `1.12.208`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Clojure babushka for the grey areas of Bash
- **Homepage**: [https://github.com/babashka/babashka](https://github.com/babashka/babashka)
- **License**: `unknown`
- **Platforms**: `aarch64-darwin`, `aarch64-linux`, `x86_64-darwin`, `x86_64-linux`
## 👥 Maintainers

- @bennyandresen
- @bhougland18
- @DerGuteMoritz
- @jlesquembre


## 🔧 Build Information

- **Derivation Path**: `/nix/store/c9cncnhjhw413mdj75xc8aklqhiz1bas-babashka-1.12.208.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/interpreters/babashka/default.nix:76`
- **Outputs**:
  - `out`:  `/nix/store/c9cncnhjhw413mdj75xc8aklqhiz1bas-babashka-1.12.208`

## 🔗 Dependencies

- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[47vzy8p7cx5qiqqqncylhwwlm4hjvkf2-openjdk-21.0.8+9]]
- [[4wf8b9y7y7r7zgxg7li2ddxydqf1g343-babashka-clojure-tools-1.12.2.1565]]
- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[r6mbwhxq458k6m4h2wl6n8bpmcdl1rbr-babashka-unwrapped-1.12.208]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:47:38 UTC*
