---
aliases:
  - azure-cli
tags:
  - license/unknown
  - maintainers/katexochen
  - maintainers/ulrikstrid
  - outputs/dist
  - outputs/out
---

# azure-cli

## 📝 Description

The Azure Command-Line Interface (CLI) is a cross-platform
command-line tool to connect to Azure and execute administrative
commands on Azure resources. It allows the execution of commands
through a terminal using interactive command-line prompts or a script.

`azure-cli` has extension support. For example, to install the `aks-preview` extension, use

```nix
environment.systemPackages = [
  (azure-cli.withExtensions [ azure-cli.extensions.aks-preview ])
];
```

To make the `azure-cli` immutable and prevent clashes in case `azure-cli` is also installed via other package managers,
some configuration files were moved into the derivation. This can be disabled by overriding `withImmutableConfig = false`
when building `azure-cli`.


## 📋 Package Information

- **Name**: `azure-cli`
- **Version**: `2.77.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Next generation multi-platform command line experience for Azure
- **Homepage**: [https://github.com/Azure/azure-cli](https://github.com/Azure/azure-cli)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @katexochen
- @ulrikstrid


## 🔧 Build Information

- **Derivation Path**: `/nix/store/5fbfhgrizkzskiyxxcpy64x6gyfkc357-python3.13-azure-cli-2.77.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/az/azure-cli/package.nix:457`
- **Outputs**:
  - `dist`:  `/nix/store/5fbfhgrizkzskiyxxcpy64x6gyfkc357-python3.13-azure-cli-2.77.0`
  - `out`:  `/nix/store/5fbfhgrizkzskiyxxcpy64x6gyfkc357-python3.13-azure-cli-2.77.0`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[0bavf0ppz7r8b24m8nr40ix8lph04ddf-python3.13-argcomplete-3.6.2]]
- [[0s798hkb6zahxl4pcpqkv5k42lv68mfj-python3.13-azure-storage-common-2.1.0]]
- [[0vj8k22kq9h6z8djsj4rs13mhij9a9km-python3.13-azure-keyvault-certificates-4.10.0]]
- [[0yx8amis1yklq1jl65pgvyd0mf4v9b0l-python3.13-azure-mgmt-iotcentral-9.0.0]]
- [[0zhfhjncigbgyvb248pss7ka1sfgiijx-python3.13-azure-mgmt-servicefabric-2.1.0]]
- [[16mmvncb38jvxi243zw7b3xdv8kj7js2-python3.13-wrapt-1.17.2]]
- [[1j4v10ipf4ii8gs4vafybjz231zca1nm-python3.13-attrs-25.3.0]]
- [[1nmb89xbjpga1209x3ifs5m34g63zgwb-python3.13-azure-mgmt-sql-4.0.0b20]]
- [[239qqn9by0qd1clvxghvjgpwb0wpwzq9-python3.13-semver-3.0.4]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[268gz3k6jnacvwkrm0vnvr4rj8fkksnc-python3.13-azure-nspkg-3.0.2]]
- [[2fjvpavymm3lr9dnbi628namxd03qc0y-python3.13-msal-1.32.3]]
- [[2ryyvahjjqnc1ggm6cfggb94nhn7qx4p-python3.13-py-deviceid-0.1.1]]
- [[2swqh5g4l8h811qnl6m0dxxlzxkk8fzr-python3.13-azure-mgmt-maps-2.1.0]]
- [[3cjxai08z8la5sqhdbkjrx4pjd2rgbl9-python3.13-azure-mgmt-batchai-7.0.0]]
- [[3d7imjdp86kp9grmawk4pk914v6n7hp0-python3.13-knack-0.12.0]]
- [[3gw95s4ikz8qjigw811c45n20z9a9r8a-python3.13-azure-synapse-spark-0.7.0]]
- [[3k7xi6p075f7v5gw0i4vibgd33g9mxyp-python3.13-azure-mgmt-containerregistry-14.0.0]]
- [[4b1nxkkprbrmfn52l1fp9sqw9w06xrrr-python3.13-aiohttp-3.12.15]]
- [[4dcs6gasw3vfjfga1rybq7wm1v35phfr-python3.13-azure-core-1.35.0]]
- [[4saqrrp0xw9kw1pzwl6n08dbkl5s4y5n-python3.13-pyopenssl-25.1.0]]
- [[57nmvcchc394fpgh952dnvic3n8mlh84-python3.13-azure-mgmt-keyvault-12.0.0]]
- [[5hbgdipffhlgmbxgzs9vjrgbfc3kbmvq-python3.13-urllib3-2.5.0]]
- [[5m8cal23fgjsdy7xxxgkglvxq1m5qmk2-python3.13-frozenlist-1.7.0]]
- [[5z89akchxs9li745mv4y2yfxkhar0gs2-python3.13-azure-mgmt-sqlvirtualmachine-1.0.0b5]]
- [[5zq75vfnkwsanibx4avgfizyf8awv2s0-python3.13-azure-mgmt-managementgroups-1.0.0]]
- [[6qbd2bss5yj7ncpxs7smlnz0kn3b2kzd-python3.13-azure-mgmt-search-9.2.0]]
- [[734pqyw7wfgn02s40aqrxwblpjm0w0g9-python3.13-azure-mgmt-appcontainers-3.2.0]]
- [[7i684k8mnqifv9j4wpxwnws6z6ls7r8b-python3.13-azure-mgmt-iothub-4.0.0]]
- [[7m3s2g4vah11qdbf1qn6jq1kq21jg3ls-python3.13-sshtunnel-0.4.0]]
- [[7pbq8ncdrbal7rsxb5i1b4ccsdqpgmia-python3.13-antlr4-python3-runtime-4.13.2]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[81f0k5mrxc1r6cgwgslivi3vp2vh0ypn-python3.13-azure-mgmt-media-9.0.0]]
- [[84j2hb7bla3l8a2y4m0p75qi83zj8rzw-python3.13-paramiko-4.0.0]]
- [[877bqglha9r7d5i1d1hz1y5jl3l0g27z-python3.13-azure-mgmt-applicationinsights-4.1.0]]
- [[87inywz5rr8kmaxqzrgw3f53pkgsr31m-python3.13-pyjwt-2.10.1]]
- [[8gsr0ng9r46kpjqn5swdmlviph4d4bjq-python3.13-azure-mgmt-recoveryservices-3.1.0]]
- [[8j5b6zyyrmvmlm9g2xzq7ipkqpp7r8vj-python3.13-msrestazure-0.6.4]]
- [[8ld5397ixyr6fjlmbaikw8r6dd243hw3-python3.13-azure-mgmt-security-7.0.0]]
- [[8m53ih1dxdm8adv5agixy1fzp9jgfrx5-python3.13-microsoft-security-utilities-secret-masker-1.0.0b4]]
- [[8mxkhfsfpi9arz1a8bivx1maqcd62xlz-python3.13-azure-mgmt-mysqlflexibleservers-1.0.0b2]]
- [[8p99ybapk8fdvw2apsfwjf4h4p6dczqs-python3.13-adal-1.2.7]]
- [[8skk840jbh5dxl6q40s9jzvq0f4j3sdp-python3.13-invoke-2.2.0]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[9kzwxwpwcyjygx2yha8cr2613pkqp1d1-python3.13-azure-mgmt-netapp-13.7.0]]
- [[9qjacc23js20bmkczs0l7j41pcx3vxrz-python3.13-azure-mgmt-cognitiveservices-13.7.0]]
- [[9vr2sv97qhsgmg2l8c7mzpy6z5d92l4i-python3.13-azure-mgmt-recoveryservicesbackup-9.2.0]]
- [[9xnqlzraglxb85gqw970j0m4vxk1cm1m-python3.13-azure-mgmt-eventhub-11.2.0]]
- [[a8b3nw86ga3zg1pdr5pmrbv15p687vxy-python3.13-cryptography-45.0.4]]
- [[acgixx4bfjaks8qammk6dn3rizlz0njg-python3.13-azure-mgmt-policyinsights-1.0.0]]
- [[aij3bxpfdp189pq4fx7p5cbqicnmmlcw-python3.13-pygments-2.19.2]]
- [[amaniqrr9wi1q9sw15saw0wpgivnr9y0-python3.13-cffi-1.17.1]]
- [[b0gsqrhslfk60jars9xdp9r3g3kqwc0k-python3.13-azure-mgmt-imagebuilder-1.4.0]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[b7jzfqaswv96y7xgmw2q3alsfgvrn36z-python3.13-azure-datalake-store-1.0.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[byyfblx3zqy0g71m5s70cjfjswcss0zw-python3.13-applicationinsights-0.11.10]]
- [[ciqn9cwwh1zf1vki5mva76nhfkrxarq9-python3.13-aiosignal-1.4.0]]
- [[cscs9fsh6kcm6a3mhf6vprkqjykpik7j-python3.13-azure-mgmt-resource-all-2.77.0]]
- [[cv9zjk6dmhybvxdx0k17z0gk7fc6q03b-python3.13-pycparser-2.22]]
- [[cy8nd2h006ikmvcy85kzgfx6vw8234hp-python3.13-azure-mgmt-extendedlocation-2.0.0]]
- [[d87dlg2cqni982s53gcp2qwz05085svl-python3.13-pycomposefile-0.0.34]]
- [[d8drnbjil3rb3vcdj7kicszsj3qslb9b-python3.13-azure-mgmt-hdinsight-9.0.0b3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[dgvjv83pa1r6j8vxncnhrv34fqmmzns9-python3.13-azure-mgmt-redhatopenshift-1.5.0]]
- [[dlajm18ifvf2c3a2015z2vzhy9hi2xvb-python3.13-azure-mgmt-marketplaceordering-1.1.0]]
- [[f45q2aymvhnk8l4r64y3wydp0bmibi43-python3.13-azure-mgmt-common-0.20.0]]
- [[f77f790bd1ibkmw71scmlxxfjyzxkvk3-python3.13-azure-monitor-query-2.0.0]]
- [[f96b3al2fq8pz5y45r7d8dya0v9rfrd7-python3.13-decorator-5.2.1]]
- [[fc7cb1kby30xx51vkpmq6if41n6hgk3n-python3.13-azure-mgmt-authorization-4.0.0]]
- [[fqg4b53s2m8cj6k6z74vd23kjr9swhb3-python3.13-azure-mgmt-iothubprovisioningservices-1.1.0]]
- [[fr6nd9gd7g4c9kirg69ii7i9iagh4gx4-python3.13-humanfriendly-10.0]]
- [[g0dvfs27h26vghh5id5s0rfc2fascyxb-python3.13-isodate-0.7.2]]
- [[g1rh1agrz3fk3hrqgrna3yhr86x4bpi2-python3.13-tabulate-0.9.0]]
- [[g2gfb4pbmx3v634zkqhvjr8kxwl5l04q-python3.13-azure-mgmt-datalake-store-1.0.0]]
- [[g78hnqba0l2cnkw6ka9bfkpknf9j4619-python3.13-azure-mgmt-trafficmanager-1.1.0]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[gbw5bcdp8pkdmyimqvhcc3k1i11si898-python3.13-azure-mgmt-storage-23.0.1]]
- [[gigxba91wk19lwag4b9412lsbaqjxzpx-python3.13-azure-mgmt-datalake-nspkg-3.0.1]]
- [[grm9hakjmy44p60klbw7lkbwj8xcmpmk-python3.13-azure-keyvault-administration-4.6.0]]
- [[gw18fiibdnn237gp7f88xh4nx5db9yj4-python3.13-psutil-7.0.0]]
- [[gw9msiijkswnv7bv8rj1x8dgcpa60lby-python3.13-multidict-6.6.4]]
- [[h4k3g3z6q6lwcc6xvr4rsg2m2n4w4icz-python3.13-bcrypt-4.3.0]]
- [[hhyb6699r2r5kc1kfca2x09bbgmdpha9-python3.13-azure-mgmt-redis-14.5.0]]
- [[hii8615lsc12b3nfmgbbmc11m66s9wv0-python3.13-azure-mgmt-compute-35.0.0]]
- [[hrsgnaag0ax9kwcx9p1a85ja94r832m5-python3.13-azure-mgmt-monitor-7.0.0b1]]
- [[hy83w8wkamyz00ljqi55qvlb8vmqv21r-python3.13-azure-mgmt-apimanagement-5.0.0]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[id0l5i47i6vrwbzv4s7rj9hx54zrv5ma-python3.13-aiodns-3.5.0]]
- [[ilj979y12px6z0qga4ir7rbzwd8vnslg-python3.13-azure-mgmt-servicelinker-1.1.0]]
- [[in4ha179zpcjaxzz72lij0z3hq9nilgd-python3.13-azure-mgmt-cosmosdb-9.8.0]]
- [[ivnmdsi13nngmww0lmpnnlxpbvi8b8kk-python3.13-msal-extensions-1.3.1]]
- [[iwz9gc9zlscjq5vrw5czzkh1cwgappm7-python3.13-xmltodict-0.14.2]]
- [[ixvnimbb1wjjqv4bw4dn70zg5xh31rcb-python3.13-pkginfo-1.12.1.2]]
- [[j2wbhhdkqqm80cdrls2kp22kccmfh0z0-python3.13-azure-mgmt-synapse-2.1.0b5]]
- [[j4i608y8gx96b0jrrf2k8j5wbncvl2pb-python3.13-certifi-2025.07.14]]
- [[j83m3z318x8sf8hjy9cigvi6y7k154ab-python3.13-azure-mgmt-loganalytics-12.0.0]]
- [[jd8zba96a1aw2wsyvaf771590fk8q97h-python3.13-azure-mgmt-advisor-9.0.0]]
- [[jjlcxa2kqqg6vv4qi9fq1j8cqx64s4xs-python3.13-yarl-1.21.1]]
- [[jk19paaddh25cx3yngj44hi3cn8rbl8n-python3.13-aiohappyeyeballs-2.6.1]]
- [[jqq5x28kddwnjdq3wagwha8nda5ciqhk-python3.13-six-1.17.0]]
- [[jzljc4434kpi8qyxnzwv1rmi769jrl45-azure-cli-2.77.0-src]]
- [[k46174hnqd2229ydg5mqvn0nd971z09d-python3.13-azure-cli-telemetry-1.1.0]]
- [[k5b8flmpd8f02cd9qrr585jdapa6rv1q-python3.13-azure-synapse-managedprivateendpoints-0.4.0]]
- [[k5ijkfj6kz3f05xdn8cfl1406zfrswii-python3.13-scp-0.15.0]]
- [[kkxz2n5xywp90i5dj2pc9sy0l7c9y3q3-python3.13-portalocker-3.2.0]]
- [[l2yxgp6n1xmbbbsyq5z71377gq0l1s5g-python3.13-fabric-3.2.2]]
- [[l4g9rsqqmw750arzw5vjyw008lj7zvvd-python3.13-chardet-5.2.0]]
- [[l85w1ppr4yg887djh09jx8f7j1fw912f-python3.13-azure-mgmt-botservice-2.0.0]]
- [[lampjf0kwkaz3zl91gc0xwm103x0ml4f-python3.13-azure-mgmt-msi-7.0.0]]
- [[mlbqiqx3pjk9xz4r9whk4li9pdi07br6-python3.13-azure-mgmt-signalr-2.0.0b2]]
- [[mm1n0b9sw1y8iwr0k8q54pakirq2sqa4-python3.13-azure-mgmt-rdbms-10.2.0b17]]
- [[mmhbipk8dv8s8hl1rd7ps94pdrq15jj8-python3.13-azure-mgmt-billing-6.0.0]]
- [[mp3hh1a0c4hljcpbfzbyg1ch11gg6dw2-python3.13-oauthlib-3.3.1]]
- [[mq7arbh2d7lh8yqmdz8kbbcswvg6k7kz-python3.13-azure-mgmt-nspkg-3.0.2]]
- [[mr571ivbxc2m3rdjwh1l5ivvyc7k7gpf-python3.13-azure-mgmt-servicebus-8.2.0]]
- [[n3l1hhf4194qxjabqcavix6wgqai8xhl-python3.13-azure-synapse-accesscontrol-0.7.0]]
- [[n72jwcb204vfqh3lsvk32bkwd9p7ny2j-python3.13-azure-common-1.1.28]]
- [[n8f29lrai9rlvyv1vj53a1gl4ffaqq0b-python3.13-azure-keyvault-secrets-4.10.0]]
- [[n9idavb7slps8c6gn72km602adzj340x-python3.13-websocket-client-1.8.0]]
- [[nhyy1x1b7ip7lfbfjrw51ar1da2a9fn1-python3.13-idna-3.10]]
- [[nmy2q4zs1nnh2qlxb2nghy041k3vvyjy-python3.13-typing-extensions-4.14.1]]
- [[p1d791mgrryf0ya1pqx9x6bvsa0q83j8-python3.13-pycares-4.9.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[p9ji9yhrh5l60vrkii74vlsln5i93gfj-python3.13-brotli-1.1.0]]
- [[pwc3qiryy22aqlawc40c0bc06325hwh1-python3.13-azure-keyvault-keys-4.11.0]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[q4369fbczfzmbfbk2sg211izyw1rpr5x-python3.13-azure-mgmt-core-1.6.0]]
- [[qfic53kbch2jqpl9i31yf9a35i340f2b-python3.13-python-dateutil-2.9.0.post0]]
- [[qh6hqrdnnna45xm46zbnckdsqpjwr587-python3.13-azure-multiapi-storage-1.5.0]]
- [[qjmw97xwsgfiy86sk176q4jjrh4aiv2k-python3.13-azure-mgmt-postgresqlflexibleservers-1.1.0]]
- [[qwlpx27l2018lbbm02bhcczpbckpp5x2-python3.13-azure-mgmt-containerinstance-10.2.0b1]]
- [[qznzfkf5qiqnwh3rgjfycs05mgpfz906-python3.13-charset-normalizer-3.4.3]]
- [[r9z35f5s39py9msnmxxzz6mwgnc9mrky-python3.13-jsondiff-2.2.1]]
- [[rb3sbcck4yr7hfqqxig40zds9a87n7pc-python3.13-azure-mgmt-containerservice-39.1.0]]
- [[rk90alywyq65nz9kfs8daj52y946qi69-python3.13-colorama-0.4.6]]
- [[rryvxd82bqz6bbi3vkp3k38ywa2pd247-python3.13-azure-mgmt-privatedns-1.2.0]]
- [[rs3h8g5y8rznyb4k64hgvzvp3jgsr5b8-python3.13-requests-2.32.4]]
- [[s8wr0z2vr6x35c1zv2243j1frgcqvfy8-python3.13-msrest-0.7.1]]
- [[v01yjng5bg93rwwnxcxp9q9zghfv8ghf-python3.13-pygithub-2.8.1]]
- [[v2vy5hznlsfsssq8brlkxkj2y71wnha6-python3.13-azure-mgmt-batch-18.0.0]]
- [[v57l6knxkp4kvj3ny9dkxi9vp1ppxza4-python3.13-jmespath-1.0.1]]
- [[vcmb3h3nnv3rzx470xyaxxscsinh9mgb-python3.13-pynacl-1.5.0]]
- [[vdsvnscqhjwxas9g504x1px8k853pcyx-python3.13-azure-mgmt-web-9.0.0]]
- [[vh41aklhjry4ym77kvjz0kl0vjxd8miq-python3.13-azure-mgmt-servicefabricmanagedclusters-2.0.0]]
- [[vlllcjxim8k9346xiccp5m5wapiw6gq7-python3.13-azure-cli-core-2.77.0]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[vvb1qv6sb5g888yhmq43nywirnnkz72s-python3.13-redis-6.2.0]]
- [[vzags5vr9anbqr93lcq7xc5dxz22499x-python3.13-deprecated-1.2.18]]
- [[w5qalgw98bl1flxpi2rpjdach16blwll-python3.13-requests-oauthlib-2.0.0]]
- [[wg5y3m50pr5mjw7r51dlayap4rq4zlqx-python3.13-packaging-25.0]]
- [[wiymq0rb9pki1dcp8nvwj0gqd8x9ppw7-setuptools-build-hook]]
- [[wsyzp3yid1zpl973srg464y287mcncag-python3.13-azure-mgmt-appconfiguration-5.0.0]]
- [[x1vz30r1s9j5k39f7i9qnbh4s6vh170m-python3.13-azure-data-tables-12.7.0]]
- [[xjd7dfp43n1x3652knl2hdwljqf5yw8l-python3.13-javaproperties-0.8.2]]
- [[xm77jjmvhas5c5rpb00jjb03jyli7z03-python3.13-azure-mgmt-datamigration-10.0.0]]
- [[xqhidb331dc4acy47znw1748qgxss73m-python3.13-azure-mgmt-eventgrid-10.2.0b2]]
- [[xqp21qgvl8mh3vwsk6zh2zzzyiv0qvas-python3.13-azure-appconfiguration-1.7.1]]
- [[xyvrrp17y9dp564f6d7sf77ysk3rgpf2-python3.13-azure-keyvault-securitydomain-1.0.0b1]]
- [[ydg0yy0vs2jh74883hyr34iyf8s7js4w-python3.13-azure-cosmos-4.9.0]]
- [[yp26qdz7dpxrvik5gka93bmfmnmi7fd9-python3.13-azure-synapse-artifacts-0.21.0]]
- [[yx8zcwyvs5s8h8y94shk5sg13zhv49lg-python3.13-azure-batch-15.0.0b1]]
- [[yx9ag0icz7v1fbkq3an2658q40b7cgd2-python3.13-pyyaml-6.0.2]]
- [[z695ql5xcnip86m164248xr6vkgf9vga-install-shell-files]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]
- [[z9cgy1dn9lmmf90ac39x5z46wi7vlnrr-python3.13-async-timeout-5.0.1]]
- [[zcnmzniaww8bk1rlpzcx12h9ml59hb22-python3.13-distro-1.9.0]]
- [[zrk548zjy23g2ymw1hbh90r6np5gijf6-python3.13-azure-mgmt-cdn-12.0.0]]
- [[zrqvvjmb0q4rjbl3vpgqwxfflhn0zvvi-python3.13-pysocks-1.7.1]]
- [[zwb5ifwshq3y1bxmkx0rjm5p7l1pvgjh-python3.13-propcache-0.3.2]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:45:46 UTC*
