---
aliases:
  - systemdMinimal
tags:
  - license/unknown
  - maintainers/flokli
  - maintainers/arianvp
  - maintainers/ElvishJerricco
  - maintainers/aanderse
  - maintainers/LordGrimmauld
  - outputs/debug
  - outputs/dev
  - outputs/man
  - outputs/out
---

# systemdMinimal

## 📝 Description

systemd is a suite of basic building blocks for a Linux system. It
provides a system and service manager that runs as PID 1 and starts the
rest of the system. systemd provides aggressive parallelization
capabilities, uses socket and D-Bus activation for starting services,
offers on-demand starting of daemons, keeps track of processes using Linux
control groups, maintains mount and automount points, and implements an
elaborate transactional dependency-based service control logic. systemd
supports SysV and LSB init scripts and works as a replacement for
sysvinit. Other parts include a logging daemon, utilities to control basic
system configuration like the hostname, date, locale, maintain a list of
logged-in users and running containers and virtual machines, system
accounts, runtime directories and settings, and daemons to manage simple
network configuration, network time synchronization, log forwarding, and
name resolution.


## 📋 Package Information

- **Name**: `systemdMinimal`
- **Version**: `257.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: System and service manager for Linux
- **Homepage**: [https://www.freedesktop.org/wiki/Software/systemd/](https://www.freedesktop.org/wiki/Software/systemd/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `x86_64-linux`, `loongarch64-linux`, `m68k-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`
## 👥 Maintainers

- @flokli
- @arianvp
- @ElvishJerricco
- @aanderse
- @LordGrimmauld


## 🔧 Build Information

- **Derivation Path**: `/nix/store/lm7x9kv0zsy40ln4pkk7xgdv6ph0i738-systemd-minimal-257.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/os-specific/linux/systemd/default.nix:1045`
- **Outputs**:
  - `debug`:  `/nix/store/lm7x9kv0zsy40ln4pkk7xgdv6ph0i738-systemd-minimal-257.8`
  - `dev`:  `/nix/store/lm7x9kv0zsy40ln4pkk7xgdv6ph0i738-systemd-minimal-257.8`
  - `man`:  `/nix/store/lm7x9kv0zsy40ln4pkk7xgdv6ph0i738-systemd-minimal-257.8`
  - `out`:  `/nix/store/lm7x9kv0zsy40ln4pkk7xgdv6ph0i738-systemd-minimal-257.8`

## 🔗 Dependencies

- [[04sxd1ncbv87d14flich8a6g06jbyw6c-docbook-xsl-nons-1.79.2]]
- [[19dkqq6j7z6ahjqgj3pa5wkkj6rl3wdg-auto-patchelf-hook]]
- [[3kgj31l4fhkbp0s74bzl7zvrr1v6aymc-libxcrypt-4.4.38]]
- [[3z6dcp2i69nn7h8kwl6snf651i7ds14v-util-linux-minimal-2.41.1]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[55skdvm9nvfv299nmajgpznd8x6mns9s-glibc-locales-2.40-66]]
- [[629fvw2crss9xny88yp4mq2jly9d3fys-libcap-2.76]]
- [[7prdpldqvb04fk0pnfnrypj6y7m7zsnn-python3-3.13.7-env]]
- [[agnkcpgsw63ima1rywjanh2pqz1zpl18-gperf-3.3]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[d83ikic6a9kflg1nrghh490iwndr9xl6-docbook-xml-4.2]]
- [[dil6p2zn6xgiwrbd252ck5bl9cc2x3gc-docbook-xml-4.5]]
- [[f368fizl82c6krd1a5gcxp0m6m4zd474-intltool-0.51.0]]
- [[h52lzzip82l66c7bv23g7xckp89y5kgr-linux-headers-6.16]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[ix6d8z5gbs4yl44p8c2ihslqdzqqqawg-getent-glibc-2.40-66]]
- [[jqbkfpfrxs7mipq43ny5j7zkwkmpwaic-kbd-2.8.0-unstable-2025-08-12]]
- [[jvk6w0wmh9f50wh0xr7mb7faz9ipbmzv-libseccomp-2.6.0]]
- [[k2lm2qkl0haj7vph5sa2r97my0ah0q1b-libxslt-1.1.43]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[m0h8vm7wnxqmzy77yph902p607lx7np5-gettext-0.25.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pg5k3nk2hj6mq23nbhbl1n5ms9a8n8af-kexec-tools-2.0.31]]
- [[pn03b9dijjmykv1k5sfjm4h990h4k25f-make-binary-wrapper-hook]]
- [[qmg0h7ddbh8r5iissdh538jgwx5xi189-kmod-31]]
- [[rrn4zjbhvfmi5asxn3cjgddfzjkvpz8y-gnutar-1.35]]
- [[sp2vq01660i7gmsgddk4x9di14gwny4m-gnum4-1.4.20]]
- [[v1b98vshlqziaxpk5n7bwaxixarp4ll2-source]]
- [[v28sdl3535sxb6a71z5faqdzbns9pv0h-bash-interactive-5.3p3]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]

## 📁 Input Sources

- `/nix/store/aapb6r3makw2j6ka6jrazhj3x000s62m-0010-systemd-shutdown-execute-scripts-in-etc-systemd-syst.patch`
- `/nix/store/d1fha1isncmdjjady7b7s6q6h2whgdkw-0016-systemctl-edit-suggest-systemdctl-edit-runtime-on-sy.patch`
- `/nix/store/d6gi2r8aw5djhfnd8izxbhnhmp7d9cs6-0019-install-unit_file_exists_full-follow-symlinks.patch`
- `/nix/store/gh1rgp047swszc96zxp7hdw2blgah0wq-0013-inherit-systemd-environment-when-calling-generators.patch`
- `/nix/store/hsz0hm0ws5jc0k91ykr0ry5ql3clslnj-0012-path-util.h-add-placeholder-for-DEFAULT_PATH_NORMAL.patch`
- `/nix/store/iwhg0gynr58q5hd9j0hry9qw8a3g7csc-0001-Start-device-units-for-uninitialised-encrypted-devic.patch`
- `/nix/store/j6lp6n92pb5k8dmfcngqxdjh8m4mxpii-0018-meson-Don-t-link-ssh-dropins.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/m0zpma2441b5j7n015i481jhf7inbc1p-0020-timesyncd-disable-NSCD-when-DNSSEC-validation-is-dis.patch`
- `/nix/store/mi1rd781rd1r3ga6qyhq7llszvc1xhyj-0006-hostnamed-localed-timedated-disable-methods-that-cha.patch`
- `/nix/store/r989dk196nl9frhnfsa1lb7knhbyjxw6-separate-debug-info.sh`
- `/nix/store/rfgpmlc59k58r390jsv9nvjc7p5r3ygr-0009-add-rootprefix-to-lookup-dir-paths.patch`
- `/nix/store/s1h9ijczidxcvwhh02y5dinx6b97byfm-0017-meson.build-do-not-create-systemdstatedir.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/sryfrvip8baif0vc8b2pnxfv9n26nrjc-0007-Change-usr-share-zoneinfo-to-etc-zoneinfo.patch`
- `/nix/store/vr8s6r6ai5gj1j3jjxah9pzgqvsjn4k1-0008-localectl-use-etc-X11-xkb-for-list-x11.patch`
- `/nix/store/wzwxp1rd2k853194a865211297rc8jij-0015-tpm2_context_init-fix-driver-name-checking.patch`
- `/nix/store/x8rcsx9c3lh2hrn554nmq8b4l38m83dm-0002-Don-t-try-to-unmount-nix-or-nix-store.patch`
- `/nix/store/x92i8rz0w3dp9w35jqzj2k8v3r7ql61v-0003-Fix-NixOS-containers.patch`
- `/nix/store/xa14wj0j84vylv8ay3qyh1wc8k51anln-0011-systemd-sleep-execute-scripts-in-etc-systemd-system-.patch`
- `/nix/store/xxlp9bvbkaisyvj6vfqbva8l0q2kjp2d-0004-Add-some-NixOS-specific-unit-directories.patch`
- `/nix/store/y1a2avjghqx9rasskgdm0qw0xwsik4ky-0005-Get-rid-of-a-useless-message-in-user-sessions.patch`
- `/nix/store/zcmrmn878kq66nyp6yvmfafda949isnl-0014-core-don-t-taint-on-unmerged-usr.patch`

---
*Generated on 2025-09-27 13:01:48 UTC*
