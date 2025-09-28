---
aliases:
  - alpaca
tags:
  - license/unknown
  - maintainers/Aleksanaa
  - maintainers/Gliczy
  - outputs/out
---

# alpaca

## 📝 Description

To run Alpaca with GPU acceleration enabled, simply override it:
```nix
pkgs.alpaca.override {
  ollama = pkgs.ollama-cuda;
}
```
Or using `pkgs.ollama-rocm` for AMD GPUs.


## 📋 Package Information

- **Name**: `alpaca`
- **Version**: `6.1.7`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Ollama client made with GTK4 and Adwaita
- **Homepage**: [https://jeffser.com/alpaca](https://jeffser.com/alpaca)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @Aleksanaa
- @Gliczy


## 🔧 Build Information

- **Derivation Path**: `/nix/store/b7nh8rcpqfh9r81bmj60i1100bfra9f7-alpaca-6.1.7.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/al/alpaca/package.nix:86`
- **Outputs**:
  - `out`:  `/nix/store/b7nh8rcpqfh9r81bmj60i1100bfra9f7-alpaca-6.1.7`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[10jhr0796d2wz5cgws87a5xz5dhp5igf-python3.13-html2text-2025.4.15]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[3qnnawic15jhvpj6zzsqwpcsfks8b7h7-ollama-0.12.0]]
- [[47psc28lp0vfkfmjck9lz091i7igpp92-gtksourceview-5.16.0]]
- [[4ixzqy5zi3dlxfwd0y1vaccv5kns18b7-python3.13-pydbus-0.6.0]]
- [[50ffb31mwv2bmm7kmmrxjyb86vgccggq-python3.13-odfpy-1.4.1]]
- [[7rqxw5xaszi1ypfvky5rsxhbg5l21nim-python3.13-markitdown-0.1.3]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[95yd3c1948h410vxpc2nzhf91ahv9hl7-wrap-gapps-hook]]
- [[b05z186xzqma81zqs77gg21clw2axy6l-source]]
- [[b2avblqs1ivmcgyg2p8hy1yhm2gfmsr6-python3.13-openai-1.101.0]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[d5rgq2qwa73cabnkp2smb30x3wvi326f-xdg-utils-1.2.1]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[jqqc83j9v460xa1qlp77ky52gbqg5af8-gobject-introspection-wrapped-1.84.0]]
- [[jv0cyqwn1klsqwcdd3f37n4mdcljvkip-libspelling-0.4.9]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[mvc08s64jg84nrh0gxsvkgzvnmbkfn0f-desktop-file-utils-0.28]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[ph9fvlg5zs92d2pdpddgcp1566nrf4sa-vte-0.80.3]]
- [[pppp6647rjri9lwm7nv7g0s1cwyq61dk-appstream-1.0.4]]
- [[qrjwrd8bxrzyp1z4cpnfgpwssr0qglw9-libadwaita-1.7.6]]
- [[rlyzp1xm9ghkyf96qij1dnxki5g725px-python3.13-pygobject-3.50.0]]
- [[rs3h8g5y8rznyb4k64hgvzvp3jgsr5b8-python3.13-requests-2.32.4]]
- [[s9yaqazqf675l0xca1grb78ks1lza91q-python3.13-pyicu-2.15.2]]
- [[swwhxdnkhx8q81vm3m58k5kmlgsm4b51-python3.13-pillow-11.3.0]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[z3g63djg1fkn29w1700qzhv7lbg14xnz-python3.13-youtube-transcript-api-1.2.2]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]
- [[zjjxap0vdjkpi8bjqkdz8l2zzrfy4dyi-python3.13-matplotlib-3.10.5]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:54:28 UTC*
