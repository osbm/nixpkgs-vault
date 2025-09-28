---
aliases:
  - gpsd
tags:
  - license/unknown
  - maintainers/bjornfor
  - maintainers/rasendubi
  - outputs/out
---

# gpsd

## 📝 Description

gpsd is a service daemon that monitors one or more GPSes or AIS
receivers attached to a host computer through serial or USB ports,
making all data on the location/course/velocity of the sensors
available to be queried on TCP port 2947 of the host computer. With
gpsd, multiple location-aware client applications (such as navigational
and wardriving software) can share access to receivers without
contention or loss of data. Also, gpsd responds to queries with a
format that is substantially easier to parse than the NMEA 0183 emitted
by most GPSes. The gpsd distribution includes a linkable C service
library, a C++ wrapper class, and a Python module that developers of
gpsd-aware applications can use to encapsulate all communication with
gpsd. Third-party client bindings for Java and Perl also exist.

Besides gpsd itself, the project provides auxiliary tools for
diagnostic monitoring and profiling of receivers and feeding
location-aware applications GPS/AIS logs for diagnostic purposes.


## 📋 Package Information

- **Name**: `gpsd`
- **Version**: `3.26.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GPS service daemon
- **Homepage**: [https://gpsd.gitlab.io/gpsd/index.html](https://gpsd.gitlab.io/gpsd/index.html)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @bjornfor
- @rasendubi


## 🔧 Build Information

- **Derivation Path**: `/nix/store/2m3xi8g60p4vvd1xj96amlrxmb593mb2-gpsd-3.26.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/gp/gpsd/package.nix:131`
- **Outputs**:
  - `out`:  `/nix/store/2m3xi8g60p4vvd1xj96amlrxmb593mb2-gpsd-3.26.1`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[27jxqcdhqw4h3cmmsih83c4488jpx2a7-python3.13-pycairo-1.28.0]]
- [[28phnmnqgzmkqlby0znahvp3bgx6d6vv-dbus-1.14.10]]
- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[474kivdzi525za8vzpgr0ils1k0qf8r3-wrap-gapps-hook]]
- [[4sy9c2y3gzb70jwxvvd60ch7h1kd50rg-gpsd-3.26.1.tar.gz]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[bfrhypf8s25npqqk6h8hi5qyr3apb3vr-gdk-pixbuf-2.42.12]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[ca06pjvdmc5ckxnmppbz2f82l2q5bxn9-scons-4.7.0]]
- [[d99f4z55b6p4hx1wfl4r6d6i0zi5bh7m-libxext-1.3.6]]
- [[dkssw3csslvbv7cb9mrmfccns92l65c5-pango-1.56.3]]
- [[f2zlnw16484q5c9hi6fjnmbiimskrwsg-libxt-1.3.1]]
- [[fmcl48pl1yd2dj0i667whqy578xlns7z-at-spi2-core-2.56.2]]
- [[fy9wjrqf0pzd5x3rvy665v50ff747wfd-libusb-1.0.29]]
- [[gvp7gvf5582a2n8q1a4lf94dxs94bxhc-libxaw-1.0.16]]
- [[h3p18wvgddjr72bcxrgm83ipa3cwcwdp-libxpm-3.5.17]]
- [[hcyf24kf52p5ib5q0zvl1nxvhh7q5kfd-dbus-glib-0.114]]
- [[jqqc83j9v460xa1qlp77ky52gbqg5af8-gobject-introspection-wrapped-1.84.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[nncd4f9vl1alqwmiff6a138ppbsgbp5l-libx11-1.8.12]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pldfa9xafzpqfs0xkxw6sqir28lvsb1r-python3.13-pyserial-3.5]]
- [[rlyzp1xm9ghkyf96qij1dnxki5g725px-python3.13-pygobject-3.50.0]]
- [[z2xr6i42j3h3p1r1y59ycrczccjx9zf3-pps-tools-1.0.3]]

## 📁 Input Sources

- `/nix/store/8x1rgpz4p208vgz2sf6nnx80sj3swnhn-sconstruct-env-fixes.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/nra63m3vadmzim0vaaafdaifa1bn95wy-sconstrict-rundir-fixes.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:54:22 UTC*
