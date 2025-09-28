---
aliases:
  - scanbd
tags:
  - license/unknown
  - outputs/out
---

# scanbd

## 📝 Description

scanbd polls a scanner's buttons, looking for button presses, function
knob changes, or other scanner events such as paper inserts and removals,
while at the same time allowing scan-applications to access the scanner.

Various actions can be submitted (scan, copy, email, ...) via action
scripts. The function knob values are passed to the action scripts as
well. Scan actions are also signaled via dbus. This can be useful for
foreign applications. Scans can also be triggered via dbus from foreign
applications.

On platforms which support signaling of dynamic device insertion/removal
(libudev, dbus, hal), scanbd supports this as well.

scanbd can use all sane-backends or some special backends from the (old)
scanbuttond project.


## 📋 Package Information

- **Name**: `scanbd`
- **Version**: `1.5.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Scanner button daemon
- **Homepage**: [http://scanbd.sourceforge.net/](http://scanbd.sourceforge.net/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/y6g58n8jlvlkrpaxvv5dwmzzfr4qs157-scanbd-1.5.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/sc/scanbd/package.nix:53`
- **Outputs**:
  - `out`:  `/nix/store/y6g58n8jlvlkrpaxvv5dwmzzfr4qs157-scanbd-1.5.1`

## 🔗 Dependencies

- [[28phnmnqgzmkqlby0znahvp3bgx6d6vv-dbus-1.14.10]]
- [[2sgql247rkyqmnad6gl3pwmq6gsy13wz-libjpeg-turbo-3.1.1]]
- [[3gh0snr9wn0i6gzya2g42hmm0cc2lwg3-sane-backends-1.4.0]]
- [[70skfsvfxybyaq8x22dpsq37vbbl1zpx-scanbd-1.5.1.tgz]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dzynf7h9bw2qvzwkzm5kmjbgqzpsxj00-systemd-257.8]]
- [[fwnwvlgxkx4493py8m9qlxk1z8wiqlzx-libconfuse-3.3]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:01:58 UTC*
