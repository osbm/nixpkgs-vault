---
aliases:
  - xen
tags:
  - license/unknown
  - maintainers/hehongbo
  - maintainers/CertainLach
  - maintainers/SigmaSquadron
  - maintainers/digitalrane
  - outputs/boot
  - outputs/dev
  - outputs/doc
  - outputs/man
  - outputs/out
---

# xen

## 📝 Description

The Xen Project Hypervisor is a virtualisation technology defined as a *type-1
hypervisor*, which allows multiple virtual machines, known as domains, to run
concurrently with the host on the physical machine. On a typical *type-2
hypervisor*, the virtual machines run as applications on top of the
host. NixOS runs as the privileged **Domain 0**, and can paravirtualise or fully
virtualise **Unprivileged Domains**.

Use with the `qemu_xen` package.

Includes:
* `xen-4.20.1.efi`: The Xen Project's [EFI binary](https://xenbits.xenproject.org/docs/4.20-testing/misc/efi.html), available on the `boot` output of this package.
* `xen-4.20.1`: The Xen Project's multiboot binary, available on the `boot` output of this package.
* `seabios`: Support for the SeaBIOS boot firmware on HVM domains.
* `ovmf`: Support for the OVMF UEFI boot firmware on HVM domains.
* `ipxe`: Support for the iPXE boot firmware on HVM domains.

## 📋 Package Information

- **Name**: `xen`
- **Version**: `4.20.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Type-1 hypervisor intended for embedded and hyperscale use cases
- **Homepage**: [https://xenproject.org/](https://xenproject.org/)
- **License**: `unknown`
## 👥 Maintainers

- @hehongbo
- @CertainLach
- @SigmaSquadron
- @digitalrane


## 🔧 Build Information

- **Derivation Path**: `/nix/store/yydw8k3ciyvbc8cvibn7yp324359xlgg-xen-4.20.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/xe/xen/package.nix:388`
- **Outputs**:
  - `boot`:  `/nix/store/yydw8k3ciyvbc8cvibn7yp324359xlgg-xen-4.20.1`
  - `dev`:  `/nix/store/yydw8k3ciyvbc8cvibn7yp324359xlgg-xen-4.20.1`
  - `doc`:  `/nix/store/yydw8k3ciyvbc8cvibn7yp324359xlgg-xen-4.20.1`
  - `man`:  `/nix/store/yydw8k3ciyvbc8cvibn7yp324359xlgg-xen-4.20.1`
  - `out`:  `/nix/store/yydw8k3ciyvbc8cvibn7yp324359xlgg-xen-4.20.1`

## 🔗 Dependencies

- [[0y20y5glzrd67xskzh9vjindzjl1jiiv-bison-3.8.2]]
- [[19dkqq6j7z6ahjqgj3pa5wkkj6rl3wdg-auto-patchelf-hook]]
- [[19y8rq249d578ag3ak1xvfb43rkzdy7n-xsa473-1.patch]]
- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[3b5aag9nkc82699nh2rq53xpsdwlhvnm-xen-08f0439]]
- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[3z6dcp2i69nn7h8kwl6snf651i7ds14v-util-linux-minimal-2.41.1]]
- [[4lykrm96bxajhbrv42nzm365n9yf9s1y-coreutils-9.7]]
- [[6lmmmpmfwdflrxnl93nzbqh92yn782h6-acpica-tools-20250807]]
- [[7iqk0g6h0lrprqbw4nb7rpkr79dzgl2g-ipxe-1.21.1-unstable-2025-09-18]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[9nm9ia66h8iqcc75h5zkn8bg6y7452c7-0002-scripts-external-executable-calls.patch]]
- [[9qky27qydgriwxkan4r6mh0q5s1mnsfx-seabios-1.17.0]]
- [[al49frxsp7fhdpyi36dqs0bdwgz40gb2-xsa472-1.patch]]
- [[ap65r3906858k58jisl8qphg092ywhkp-zstd-1.5.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[hvj99gxd587y6qpvmlvggb37jl1jkd6d-ocaml-5.3.0]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[iw7i7rklrzsglv5l2p8am46y9xa92s8r-xz-5.8.1]]
- [[jmq1spk1cdbx3w7cwk8d2m0wlgjwny1m-yajl-2.1.0-unstable-2024-02-01]]
- [[l07v8fhyw17a24sklyx76baqlvajvvsv-xsa473-2.patch]]
- [[l2sbq1hgn5radixccg11a3hibnbzj0yf-xsa472-2.patch]]
- [[lcm255yygf2ynzhgspppj3p5a5xkmxnz-e2fsprogs-1.47.3]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[m2glg0c5k3xgb82x8xpvd3q7ygpw8a37-libnl-3.11.0]]
- [[mrrjs2wpc1dqhkhcys9zidj9bi3pvg1d-xsa472-3.patch]]
- [[nfccfj86560vhr037if3bdxdm390apj6-lzo-2.10]]
- [[nmkmyb7a228amldqqq405d7q9149hgyx-binutils-2.44]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qsc6bph6wsr6rwjqamcmivdh6zznbh4y-OVMF-202508]]
- [[v28sdl3535sxb6a71z5faqdzbns9pv0h-bash-interactive-5.3p3]]
- [[wy61x67y125m36dp7l7xhzqbi30mxg1d-flex-2.6.4]]
- [[y0x00cv4f56y7gyqz3s1x410cf3v1lvi-dev86-1.0.1]]
- [[y4lfwlviqzkdrk9973a02vpl0fk4h1vy-bzip2-1.0.8]]
- [[y4p2cj0lr29dsczxm3024pgp6f4mrjp0-ocaml5.3.0-findlib-1.9.8]]
- [[zb5cj6gmxg0g561dg8vkmb4sb67z2b07-pandoc-cli-3.6]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/yji5l3m95p7z8hhcdyxfmdxwjacqqg7p-0001-makefile-efi-output-directory.patch`

---
*Generated on 2025-09-27 13:09:29 UTC*
