---
aliases:
  - linux-router-without-wifi
tags:
  - license/unknown
  - maintainers/x3rAx
  - outputs/out
---

# linux-router-without-wifi

## 📝 Description

Features:

- Create a NATed sub-network
- Provide Internet
- DHCP server and RA
- DNS server
- IPv6 (behind NATed LAN, like IPv4)
- Creating Wifi hotspot:
  - Channel selecting
  - Choose encryptions: WPA2/WPA, WPA2, WPA, No encryption
  - Create AP on the same interface you are getting Internet (require same channel)
- Transparent proxy (redsocks)
- DNS proxy
- Compatible with NetworkManager (automatically set interface as unmanaged)


## 📋 Package Information

- **Name**: `linux-router-without-wifi`
- **Version**: `0.8.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Set Linux as router / Wifi hotspot / proxy in one command
- **Homepage**: [https://github.com/garywill/linux-router](https://github.com/garywill/linux-router)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @x3rAx


## 🔧 Build Information

- **Derivation Path**: `/nix/store/dq9ccagglxaln5pw3pqgr4fnafl40xm5-linux-router-0.8.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/li/linux-router/package.nix:92`
- **Outputs**:
  - `out`:  `/nix/store/dq9ccagglxaln5pw3pqgr4fnafl40xm5-linux-router-0.8.1`

## 🔗 Dependencies

- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[4f9j67x7cgs2hzjgyyzm8q6z1w2vgy41-which-2.23]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[9a0fz16651fcbs48ih9gcwbrjq6x3lad-flock-0.4.0]]
- [[9qnjgd5vx73f8ibl1fpjhzvkyfawrwfj-iptables-1.8.11]]
- [[a050f45jpjlyvg196x6wyisx4dasssp8-source]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cflrzgbglppcagf2jfix9hgq25126m9z-gnugrep-3.12]]
- [[lxw1zfs9v3nm19mpqbllvcl3s2hkpbjq-procps-4.0.4]]
- [[mc983csj0fvcg5gf5gwhvmi4a9v3jajq-iproute2-6.16.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q331wl66bksvjp5qq0b3dhbcw3fx09x2-gawk-5.3.2]]
- [[q6r8nhgmx37s1vk3580hn9q1illlh9n2-getopt-1.1.6]]
- [[rarkch61g8fxilw9ff4hibi0r0ak13fb-networkmanager-1.52.1]]
- [[rb6vkx53n8h865fndyv0kzx4knmky5zc-dnsmasq-2.91]]
- [[v28sdl3535sxb6a71z5faqdzbns9pv0h-bash-interactive-5.3p3]]
- [[whmvyjphw10d78zfrb04kqjlc0dy68z3-gnused-4.9]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:06:48 UTC*
