---
aliases:
  - sway-assign-cgroups
tags:
  - license/unknown
  - maintainers/NickHu
  - outputs/out
---

# sway-assign-cgroups

## 📝 Description

Automatically assign a dedicated systemd scope to the GUI applications
launched in the same cgroup as the compositor. This could be helpful for
implementing cgroup-based resource management and would be necessary when
`systemd-oomd` is in use.

Limitations: The script is using i3ipc window:new event to detect application
launches and would fail to detect background apps or special surfaces.
Therefore it's recommended to supplement the script with use of systemd user
services for such background apps.


## 📋 Package Information

- **Name**: `sway-assign-cgroups`
- **Version**: `0.4.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Place GUI applications into systemd scopes for systemd-oomd compatibility
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @NickHu


## 🔧 Build Information

- **Derivation Path**: `/nix/store/ksj91skr1x8nkxmzr6raphs4a5ps1w7z-sway-assign-cgroups-0.4.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sw/sway-assign-cgroups/package.nix:34`
- **Outputs**:
  - `out`:  `/nix/store/ksj91skr1x8nkxmzr6raphs4a5ps1w7z-sway-assign-cgroups-0.4.1`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[67ppk6gnh68nivx28kc5689w1bn4l7lj-source]]
- [[6vwms701y3kk0kdcfs4fkv345v6pd64k-python3.13-xlib-0.33]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[7sxb0nv7401ym34047y636wx05b0aqyc-python3.13-dbus-next-0.2.3]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[gw18fiibdnn237gp7f88xh4nx5db9yj4-python3.13-psutil-7.0.0]]
- [[ll3g7ab18pinn39km8pcz2hhcn6mf917-python3.13-i3ipc-2.2.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[wjdpplwdh78p88wv2d3dzqg0m7wzpgpn-python3.13-tenacity-9.1.2]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:58:51 UTC*
