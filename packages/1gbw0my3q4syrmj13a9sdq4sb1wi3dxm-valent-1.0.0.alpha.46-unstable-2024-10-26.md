---
aliases:
  - valent
tags:
  - license/unknown
  - maintainers/Aleksanaa
  - outputs/out
---

# valent

## 📝 Description

Note that you have to open firewall ports for other devices
to connect to it. Use either:
```nix
programs.kdeconnect = {
  enable = true;
  package = pkgs.valent;
}
```
or open corresponding firewall ports directly:
```nix
networking.firewall = rec {
  allowedTCPPortRanges = [ { from = 1714; to = 1764; } ];
  allowedUDPPortRanges = allowedTCPPortRanges;
}
```


## 📋 Package Information

- **Name**: `valent`
- **Version**: `1.0.0.alpha.46-unstable-2024-10-26`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Implementation of the KDE Connect protocol, built on GNOME platform libraries
- **Homepage**: [https://valent.andyholmes.ca](https://valent.andyholmes.ca)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @Aleksanaa


## 🔧 Build Information

- **Derivation Path**: `/nix/store/1gbw0my3q4syrmj13a9sdq4sb1wi3dxm-valent-1.0.0.alpha.46-unstable-2024-10-26.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/va/valent/package.nix:71`
- **Outputs**:
  - `out`:  `/nix/store/1gbw0my3q4syrmj13a9sdq4sb1wi3dxm-valent-1.0.0.alpha.46-unstable-2024-10-26`

## 🔗 Dependencies

- [[0naxaa1qv8im32fmwrk12qiwfvwwkmsn-gnutls-3.8.10]]
- [[1pmb0rwh9jss40w41by16hm8jah2brji-libpeas-2.0.7]]
- [[3y3h8vjvm1v74q8jlbjcwzy9m4js9z7l-vala-0.56.18]]
- [[51pl2di557fm6xk545yfjjqfxwlfh96m-glib-networking-2.80.1]]
- [[5jnsk32kmr80r0gygfzjlnm3sng90075-pipewire-1.4.7]]
- [[95yd3c1948h410vxpc2nzhf91ahv9hl7-wrap-gapps-hook]]
- [[adsawk1zc4w79nrlw1jylkq5c0y16m3z-tinysparql-3.9.2]]
- [[bfrhypf8s25npqqk6h8hi5qyr3apb3vr-gdk-pixbuf-2.42.12]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cghp1rq1z37hvislx842w5dc0940lrcr-source]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[khcnbl4hfjibl6zyn5r3rpdsmzw5pvbr-gstreamer-1.26.5]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[mvc08s64jg84nrh0gxsvkgzvnmbkfn0f-desktop-file-utils-0.28]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pj3izjl0x4nig0fisid56yy6h08snp65-libportal-gtk4-0.9.1]]
- [[pmwd6bn6y0sf8i3m7l1a8bpp3sxzswsw-json-glib-1.10.6]]
- [[qrjwrd8bxrzyp1z4cpnfgpwssr0qglw9-libadwaita-1.7.6]]
- [[qy6jmq3x3wjl0d6vzwnlzmd9mqsmai94-gst-plugins-base-1.26.5]]
- [[rqgfczspkldc6cgfqffc1pk54lvfk004-pulseaudio-17.0]]
- [[s56wp0aif4spa5dxb1yg2vbdg22rd2bv-evolution-data-server-3.56.2]]
- [[vb66bj2dm0i3xi6h50xi4wgrlfkhx8zl-libphonenumber-9.0.14]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:19:27 UTC*
