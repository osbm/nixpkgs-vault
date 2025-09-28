---
aliases:
  - python312Packages.euporie
tags:
  - license/unknown
  - maintainers/pacien
  - maintainers/renesat
  - outputs/dist
  - outputs/out
---

# python312Packages.euporie

## 📝 Description

Similar to `jupyter lab` or `jupyter notebook`, This package
can only be used inside a python environment. To quickly summon
a python environment with euporie, you can use:
```
nix-shell -p 'python3.withPackages (ps: with ps; [ euporie ])'
```


## 📋 Package Information

- **Name**: `python312Packages.euporie`
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

- **Derivation Path**: `/nix/store/0ji18vzqr4q0s820csvwbrgznrmwy0ry-python3.12-euporie-2.8.13.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/python-modules/euporie/default.nix:99`
- **Outputs**:
  - `dist`:  `/nix/store/0ji18vzqr4q0s820csvwbrgznrmwy0ry-python3.12-euporie-2.8.13`
  - `out`:  `/nix/store/0ji18vzqr4q0s820csvwbrgznrmwy0ry-python3.12-euporie-2.8.13`

## 🔗 Dependencies

- [[113b6hxwnpbyv852cf0zwd6a6z2w8m68-python3.12-aiohttp-3.12.15]]
- [[1mxyv5wmnq0srsx19piaadpqdd21p07r-writable-tmpdir-as-home-hook]]
- [[1vdjhy94i353i6sbw8g30vfddbh49a9g-python3.12-aenum-3.1.15]]
- [[2a76j8gw9kswbd56w687i4fmwvnpq0cy-python3.12-markdown-it-py-3.0.0]]
- [[2k71fvzprqr677wnasb5g015h7kdlpxf-python3.12-timg-1.1.6]]
- [[5c9a3jn60a3jyw9ajsnd3a5hvlpdfq93-python3.12-ipykernel-6.30.1]]
- [[5vsffdi0kgla24ca4l9bv0fxzc7s2qyk-pypa-build-hook.sh]]
- [[6a7wqn7f6hcjvh49630b47bwdzyv914v-python3.12-imagesize-1.4.1]]
- [[739zlyjhr8faafkciba1ck57s7m1k18s-python3.12-html2text-2025.4.15]]
- [[7pw6mhhlbjz7vb2py5vyxdlaw3b4waw9-python3.12-sixelcrop-0.1.9]]
- [[8j4zbjkkrg2kzs50mam0h67lw5gbwdn5-python3.12-linkify-it-py-2.0.3]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bbl5x6p28inxrcjwvr2hi5yylsf5y8va-python3.12-jupytext-1.17.2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bki4kxsbvd13sz5a2bqr2b9y7vvgpmiy-python-runtime-deps-check-hook.sh]]
- [[bn85b1qplhk664nvhp9xjgh1s63p5jdr-python-relax-deps-hook]]
- [[di2np59yg9yf560yms5ff9188a5gnlbb-python-imports-check-hook.sh]]
- [[dkqa3dj2k1vqrmlyd6hrdf8dww0f5dr9-python-remove-tests-dir-hook]]
- [[farc3d8rygdmd423fw2zvv11xqidhvgi-python3.12-pygments-2.19.2]]
- [[fhrpbbzpqw4bvsy4ixq1fb9k2aaslnw0-python-catch-conflicts-hook]]
- [[ficczvn8b3qmkkvad9mgv9ljs1krhnxc-python3.12-mdit-py-plugins-0.4.2]]
- [[fjyqy8qfq6g742gmpwa9ixzv77y548bd-python3.12-pytest-cov-stub-1.0.0]]
- [[fz0k8m7chhichwdj1h1g54hjfh80g3nm-python3-3.12.11]]
- [[g9bcdx47nd5qfi29d66nbxbwckd5g99m-python-namespaces-hook.sh]]
- [[j45jmjf6mwz46p7f0f8hjpnzi9pz2pzv-wrap-python-hook]]
- [[ji8jwdz0mzm5z19pnw8rp1a5rm7jhnxg-python3.12-platformdirs-4.3.8]]
- [[jwvjj3l7n5hkjpvmb2dw6b6wsc3fg106-python3.12-universal-pathlib-0.2.6]]
- [[jzdl0i3di0kb5v41nvfwgc4j9dc2km9x-pytest-check-hook]]
- [[kh0627w4wff8syd1iis567224170xw3l-pypa-install-hook]]
- [[m1frhzhcibf9rsp57h5hzw46shk3xahs-python3.12-pytest-asyncio-1.1.0]]
- [[n5ymf85psm25bmlfqflj7ajfnqwj6a7g-python3.12-flatlatex-0.15]]
- [[n9wv4d06cpbh0kw3knb2cxrh4bv8sfjz-python3.12-pyperclip-1.9.0]]
- [[nxkv5589dvmqlxs3wrjxgggjbfn1831i-python3.12-jupyter-client-8.6.3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pzq7k2k0jqg53dayfmcx4cqg6dix7a5w-python3.12-typing-extensions-4.14.1]]
- [[q2wblirg740bczx6814r17vv1hdd38ly-python3.12-pillow-11.3.0]]
- [[qr5rjwg6mdbawzg3nlijnk5qq34lf3vy-python3.12-prompt-toolkit-3.0.51]]
- [[v9an8cin4v0rn4rzlishgisfrn8kn177-python3.12-fastjsonschema-2.21.1]]
- [[vllnj0xsh5mdm22pwq2mwjyz29kjpld8-python3.12-fsspec-2025.3.2]]
- [[xd6hjs13vg5p7hp5pnwr4cba0vlh02hw-source]]
- [[xj97f4d4d468fjvhhx214ma7zh4l2wyc-python3.12-setuptools-80.9.0]]
- [[xwxgchijfwzn543d6g2zprwrj06h6g9n-python3.12-python-magic-0.4.27]]
- [[y3rs6r1b8v0xyq95fsr7irqsdix69xx4-python3.12-nbformat-5.10.4]]
- [[yky4w8wk411rw7j1w9zg61n6ahh7irxb-python3.12-hatchling-1.27.0]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:19:23 UTC*
