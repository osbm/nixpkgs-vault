---
aliases:
  - python313Packages.euporie
tags:
  - license/unknown
  - maintainers/pacien
  - maintainers/renesat
  - outputs/dist
  - outputs/out
---

# python313Packages.euporie

## 📝 Description

Similar to `jupyter lab` or `jupyter notebook`, This package
can only be used inside a python environment. To quickly summon
a python environment with euporie, you can use:
```
nix-shell -p 'python3.withPackages (ps: with ps; [ euporie ])'
```


## 📋 Package Information

- **Name**: `python313Packages.euporie`
- **Version**: `2.8.13`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Jupyter notebooks in the terminal
- **Homepage**: [https://euporie.readthedocs.io/](https://euporie.readthedocs.io/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @pacien
- @renesat


## 🔧 Build Information

- **Derivation Path**: `/nix/store/swfiwqwksgspbxwjbhmqhiqlizgb2p6i-python3.13-euporie-2.8.13.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/python-modules/euporie/default.nix:99`
- **Outputs**:
  - `dist`:  `/nix/store/swfiwqwksgspbxwjbhmqhiqlizgb2p6i-python3.13-euporie-2.8.13`
  - `out`:  `/nix/store/swfiwqwksgspbxwjbhmqhiqlizgb2p6i-python3.13-euporie-2.8.13`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[10jhr0796d2wz5cgws87a5xz5dhp5igf-python3.13-html2text-2025.4.15]]
- [[1m5k6jw675cz1vkalh64ph2rp4x75mng-python3.13-platformdirs-4.3.8]]
- [[1mxyv5wmnq0srsx19piaadpqdd21p07r-writable-tmpdir-as-home-hook]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2cd9wvwxv5sv71a3vr6hbwfj78vxrbv7-python3.13-fsspec-2025.3.2]]
- [[2ya7z371vgfz7r8d6024fx5r8yx4y6d8-python3.13-nbformat-5.10.4]]
- [[4b1nxkkprbrmfn52l1fp9sqw9w06xrrr-python3.13-aiohttp-3.12.15]]
- [[7cbqswccqkv4yiw16rbwzy6074pikjbb-python3.13-imagesize-1.4.1]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[8mpz429m992vymm7fdp19zlh54yhk99k-python3.13-prompt-toolkit-3.0.51]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[9m7l85h3xmk6fgk61x3avx9rmq1ma115-python3.13-pyperclip-1.9.0]]
- [[aij3bxpfdp189pq4fx7p5cbqicnmmlcw-python3.13-pygments-2.19.2]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[dnbzpphxbd6h31n44gfwbg1qf9q03wcr-pypa-build-hook.sh]]
- [[fhkpwfv255khjyyncxbl0825wyyn8y7v-python3.13-linkify-it-py-2.0.3]]
- [[fmgak3lvqw3ff8wym1v40kgi0b5i1iza-python-runtime-deps-check-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[hgivx7dr21v7dr2p4jkrmwb7b3d08ri8-python3.13-hatchling-1.27.0]]
- [[hv1xx5p37v0imlzvprlj97g9ani38c92-python3.13-universal-pathlib-0.2.6]]
- [[i60yfmxbfiisjyiq13076hfwihf4a2yr-python3.13-jupyter-client-8.6.3]]
- [[i9ihmj0m433zm8ir1xk90ac4vfha7qar-python3.13-timg-1.1.6]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[j3kpppl9dpwvva23c2a73w03l052jrlj-python-relax-deps-hook]]
- [[jkyig2d0mslb754a4qqfrj2wlh0qnx0w-python3.13-jupytext-1.17.2]]
- [[jmg2c7bm1cbc0akgbbpjmrbsn792vw86-pytest-check-hook]]
- [[k7jg0xr24c1pdmydm0q7i45jads63680-python3.13-markdown-it-py-3.0.0]]
- [[krglskr8ddwp8c6yq0kaa3lj3wwqbxv0-python3.13-fastjsonschema-2.21.1]]
- [[nmy2q4zs1nnh2qlxb2nghy041k3vvyjy-python3.13-typing-extensions-4.14.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[ps30k9ym4331dnzsqrpzl1f2ncivpl3p-python3.13-aenum-3.1.15]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[q6q400lfxczcryxxmdyjns44bgjm5qb9-python3.13-sixelcrop-0.1.9]]
- [[r9ddnpas38jsfrpiqhbpwnbmy0abq43m-python3.13-python-magic-0.4.27]]
- [[swwhxdnkhx8q81vm3m58k5kmlgsm4b51-python3.13-pillow-11.3.0]]
- [[vfb2h653y4k8ag9vlrqa6gh2pdjkkin2-python3.13-pytest-cov-stub-1.0.0]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[vp3l4h555x4sindp3g93vvyap7phqkgp-python3.13-mdit-py-plugins-0.4.2]]
- [[wv6cavji8prx5qf3kgxid90nyh4j9wwy-python3.13-pytest-asyncio-1.1.0]]
- [[xd6hjs13vg5p7hp5pnwr4cba0vlh02hw-source]]
- [[z0iak1196w00micd8k9xbrsyqsa99kiy-python3.13-flatlatex-0.15]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]
- [[zrb7lsxiwkbqmv7kjn6j0nlj4ndgq96b-python3.13-ipykernel-6.30.1]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:57:27 UTC*
