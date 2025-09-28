---
aliases:
  - paretosecurity
tags:
  - license/unknown
  - maintainers/zupo
  - outputs/out
---

# paretosecurity

## 📝 Description

[Pareto Desktop](https://paretosecurity.com/linux) is a free and open
source trayicon app to help you configure your laptop for security. It
nudges you to take care of 20% of security-related tasks that bring 80% of
protection.

In it's simplest form, it's a CLI command that prints out a report on basic
security settings such as if you have disk encryption and firewall enabled.

If you use the `services.paretosecurity` NixOS module, you also get a
root helper that allows you to run the checker in userspace. Some checks
require root permissions, and the checker asks the helper to run those.

Additionally, using the NixOS module gets you a little Vilfredo Pareto
living in your systray showing your the current status of checks. The
NixOS Module also installs a systemd timer to update the status of checks
once per hour. If you want to use just the CLI mode, set
`services.paretosecurity.trayIcon` to `false`.

Finally, if you set `users.users.alice.paretosecurity.inviteId = "..."`
to the `inviteId` you get on [Pareto Cloud](https://cloud.paretosecurity.com/),
then Pareto Desktop acts as a read-only and push-only agent that sends the
status of checks to https://cloud.paretosecurity.com which makes
compliance people happy and your privacy intact.


## 📋 Package Information

- **Name**: `paretosecurity`
- **Version**: `0.3.6`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: A simple trayicon app that makes sure your laptop is correctly configured for security
- **Homepage**: [https://github.com/ParetoSecurity/agent](https://github.com/ParetoSecurity/agent)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `wasm64-wasi`, `wasm32-wasi`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @zupo


## 🔧 Build Information

- **Derivation Path**: `/nix/store/g9fg0fbjhvj8h1z9s03zlmy5mrhcz63j-paretosecurity-0.3.6.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/pa/paretosecurity/package.nix:81`
- **Outputs**:
  - `out`:  `/nix/store/g9fg0fbjhvj8h1z9s03zlmy5mrhcz63j-paretosecurity-0.3.6`

## 🔗 Dependencies

- [[4dq8np7c2mimniwl3if93g7ncz1cjr4r-gtk+3-3.24.49]]
- [[5855q22sdr56py9dpmgq0zxv4rbhjl72-source]]
- [[9zmq0wdwa3cdnpn8bfb4xb0g10mh67ch-webkitgtk-2.50.0+abi=4.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[lz6qpyi8lbn210g2sad31g28ijdxsbqw-paretosecurity-0.3.6-go-modules]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:11:56 UTC*
