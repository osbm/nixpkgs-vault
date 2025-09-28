---
aliases:
  - python313Packages.sphinx-better-theme
tags:
  - license/unknown
  - maintainers/KAction
  - outputs/dist
  - outputs/doc
  - outputs/out
---

# python313Packages.sphinx-better-theme

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

- **Name**: `python313Packages.sphinx-better-theme`
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

- **Derivation Path**: `/nix/store/m2f4rm2qiw1rla27k9bz3922cs4hlv85-python3.13-sphinx-better-theme-0.1.5.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/python-modules/sphinx-better-theme/default.nix:30`
- **Outputs**:
  - `dist`:  `/nix/store/m2f4rm2qiw1rla27k9bz3922cs4hlv85-python3.13-sphinx-better-theme-0.1.5`
  - `doc`:  `/nix/store/m2f4rm2qiw1rla27k9bz3922cs4hlv85-python3.13-sphinx-better-theme-0.1.5`
  - `out`:  `/nix/store/m2f4rm2qiw1rla27k9bz3922cs4hlv85-python3.13-sphinx-better-theme-0.1.5`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[89zsngnp1b50hzl763gisjppc7gg46mz-source]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[wiymq0rb9pki1dcp8nvwj0gqd8x9ppw7-setuptools-build-hook]]
- [[xgw1wk640brg0fcp4943df77gk4qkj3p-python3.13-sphinx-hook]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:34:35 UTC*
