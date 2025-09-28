---
aliases:
  - todoman
tags:
  - license/unknown
  - maintainers/leenaars
  - maintainers/antonmosich
  - outputs/dist
  - outputs/doc
  - outputs/man
  - outputs/out
---

# todoman

## 📝 Description

Todoman is a simple, standards-based, cli todo (aka task) manager. Todos
are stored into iCalendar files, which means you can sync them via CalDAV
using, for example, vdirsyncer.

Todos are read from individual ics files from the configured directory.
This matches the vdir specification. There is support for the most common TODO
features for now (summary, description, location, due date and priority) for
now.
Unsupported fields may not be shown but are never deleted or altered.


## 📋 Package Information

- **Name**: `todoman`
- **Version**: `4.6.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Standards-based task manager based on iCalendar
- **Homepage**: [https://github.com/pimutils/todoman](https://github.com/pimutils/todoman)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @leenaars
- @antonmosich


## 🔧 Build Information

- **Derivation Path**: `/nix/store/sk1pmgsx6ly12cald5msv0kksbn9ppij-todoman-4.6.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/to/todoman/package.nix:99`
- **Outputs**:
  - `dist`:  `/nix/store/sk1pmgsx6ly12cald5msv0kksbn9ppij-todoman-4.6.0`
  - `doc`:  `/nix/store/sk1pmgsx6ly12cald5msv0kksbn9ppij-todoman-4.6.0`
  - `man`:  `/nix/store/sk1pmgsx6ly12cald5msv0kksbn9ppij-todoman-4.6.0`
  - `out`:  `/nix/store/sk1pmgsx6ly12cald5msv0kksbn9ppij-todoman-4.6.0`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[1mxyv5wmnq0srsx19piaadpqdd21p07r-writable-tmpdir-as-home-hook]]
- [[22067a6y3jqcmwj75pd2v2a9ccizajd0-jq-1.8.1]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[5z6nnza3fql5kinsgpk2in7ap7s15rw1-python3.13-click-log-0.4.0]]
- [[6ijpnbfpx4f261l8bsdk19n2jvgdzhwk-python3.13-click-8.1.8]]
- [[7qdbnnxcr5ysjbbvrmby8vvnwbrffy9n-python3.13-pyxdg-0.28]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[9h7r64zlgf3g51hjhxnf3i6xdqz1lhny-python3.13-freezegun-1.5.4]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cyl7ldj74xf5a7xfi9fvgxdm02qp0kfl-python3.13-hypothesis-6.136.9]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[dnbzpphxbd6h31n44gfwbg1qf9q03wcr-pypa-build-hook.sh]]
- [[fmgak3lvqw3ff8wym1v40kgi0b5i1iza-python-runtime-deps-check-hook.sh]]
- [[g1rh1agrz3fk3hrqgrna3yhr86x4bpi2-python3.13-tabulate-0.9.0]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[ifj65ycwqv4hpayyfpfrdjyjhjlfxndw-source]]
- [[jmg2c7bm1cbc0akgbbpjmrbsn792vw86-pytest-check-hook]]
- [[ll81anmn50q693zqllw3xk1ag95v8dbx-python3.13-icalendar-6.3.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[q8kcwi3c7k3siwp5gazkpr0qsa8ybc11-python3.13-click-repl-0.3.0]]
- [[raj3237wd3mqmnl4v7l0klfy00rpnyvd-python3.13-urwid-3.0.2]]
- [[rglfskdlixi4wf58wirp655q5pszsa61-python3.13-parsedatetime-2.6]]
- [[vfb2h653y4k8ag9vlrqa6gh2pdjkkin2-python3.13-pytest-cov-stub-1.0.0]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[wx7mlag0926gbdvhxvadk0glscmi5gzg-python3.13-pytz-2025.2]]
- [[wzv10xlid5lm4i5fgsqiv5ksqmmk0114-python3.13-sphinx-rtd-theme-3.0.2]]
- [[xfqdk1k7y20kk46ij000l468ds58jif3-python3.13-setuptools-scm-9.0.1]]
- [[xgw1wk640brg0fcp4943df77gk4qkj3p-python3.13-sphinx-hook]]
- [[xzg0ff27p273fgi0j7y4yxyq0kky5afj-python3.13-atomicwrites-1.4.1]]
- [[z0pn2q94jd6p96b34636d7bsliyzh2l8-python3.13-sphinx-click-6.0.0]]
- [[z3q41vfm6nnr2i8gs0rkvxrwwvrpywk3-python3.13-humanize-4.12.3]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:49:36 UTC*
