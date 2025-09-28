---
aliases:
  - savvycan
tags:
  - license/unknown
  - maintainers/simoneruffini
  - outputs/out
---

# savvycan

## 📝 Description

SavvyCAN is a cross platform QT based C++ program. It is a CAN bus reverse
engineering and capture tool. It was originally written to utilize EVTV
hardware such as the EVTVDue and CANDue hardware. It has since expanded to be
able to use any socketCAN compatible device as well as the Macchina M2 and
Teensy 3.x boards. SavvyCAN can use any CAN interface supported by QT's
SerialBus system (PeakCAN, Vector, SocketCAN, J2534, etc) It can capture and
send to multiple buses and CAN capture devices at once. It has many functions
specifically meant for reverse engineering data found on the CAN bus:
- Ability to capture even very highly loaded buses
- Ability to connect to many dongles simultaneously
- Scan captured traffic for data that looks coherent
- Show ASCII of captured data to find things like VIN numbers and traffic to
  and from the radio
- Graph data found on the bus
- Load and Save many different file formats common to CAN capture tools (Vector
  captures, Microchip, CANDo, PCAN, and many more)
- Load and Save DBC files. DBC files are used to store definitions for how data
  are formatted on the bus. You can turn the raw data into things like a RPM,
  odometer readings, and more.
- UDS scanning and decoding
- Scripting interface to be able to expand the scope of the software
- Best of all, it's free and open source. Don't like something about it? Change
  it!


## 📋 Package Information

- **Name**: `savvycan`
- **Version**: `220`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: QT based cross platform canbus tool
- **Homepage**: [https://savvycan.com/](https://savvycan.com/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @simoneruffini


## 🔧 Build Information

- **Derivation Path**: `/nix/store/kr65ck9rcw8l8s3dy3hsy4fd2hi8r99v-savvycan-220.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sa/savvycan/package.nix:39`
- **Outputs**:
  - `out`:  `/nix/store/kr65ck9rcw8l8s3dy3hsy4fd2hi8r99v-savvycan-220`

## 🔗 Dependencies

- [[0dyaxjhz2kj25fissh5yj32khwz8crrz-qtbase-5.15.17]]
- [[4dhrk0y3h7f7qgs499ma30zl4y704ij6-qttools-5.15.17]]
- [[635cp93yrwplbs7c1hmw0b552azq56ac-qtserialbus-5.15.17]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[c26wpg1hhjpjmm8c8k1xdv96xakbmfh7-qtdeclarative-5.15.17]]
- [[npgf3vz82j3ns9d14gf8rl1a9cj4n77s-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[r2db2qh3wxwmqd0615pzcixjcirgvj12-wrap-qt5-apps-hook]]
- [[yr347iy0dhh3w6hqw3nzwcrk42lkdpl2-qmake-hook]]
- [[zcskc0ijpf1aixaj7vmwn6kpvsdb9wwx-qtserialport-5.15.17]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:19:53 UTC*
