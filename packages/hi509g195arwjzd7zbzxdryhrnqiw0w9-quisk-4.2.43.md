---
aliases:
  - quisk
tags:
  - license/unknown
  - maintainers/pulsation
  - maintainers/kashw2
  - outputs/dist
  - outputs/out
---

# quisk

## 📝 Description

QUISK is a Software Defined Radio (SDR) transceiver. You supply radio
hardware that converts signals at the antenna to complex (I/Q) data at an
intermediate frequency (IF). Data can come from a sound card, Ethernet or
USB. Quisk then filters and demodulates the data and sends the audio to
your speakers or headphones. For transmit, Quisk takes the microphone
signal, converts it to I/Q data and sends it to the hardware.

Quisk can be used with SoftRock, Hermes Lite 2, HiQSDR, Odyssey and many
radios that use the Hermes protocol. Quisk can connect to digital
programs like Fldigi and WSJT-X. Quisk can be connected to other software
like N1MM+ and software that uses Hamlib.


## 📋 Package Information

- **Name**: `quisk`
- **Version**: `4.2.43`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: SDR transceiver for radios that use the Hermes protocol
- **Homepage**: [https://james.ahlstrom.name/quisk/](https://james.ahlstrom.name/quisk/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @pulsation
- @kashw2


## 🔧 Build Information

- **Derivation Path**: `/nix/store/hi509g195arwjzd7zbzxdryhrnqiw0w9-quisk-4.2.43.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/qu/quisk/package.nix:40`
- **Outputs**:
  - `dist`:  `/nix/store/hi509g195arwjzd7zbzxdryhrnqiw0w9-quisk-4.2.43`
  - `out`:  `/nix/store/hi509g195arwjzd7zbzxdryhrnqiw0w9-quisk-4.2.43`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[085xlrjn483h686si07j1k4s89hakmgz-fftw-double-3.3.10]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[dnbzpphxbd6h31n44gfwbg1qf9q03wcr-pypa-build-hook.sh]]
- [[fmgak3lvqw3ff8wym1v40kgi0b5i1iza-python-runtime-deps-check-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[if30dvb18877vhsf1yhq7bzsgw20xlby-alsa-lib-1.2.14]]
- [[k5jszcgxg447jj9hsq92djj4mkr6k016-python3.13-wxpython-4.2.3]]
- [[p40n6fy4rblc7h0lsbqhly6kv5mnjyjz-quisk-4.2.43.tar.gz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[rqgfczspkldc6cgfqffc1pk54lvfk004-pulseaudio-17.0]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]
- [[zky0d3gzpg876xhhnkpm7pprr05jqb3f-python3.13-pyusb-1.3.1]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:54:04 UTC*
