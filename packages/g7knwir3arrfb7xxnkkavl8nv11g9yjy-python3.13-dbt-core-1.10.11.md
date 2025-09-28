---
aliases:
  - python313Packages.dbt-core
tags:
  - license/unknown
  - maintainers/mausch
  - maintainers/tjni
  - outputs/dist
  - outputs/out
---

# python313Packages.dbt-core

## 📝 Description

The dbt tool needs adapters to data sources in order to work. The available
adapters are:

  dbt-bigquery
  dbt-postgres
  dbt-redshift
  dbt-snowflake

An example of building this package with a few adapters:

  dbt.withAdapters (adapters: [
    adapters.dbt-bigquery
    adapters.dbt-postgres
  ])


## 📋 Package Information

- **Name**: `python313Packages.dbt-core`
- **Version**: `1.10.11`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Enables data analysts and engineers to transform their data using the same practices that software engineers use to build applications
- **Homepage**: [https://github.com/dbt-labs/dbt-core](https://github.com/dbt-labs/dbt-core)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @mausch
- @tjni


## 🔧 Build Information

- **Derivation Path**: `/nix/store/g7knwir3arrfb7xxnkkavl8nv11g9yjy-python3.13-dbt-core-1.10.11.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/python-modules/dbt-core/default.nix:105`
- **Outputs**:
  - `dist`:  `/nix/store/g7knwir3arrfb7xxnkkavl8nv11g9yjy-python3.13-dbt-core-1.10.11`
  - `out`:  `/nix/store/g7knwir3arrfb7xxnkkavl8nv11g9yjy-python3.13-dbt-core-1.10.11`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[0pqgsv97wyw3nvkwqf8d4h65kn57k6i5-python3.13-dbt-protos-1.0.376]]
- [[0r5vk0k5fpi7mkca4hfbn0kkjm12cabk-python3.13-networkx-3.5]]
- [[23qdd2kqhkj8g3whnjrz0649y51ib6yb-python3.13-agate-1.13.0]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2wh0yh10ss2mcqfghlbww7lmbrx7s7nb-python3.13-daff-1.4.2]]
- [[4rqmxgb1lzwmlbc0pw2bjh8xibknsbmh-python3.13-msgpack-1.1.1]]
- [[610jrx9iqvxawwh0c9rm1lwxsx8bq976-python3.13-pydantic-settings-2.10.1]]
- [[6ijpnbfpx4f261l8bsdk19n2jvgdzhwk-python3.13-click-8.1.8]]
- [[6s83i11x3c7jxyx309wzmssadw0vwbsw-python3.13-dbt-extractor-0.6.0]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[dnbzpphxbd6h31n44gfwbg1qf9q03wcr-pypa-build-hook.sh]]
- [[fccb7if2kalinvfh2yyls1z8ab7vd4k6-python3.13-pathspec-0.12.1]]
- [[fmgak3lvqw3ff8wym1v40kgi0b5i1iza-python-runtime-deps-check-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[gv967y0kwjw7d8z8hx0z070fzwc2xz3v-source]]
- [[h05wqxmismxpyizn01bvkmwgqzy4z6ij-python3.13-protobuf-6.32.0]]
- [[hp0q08m7j4v6xd8yyy5mpwylq8j2b718-python3.13-dbt-adapters-1.16.7]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[j3kpppl9dpwvva23c2a73w03l052jrlj-python-relax-deps-hook]]
- [[k1vfjgw69qv21dqqaaxjrl1d2yj8l60c-python3.13-snowplow-tracker-1.1.0]]
- [[k3gjk0niyfn8bc6m5nzqcj1x6b3bpi2d-python3.13-mashumaro-3.16]]
- [[k7qk29w100bla8gvgp97wykgs2ihi9mf-python3.13-dbt-common-1.28.0-unstable-2025-08-14]]
- [[n32169by3pxfw3w085lad8mzw02i1z4i-python3.13-sqlparse-0.5.3]]
- [[nmy2q4zs1nnh2qlxb2nghy041k3vvyjy-python3.13-typing-extensions-4.14.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[qfrmizlp68dm433a0lya8hr3f9gncskj-python3.13-dbt-semantic-interfaces-0.9.0]]
- [[qxjr9myqxprhy4r2h3k9ln61msy4qlyr-python3.13-logbook-1.8.2]]
- [[r7l5c5x6l7nafwhpc02iyqbgl310cwb9-python3.13-pydantic-2.11.7]]
- [[rs3h8g5y8rznyb4k64hgvzvp3jgsr5b8-python3.13-requests-2.32.4]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[wg5y3m50pr5mjw7r51dlayap4rq4zlqx-python3.13-packaging-25.0]]
- [[wx7mlag0926gbdvhxvadk0glscmi5gzg-python3.13-pytz-2025.2]]
- [[x9vbllr5alngfap8xr7kxqi5cqnj9z0r-python3.13-jinja2-3.1.6]]
- [[yx9ag0icz7v1fbkq3an2658q40b7cgd2-python3.13-pyyaml-6.0.2]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:43:02 UTC*
