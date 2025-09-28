---
aliases:
  - firefoxpwa
tags:
  - license/unknown
  - maintainers/camillemndn
  - maintainers/pasqui23
  - outputs/out
---

# firefoxpwa

## 📝 Description

Progressive Web Apps (PWAs) are web apps that use web APIs and features along
with progressive enhancement strategy to bring a native app-like user experience
to cross-platform web applications. Although Firefox supports many of Progressive
Web App APIs, it does not support functionality to install them as a standalone
system app with an app-like experience.

This project creates a custom modified Firefox runtime to allow websites to be
installed as standalone apps and provides a console tool and browser extension
to install, manage and use them.

This package contains only the native part of the PWAsForFirefox project. You
should also install the browser extension if you haven't already. You can download
it from the [Firefox Add-ons](https://addons.mozilla.org/firefox/addon/pwas-for-firefox/)
website.

To install the package on NixOS, you need to add the following options:

```
programs.firefox.nativeMessagingHosts.packages = [ pkgs.firefoxpwa ];
environment.systemPackages = [ pkgs.firefoxpwa ];
```

As it needs to be both in the `PATH` and in the `nativeMessagingHosts` to make it
possible for the extension to detect and use it.


## 📋 Package Information

- **Name**: `firefoxpwa`
- **Version**: `2.16.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tool to install, manage and use Progressive Web Apps (PWAs) in Mozilla Firefox (native component)
- **Homepage**: [https://pwasforfirefox.filips.si/](https://pwasforfirefox.filips.si/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv6l-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv64-linux`, `s390x-linux`, `x86_64-linux`, `armv5tel-linux`, `armv7a-linux`, `m68k-linux`, `mips-linux`, `mips64-linux`, `mipsel-linux`, `mips64el-linux`, `riscv32-linux`
## 👥 Maintainers

- @camillemndn
- @pasqui23


## 🔧 Build Information

- **Derivation Path**: `/nix/store/izbrc89g32n1w4hg180n9hdm75slc6ry-firefoxpwa-2.16.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/fi/firefoxpwa/package.nix:128`
- **Outputs**:
  - `out`:  `/nix/store/izbrc89g32n1w4hg180n9hdm75slc6ry-firefoxpwa-2.16.0`

## 🔗 Dependencies

- [[0f5ann1sgwyp31vlfqqsnr95xzv3mzhf-cargo-1.89.0]]
- [[1jgyc8pm0h5lnk0imm0bs3fhshis2hr2-cups-2.4.12]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[2nf9x9f81s47xi0g4pzqqhvwzqxz3k4r-mesa-libgbm-25.1.0]]
- [[3bz4j2xzjl92yhiwfyhbz6gv4w1888bw-cargo-setup-hook.sh]]
- [[3ndchkhlxxw50k7nd48i9zdkhsr57mwh-cargo-install-hook.sh]]
- [[3zc6j1j1qgis43ig9m9gl11iqf058s76-systemd-minimal-libs-257.8]]
- [[4bycw2rdgf33gmn1z26knv8grxxh06w5-rustc-wrapper-1.89.0]]
- [[4cc0y6syxyxvjx1lh8ix60vxkly149fh-auditable-cargo-1.89.0]]
- [[557ys11d3fcr8ywgyxpy4d5y4jkjhk0b-ffmpeg-7.1.1]]
- [[5jnsk32kmr80r0gygfzjlnm3sng90075-pipewire-1.4.7]]
- [[6sfgwmiajyfby1bvjm3icw5xq2achxha-libva-2.22.0]]
- [[761d6f8hhrvq2qrbqc6ygxr3x34img28-libglvnd-1.7.0]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[7ngm3x6yy8z3dxvl9967qd0563kkcy57-libpulseaudio-17.0]]
- [[92ffs78gghjbglzng476d33211f9vnxv-libXScrnSaver-1.2.4]]
- [[b6lan6ymi22sy8w981cx3x2nymcyvx7r-pciutils-3.14.0]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[mh835h1mhbqinppdi3ggz9f28b87f0vz-libnotify-0.8.6]]
- [[mhk11c6z5b9dfbg4qdyiwhdlgxvrmppq-firefoxpwa-2.16.0-vendor]]
- [[nrw12hv4fk9sc1zfhl5zhhzq9sqfcym7-libcanberra-0.30]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qi6337yh29r9ppqm262bf6vz0g13451b-cargo-build-hook.sh]]
- [[vk8c6lf84l24566fkx6bb0qkzr240lh0-firefox-unwrapped-143.0]]
- [[xgng8kqkginzxin9shmcv322hf45nknr-source]]
- [[xqxbqs6qgnhvpkcai046s94jfrx8wb62-cargo-check-hook.sh]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:43:05 UTC*
