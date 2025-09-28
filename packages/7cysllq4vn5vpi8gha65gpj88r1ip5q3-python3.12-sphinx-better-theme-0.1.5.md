---
aliases:
  - python312Packages.sphinx-better-theme
tags:
  - license/unknown
  - maintainers/KAction
  - outputs/dist
  - outputs/doc
  - outputs/out
---

# python312Packages.sphinx-better-theme

## 📝 Description

This is a modified version of the default Sphinx theme with the following
goals:

1. Remove frivolous colors, especially hard-coded ones
2. Improve readability by limiting width and using more whitespace
3. Encourage visual customization through CSS, not themeconf
4. Use semantic markup

v0.1 meets goals one and two. Goal three is partially complete; it's simple to
add your own CSS file without creating a whole new theme.
you'd like something changed.

To use the theme, set ``html_theme_path`` to contain
``better.better_theme_path``, and set ``html_theme`` to ``'better'``::

    from better import better_theme_path
    html_theme_path = [better_theme_path]
    html_theme = 'better'


## 📋 Package Information

- **Name**: `python312Packages.sphinx-better-theme`
- **Version**: `0.1.5`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Better Sphinx Theme
- **Homepage**: [https://github.com/irskep/sphinx-better-theme](https://github.com/irskep/sphinx-better-theme)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @KAction


## 🔧 Build Information

- **Derivation Path**: `/nix/store/7cysllq4vn5vpi8gha65gpj88r1ip5q3-python3.12-sphinx-better-theme-0.1.5.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/python-modules/sphinx-better-theme/default.nix:30`
- **Outputs**:
  - `dist`:  `/nix/store/7cysllq4vn5vpi8gha65gpj88r1ip5q3-python3.12-sphinx-better-theme-0.1.5`
  - `doc`:  `/nix/store/7cysllq4vn5vpi8gha65gpj88r1ip5q3-python3.12-sphinx-better-theme-0.1.5`
  - `out`:  `/nix/store/7cysllq4vn5vpi8gha65gpj88r1ip5q3-python3.12-sphinx-better-theme-0.1.5`

## 🔗 Dependencies

- [[7vyvc6rdpjf65mrbzbgcax3bp1iz3xf6-setuptools-build-hook]]
- [[89zsngnp1b50hzl763gisjppc7gg46mz-source]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[di2np59yg9yf560yms5ff9188a5gnlbb-python-imports-check-hook.sh]]
- [[dkqa3dj2k1vqrmlyd6hrdf8dww0f5dr9-python-remove-tests-dir-hook]]
- [[fhrpbbzpqw4bvsy4ixq1fb9k2aaslnw0-python-catch-conflicts-hook]]
- [[fz0k8m7chhichwdj1h1g54hjfh80g3nm-python3-3.12.11]]
- [[g9bcdx47nd5qfi29d66nbxbwckd5g99m-python-namespaces-hook.sh]]
- [[j45jmjf6mwz46p7f0f8hjpnzi9pz2pzv-wrap-python-hook]]
- [[kh0627w4wff8syd1iis567224170xw3l-pypa-install-hook]]
- [[m4iq0kfqyczhz1hfwsxv7h8rz92s243i-python3.12-sphinx-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:15:57 UTC*
