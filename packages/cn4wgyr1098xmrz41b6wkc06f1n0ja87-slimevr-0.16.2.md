---
aliases:
  - slimevr
tags:
  - license/unknown
  - maintainers/gale-username
  - maintainers/imurx
  - outputs/out
---

# slimevr

## 📝 Description

App for SlimeVR ecosystem. It orchestrates communication between multiple sensors and integrations, like SteamVR.

Sensors implementations:

- [SlimeVR Tracker for ESP](https://github.com/SlimeVR/SlimeVR-Tracker-ESP) - ESP microcontrollers and multiple IMUs are supported
- [owoTrack Mobile App](https://github.com/abb128/owoTrackVRSyncMobile) - use phones as trackers (limited functionality and compatibility)
- [SlimeVR Wrangler](https://github.com/carl-anders/slimevr-wrangler) - use Nintendo Switch Joycon controllers as trackers

Integrations:

- Use [SlimeVR OpenVR Driver](https://github.com/SlimeVR/SlimeVR-OpenVR-Driver) as a driver for SteamVR.
- Use built-in OSC Trackers support for FBT integration with VRChat, PCVR or Standalone.
- Use built-in VMC support for sending and receiving tracking data to and from other apps such as VSeeFace.
- Export recordings as .BVH files to integrate motion capture data into 3d applications such as Blender.

More at https://docs.slimevr.dev/tools/index.html.


## 📋 Package Information

- **Name**: `slimevr`
- **Version**: `0.16.2`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: App for facilitating full-body tracking in virtual reality
- **Homepage**: [https://slimevr.dev](https://slimevr.dev)
- **License**: `unknown`
- **Platforms**: `x86_64-darwin`, `aarch64-darwin`, `aarch64-linux`, `armv6l-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv64-linux`, `s390x-linux`, `x86_64-linux`, `armv5tel-linux`, `armv7a-linux`, `m68k-linux`, `mips-linux`, `mips64-linux`, `mipsel-linux`, `mips64el-linux`, `riscv32-linux`
## 👥 Maintainers

- @gale-username
- @imurx


## 🔧 Build Information

- **Derivation Path**: `/nix/store/cn4wgyr1098xmrz41b6wkc06f1n0ja87-slimevr-0.16.2.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sl/slimevr/package.nix:121`
- **Outputs**:
  - `out`:  `/nix/store/cn4wgyr1098xmrz41b6wkc06f1n0ja87-slimevr-0.16.2`

## 🔗 Dependencies

- [[02nvbmkaqzxp5jbnl7i1rcsj85r5cl5p-udev-check-hook]]
- [[0f5ann1sgwyp31vlfqqsnr95xzv3mzhf-cargo-1.89.0]]
- [[1h0a57sbpc8k4a6rspijk1wc8c7v2n53-slimevr-0.16.2-vendor]]
- [[1jggrk899zyajdg7srrilwqpivkzdqz8-gst-plugins-good-1.26.5]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[2mqg4y2qz8kyk9xy96z1b80h3km40nch-nodejs-22.19.0]]
- [[3bz4j2xzjl92yhiwfyhbz6gv4w1888bw-cargo-setup-hook.sh]]
- [[3ndchkhlxxw50k7nd48i9zdkhsr57mwh-cargo-install-hook.sh]]
- [[474kivdzi525za8vzpgr0ils1k0qf8r3-wrap-gapps-hook]]
- [[4bycw2rdgf33gmn1z26knv8grxxh06w5-rustc-wrapper-1.89.0]]
- [[4cc0y6syxyxvjx1lh8ix60vxkly149fh-auditable-cargo-1.89.0]]
- [[51pl2di557fm6xk545yfjjqfxwlfh96m-glib-networking-2.80.1]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[7zkspkrd4dp4qw2vb6gnrxk4qkbs2fzg-tauri-hook]]
- [[8skrn4kblp5h834fip21lmch5nfb9lsb-slimevr-pnpm-deps-pnpm-deps]]
- [[92x1sw1bpxd4q8anq0r8vz5gn5h4cras-libayatana-appindicator-0.5.92]]
- [[9zmq0wdwa3cdnpn8bfb4xb0g10mh67ch-webkitgtk-2.50.0+abi=4.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[brljsm0i3yjyqhah6h2wxkz6yvic3pkj-gst-plugins-bad-1.26.5]]
- [[g6c2d8nh26yxkhawkykfqzmnm079xla6-slimevr-server-0.16.2]]
- [[gnvpsy2jrky72h6lhxf3pjx61sslzz9s-source]]
- [[hx2kjjzk3411q0cbh0vr047941lrnn0k-hidapi-0.15.0]]
- [[jh7dbla5ivglcr3ahs8hr71dz1v6rrbi-gui-no-git.patch]]
- [[jsg4v6zdc22mqxl3bcfzv6wcayfwkab8-pnpm-config-hook]]
- [[khcnbl4hfjibl6zyn5r3rpdsmzw5pvbr-gstreamer-1.26.5]]
- [[lgrrripcv9d4i4qi9pf0007dwcch88di-openjdk-17.0.16+8]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[msazycgapyf9mfwha0gx8sdbj2zn9ckx-libhidapi]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qi6337yh29r9ppqm262bf6vz0g13451b-cargo-build-hook.sh]]
- [[qy6jmq3x3wjl0d6vzwnlzmd9mqsmai94-gst-plugins-base-1.26.5]]
- [[xqxbqs6qgnhvpkcai046s94jfrx8wb62-cargo-check-hook.sh]]

## 📁 Input Sources

- `/nix/store/g20irwrjbngwm8rwzganndd0nfpq64fw-no-java-tool-options-warning.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:12:08 UTC*
