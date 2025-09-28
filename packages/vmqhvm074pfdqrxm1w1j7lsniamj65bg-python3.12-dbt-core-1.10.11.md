---
aliases:
  - python312Packages.dbt-core
tags:
  - license/unknown
  - maintainers/mausch
  - maintainers/tjni
  - outputs/dist
  - outputs/out
---

# python312Packages.dbt-core

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

- **Name**: `python312Packages.dbt-core`
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

- **Derivation Path**: `/nix/store/vmqhvm074pfdqrxm1w1j7lsniamj65bg-python3.12-dbt-core-1.10.11.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/development/python-modules/dbt-core/default.nix:105`
- **Outputs**:
  - `dist`:  `/nix/store/vmqhvm074pfdqrxm1w1j7lsniamj65bg-python3.12-dbt-core-1.10.11`
  - `out`:  `/nix/store/vmqhvm074pfdqrxm1w1j7lsniamj65bg-python3.12-dbt-core-1.10.11`

## 🔗 Dependencies

- [[0hi5a7v09xas2hppfz9brx5b52d2kczl-python3.12-agate-1.13.0]]
- [[21hk52g2dfslyjbsymvx2i09ghy4s1s7-python3.12-logbook-1.8.2]]
- [[49562k3y3iazqir7d0y6x8z4ldxc4vii-python3.12-snowplow-tracker-1.1.0]]
- [[5vsffdi0kgla24ca4l9bv0fxzc7s2qyk-pypa-build-hook.sh]]
- [[7l7cir2dmw9209h072fh7pczijrkbw45-python3.12-pyyaml-6.0.2]]
- [[8ga9zvl3762aw0ayvxd43pvfxb0x07g2-python3.12-dbt-extractor-0.6.0]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[9kkq3l2c1cpayf725b35dk13vvivr8c8-python3.12-dbt-protos-1.0.376]]
- [[9llbcdsy1kq4n8ps049z87h6ylzch4cy-python3.12-sqlparse-0.5.3]]
- [[ackfwxs8xhqjiydb05rb69bhdjzf4pn7-python3.12-dbt-adapters-1.16.7]]
- [[adjfjgffgclhpv4hwniv4w0y6j1jssvz-python3.12-pathspec-0.12.1]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bk8mkf75v8zbknmidm5ac2qa8y9r6wcr-python3.12-requests-2.32.4]]
- [[bki4kxsbvd13sz5a2bqr2b9y7vvgpmiy-python-runtime-deps-check-hook.sh]]
- [[bn85b1qplhk664nvhp9xjgh1s63p5jdr-python-relax-deps-hook]]
- [[di2np59yg9yf560yms5ff9188a5gnlbb-python-imports-check-hook.sh]]
- [[dkqa3dj2k1vqrmlyd6hrdf8dww0f5dr9-python-remove-tests-dir-hook]]
- [[fhrpbbzpqw4bvsy4ixq1fb9k2aaslnw0-python-catch-conflicts-hook]]
- [[fz0k8m7chhichwdj1h1g54hjfh80g3nm-python3-3.12.11]]
- [[g9bcdx47nd5qfi29d66nbxbwckd5g99m-python-namespaces-hook.sh]]
- [[gv967y0kwjw7d8z8hx0z070fzwc2xz3v-source]]
- [[j45jmjf6mwz46p7f0f8hjpnzi9pz2pzv-wrap-python-hook]]
- [[kdbh3npfaw4n6clgi1ncr0f0z2p5iw4w-python3.12-msgpack-1.1.1]]
- [[kh0627w4wff8syd1iis567224170xw3l-pypa-install-hook]]
- [[mn30if07ryismxck4d25qzxhkfdca7h5-python3.12-mashumaro-3.16]]
- [[nm6c86lr1nf1dgsp8iqhbq383ig8kk4q-python3.12-jinja2-3.1.6]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pfkjlnz4ibv6z84lb4yikqclbydwc4vw-python3.12-pytz-2025.2]]
- [[pzq7k2k0jqg53dayfmcx4cqg6dix7a5w-python3.12-typing-extensions-4.14.1]]
- [[r19w665ql53yvpvg82iznzj6khslvm7n-python3.12-dbt-semantic-interfaces-0.9.0]]
- [[rqhc8d07jqi00l2qlf1wf8151irzw3vb-python3.12-pydantic-settings-2.10.1]]
- [[sva1w6dis1h5m5nkdl9a74ixjahr7fps-python3.12-pydantic-2.11.7]]
- [[v6rkfzwi6q2drhp694ml6pq604cikcc2-python3.12-dbt-common-1.28.0-unstable-2025-08-14]]
- [[x3zrmk95f2ap8hshqpk40z4n8i59glf5-python3.12-packaging-25.0]]
- [[xj97f4d4d468fjvhhx214ma7zh4l2wyc-python3.12-setuptools-80.9.0]]
- [[xlvzi4v3vzkfkrm44kifjflq8aax50na-python3.12-click-8.1.8]]
- [[y4fb116j8zzrqx15ah15xnn64m0zhf2i-python3.12-networkx-3.5]]
- [[z2j49s4mhqr5dy8ykkdjkib9fwhm6gky-python3.12-daff-1.4.2]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]
- [[za8zdmi7p6xghwdv7ii48cikljngj1h7-python3.12-protobuf-6.32.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:13:58 UTC*
