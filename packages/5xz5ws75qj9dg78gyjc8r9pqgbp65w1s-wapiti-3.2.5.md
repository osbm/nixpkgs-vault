---
aliases:
  - wapiti
tags:
  - license/unknown
  - maintainers/fabaff
  - outputs/dist
  - outputs/out
---

# wapiti

## 📝 Description

Wapiti allows you to audit the security of your websites or web applications.
It performs "black-box" scans (it does not study the source code) of the web
application by crawling the webpages of the deployed webapp, looking for
scripts and forms where it can inject data. Once it gets the list of URLs,
forms and their inputs, Wapiti acts like a fuzzer, injecting payloads to see
if a script is vulnerable.


## 📋 Package Information

- **Name**: `wapiti`
- **Version**: `3.2.5`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Web application vulnerability scanner
- **Homepage**: [https://wapiti-scanner.github.io/](https://wapiti-scanner.github.io/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`
## 👥 Maintainers

- @fabaff


## 🔧 Build Information

- **Derivation Path**: `/nix/store/5xz5ws75qj9dg78gyjc8r9pqgbp65w1s-wapiti-3.2.5.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/wa/wapiti/package.nix:161`
- **Outputs**:
  - `dist`:  `/nix/store/5xz5ws75qj9dg78gyjc8r9pqgbp65w1s-wapiti-3.2.5`
  - `out`:  `/nix/store/5xz5ws75qj9dg78gyjc8r9pqgbp65w1s-wapiti-3.2.5`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[0h4nd27gqmy4w8zlxzr95bl0krzhrgjl-python3.13-h11-0.16.0]]
- [[1mxyv5wmnq0srsx19piaadpqdd21p07r-writable-tmpdir-as-home-hook]]
- [[23a0jq3jq5m95nnrrihyg2jb3l79vaym-python3.13-markupsafe-3.0.2]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2cn0bqavrz0zpancngbl5imqz8l5jnvm-python3.13-loguru-0.7.3]]
- [[4b1nxkkprbrmfn52l1fp9sqw9w06xrrr-python3.13-aiohttp-3.12.15]]
- [[4rqmxgb1lzwmlbc0pw2bjh8xibknsbmh-python3.13-msgpack-1.1.1]]
- [[6nzgwlri969sax84d2p0rn0zdjqrj22k-python3.13-wapiti-swagger-0.1.9]]
- [[74snwlw7cal05c4jsy9fmk46j7ajgmsq-python3.13-beautifulsoup4-4.13.4]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[81lj5hnxnmlbfbbvs3ksblacymimp8g5-python3.13-yaswfp-unstable-20210331]]
- [[8b8673czicchx5y1kk43lagjxzzwipjd-python3.13-tld-0.13.1]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[caiv434xs7qzlk8gjq1v9h7c98dbf18c-python3.13-mitmproxy-12.1.2]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[dnbzpphxbd6h31n44gfwbg1qf9q03wcr-pypa-build-hook.sh]]
- [[fmgak3lvqw3ff8wym1v40kgi0b5i1iza-python-runtime-deps-check-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[gd3c6d1li209nbyv1wsx5gmxhjbz36l5-source]]
- [[hnnx919i3xwmk8g3fhkdzspvgg7yk6dl-python3.13-httpcore-1.0.9]]
- [[i609rz7pajx9zac7b6bd6hc8f5c11vfj-python3.13-aiocache-0.12.3]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[ifiiii8ccy9q6dh8a38rn33jzk0m36l6-python3.13-wapiti-arsenic-28.2]]
- [[j3kpppl9dpwvva23c2a73w03l052jrlj-python-relax-deps-hook]]
- [[j5m3wi048fyb5wxj0v2gylmzi52a33z0-python3.13-browser-cookie3-0.20.1]]
- [[jmg2c7bm1cbc0akgbbpjmrbsn792vw86-pytest-check-hook]]
- [[kj4ci1wa705q8xq0zqy9nxl7n9f6jb32-python3.13-respx-0.22.0]]
- [[ky629l5wqywcf8j030mln0nwfqgjp8zw-python3.13-dnspython-2.7.0]]
- [[lzvy25g887aypn07ah8igv72z7b9jb88-version-check-hook]]
- [[nmy2q4zs1nnh2qlxb2nghy041k3vvyjy-python3.13-typing-extensions-4.14.1]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[qyyx96b6156yg8m9p1w67mvgm69lk9hb-python3.13-aiosqlite-0.21.0]]
- [[r9kr0hwdyzkl1gz9k4i9mip1jgl2w4c3-python3.13-sqlalchemy-2.0.42]]
- [[raj3237wd3mqmnl4v7l0klfy00rpnyvd-python3.13-urwid-3.0.2]]
- [[smdvbqwhfnc80pjss6g4gncn4jcvrrg6-python3.13-httpx-ntlm-1.4.0]]
- [[sqzyvhgk1znf60pi5v59vyl617cfh22h-python3.13-pyasn1-0.6.1]]
- [[vfb2h653y4k8ag9vlrqa6gh2pdjkkin2-python3.13-pytest-cov-stub-1.0.0]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[vvhz27lhj8slcbmq0nlypw3f1aq1qbl1-python3.13-httpx-0.28.1]]
- [[wg5y3m50pr5mjw7r51dlayap4rq4zlqx-python3.13-packaging-25.0]]
- [[wv6cavji8prx5qf3kgxid90nyh4j9wwy-python3.13-pytest-asyncio-1.1.0]]
- [[wxpbqgs01rjnbca1lwnva0xc4vkb7181-python3.13-mako-1.3.10]]
- [[z3q41vfm6nnr2i8gs0rkvxrwwvrpywk3-python3.13-humanize-4.12.3]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:11:08 UTC*
