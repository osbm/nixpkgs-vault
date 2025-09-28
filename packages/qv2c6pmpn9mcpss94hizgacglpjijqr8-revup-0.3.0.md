---
aliases:
  - revup
tags:
  - license/unknown
  - outputs/dist
  - outputs/out
---

# revup

## 📝 Description

Revup provides command-line tools that allow developers to iterate
faster on parallel changes and reduce the overhead of creating and
maintaining code reviews.

Features:

- Revup creates multiple independent chains of branches for you in the
  background and without touching your working tree. It then creates and
  manages github pull requests for all those branches.
- Pull requests target the actual base branch and can be merged manually
  or by continuous integration
- Rebase detection saves time and continuous integration cost by not
  re-pushing if the patch hasn't changed
- Adds reviewers, labels, and creates drafts all from the commit text
- Adds auto-updating "review graph" and "patchsets" elements to make
  pull requests easier to navigate
- revup amend and revup restack save time by replacing slow rebases


## 📋 Package Information

- **Name**: `revup`
- **Version**: `0.3.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Efficient git workflow and code review toolkit
- **Homepage**: [https://github.com/Skydio/revup](https://github.com/Skydio/revup)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/qv2c6pmpn9mcpss94hizgacglpjijqr8-revup-0.3.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/re/revup/package.nix:51`
- **Outputs**:
  - `dist`:  `/nix/store/qv2c6pmpn9mcpss94hizgacglpjijqr8-revup-0.3.0`
  - `out`:  `/nix/store/qv2c6pmpn9mcpss94hizgacglpjijqr8-revup-0.3.0`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2i16vhsnncslkql7j47bkmz6z4ln6xbp-python3.13-pip-25.0.1]]
- [[4b1nxkkprbrmfn52l1fp9sqw9w06xrrr-python3.13-aiohttp-3.12.15]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bwhrp2f1yyk2y2aglwjbh2hf5azp6ylh-python3.13-wheel-0.46.1]]
- [[ciqn9cwwh1zf1vki5mva76nhfkrxarq9-python3.13-aiosignal-1.4.0]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[dnbzpphxbd6h31n44gfwbg1qf9q03wcr-pypa-build-hook.sh]]
- [[fmgak3lvqw3ff8wym1v40kgi0b5i1iza-python-runtime-deps-check-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[gw9msiijkswnv7bv8rj1x8dgcpa60lby-python3.13-multidict-6.6.4]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[j66w4a4zjmfxp7j44g9jrhrxvcjlfmya-python3.13-async-lru-2.0.5]]
- [[jjlcxa2kqqg6vv4qi9fq1j8cqx64s4xs-python3.13-yarl-1.21.1]]
- [[lrbclcph1hpv5j144lgma5lmswj2c48l-python3.13-pytest-8.4.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[qznzfkf5qiqnwh3rgjfycs05mgpfz906-python3.13-charset-normalizer-3.4.3]]
- [[rs3h8g5y8rznyb4k64hgvzvp3jgsr5b8-python3.13-requests-2.32.4]]
- [[snqxir6mvjqiqnis4s2z9ddqqnx392rr-revup-0.3.0.tar.gz]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[wsgi40dj0aq73c9c3n07a295nbcmlm3i-python3.13-rich-14.1.0]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]
- [[z9cgy1dn9lmmf90ac39x5z46wi7vlnrr-python3.13-async-timeout-5.0.1]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:19:44 UTC*
