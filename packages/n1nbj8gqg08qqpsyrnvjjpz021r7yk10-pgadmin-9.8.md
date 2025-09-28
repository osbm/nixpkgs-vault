---
aliases:
  - pgadmin4-desktopmode
tags:
  - license/unknown
  - maintainers/gador
  - outputs/dist
  - outputs/out
---

# pgadmin4-desktopmode

## 📝 Description

pgAdmin 4 is designed to meet the needs of both novice and experienced Postgres users alike,
providing a powerful graphical interface that simplifies the creation, maintenance and use of database objects.
This version is build with SERVER_MODE set to False. It will require access to `~/.pgadmin/`. This version is suitable
for single-user deployment or where access to `/var/lib/pgadmin` cannot be granted or the NixOS module cannot be used (e.g. on MacOS).
This should NOT be used in combination with the NixOS module `pgadmin` as they will interfere.



## 📋 Package Information

- **Name**: `pgadmin4-desktopmode`
- **Version**: `9.8`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Administration and development platform for PostgreSQL. Desktop Mode
- **Homepage**: [https://www.pgadmin.org/](https://www.pgadmin.org/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @gador


## 🔧 Build Information

- **Derivation Path**: `/nix/store/n1nbj8gqg08qqpsyrnvjjpz021r7yk10-pgadmin-9.8.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/pg/pgadmin4/package.nix:249`
- **Outputs**:
  - `dist`:  `/nix/store/n1nbj8gqg08qqpsyrnvjjpz021r7yk10-pgadmin-9.8`
  - `out`:  `/nix/store/n1nbj8gqg08qqpsyrnvjjpz021r7yk10-pgadmin-9.8`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[0f2fss1anfc25v36l40s84nknpfn7bbv-python3.13-ldap3-2.9.1]]
- [[0ihzm6m1z1842bwzpm4g2957vxyr7d6m-postgresql-17.6]]
- [[0jvl8271k5gypcg3k6vjmcq79lrn1126-python3.13-selenium-4.29.0]]
- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[1y4h1d9mnbcrdpk9hl8wpnwavf725vz4-python3.13-flask-sqlalchemy-3.1.1]]
- [[22kmzhywg9aaipki1gvy3zhc3lvxsyfb-python3.13-flask-login-0.7.0dev0-2024-06-18]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2i16vhsnncslkql7j47bkmz6z4ln6xbp-python3.13-pip-25.0.1]]
- [[2mqg4y2qz8kyk9xy96z1b80h3km40nch-nodejs-22.19.0]]
- [[3mm599yfa1a30njkxigxa6jq8qp0q262-python3.13-wtforms-3.2.1]]
- [[3v99g5f4m702rada3c7vpbv77mbyjx8j-python3.13-itsdangerous-2.2.0]]
- [[461mcpgnqciaq46zi8nhcm9p75x1xc6q-python3.13-flask-socketio-5.5.1]]
- [[5i5hkdvhvnigm25j943sw217xka88la2-python3.13-simplejson-3.20.1]]
- [[7cajjjjyg4mw117fb7f5swhad04wqv3r-python3.13-botocore-1.40.4]]
- [[7m3s2g4vah11qdbf1qn6jq1kq21jg3ls-python3.13-sshtunnel-0.4.0]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[89mqqykzi1kw7jb056axh0k1ncrl0wmp-yarn-berry-config-hook]]
- [[8j701zs3bjrz027rz0bpp09dp1j8z9rd-python3.13-user-agents-2.2.0]]
- [[96p9l0mp0cy12s10705rpz96x6bgz371-python-output-dist-hook]]
- [[a8b3nw86ga3zg1pdr5pmrbv15p687vxy-python3.13-cryptography-45.0.4]]
- [[agfzfzkvpn3vcnf65wni6jvkdxpb1mwf-python3.13-flask-security-5.6.2]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bwhrp2f1yyk2y2aglwjbh2hf5azp6ylh-python3.13-wheel-0.46.1]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[dqvswdxrvkvfww3w17frydx0bay9mxlp-python3.13-azure-mgmt-rdbms-10.1.0]]
- [[f7r5jl9c3418cbq765y8li3qz5w9kak5-python3.13-flask-compress-1.17]]
- [[fwnjz1n8w7cii709kb06whq1ai7y9417-python3.13-flask-migrate-4.1.0]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[g90a2xbc4zlkl79mhs0r7nhx213h83wb-python3.13-pyotp-2.9.0]]
- [[gnyx1vmdriahy75gy73hypcfds24xq1p-python3.13-jsonformatter-0.3.4]]
- [[gw18fiibdnn237gp7f88xh4nx5db9yj4-python3.13-psutil-7.0.0]]
- [[h4k3g3z6q6lwcc6xvr4rsg2m2n4w4icz-python3.13-bcrypt-4.3.0]]
- [[hln4yf1n3ihs3nimqx2rahckj102s4y6-python3.13-flask-3.1.2]]
- [[hm3dmylqf011nz034bxbh1jwgxisb3z3-offline]]
- [[hs4d3805vhnfdvyjxv8gmb34y44issk1-python3.13-passlib-1.9.1.post0]]
- [[icpkagkixihm5cvn5mcffaqa2v1y26sy-python3.13-setuptools-80.9.0]]
- [[is3251lg4xj2jiif9l2ms72545f8yl0n-python3.13-cython-3.1.2]]
- [[ky629l5wqywcf8j030mln0nwfqgjp8zw-python3.13-dnspython-2.7.0]]
- [[lh5vikismiic2l2cm7f70mzyk58d9wbp-source]]
- [[lw0vqypj68vxxild98n713sl37n4wkpq-postgresql-test-hook]]
- [[mfcrq4npms5cwhq950b83iv6p7hgkm10-yarn-berry-4.9.4]]
- [[mq3h6ydq43gfp09nsx1srq1j7q9kpwab-python3.13-flask-paranoid-0.3.0]]
- [[mxniklnk1kcl8j655vnk3wcw1zd2hykj-python3.13-sphinx-8.2.3]]
- [[n32169by3pxfw3w085lad8mzw02i1z4i-python3.13-sqlparse-0.5.3]]
- [[nxscqqw1lfw1s8ca5k955hqdz5j3xjfw-python3.13-sphinxcontrib-youtube-1.4.1]]
- [[p2pmx3hg6613mbxj60klqbg8h92vsp30-python3.13-azure-identity-1.23.1]]
- [[p3c75yfmi4lchlfwx6vj1kdajhdl7a97-python3.13-libgravatar-1.0.4]]
- [[p5jkvfbs8qg70cjq6kzix40c191an7pj-python3.13-qrcode-8.2]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pfhrbq9pgza67d8vmvya8n4mw44wla99-python3.13-psycopg-3.2.9]]
- [[pgwhwnxanz454yv5p0l5bigmjrmp1zyd-python3.13-testscenarios-0.5.0]]
- [[pn4gflsb2q8chn9qi1qp0wmq5gi70b0a-python3.13-flask-babel-4.1.0]]
- [[q31amkdlw945gfmqcci8n00brh5liiz2-pypa-install-hook]]
- [[qa79ih4sia5gmsld69k5z650as2b8vgm-python3.13-keyring-25.6.0]]
- [[qfic53kbch2jqpl9i31yf9a35i340f2b-python3.13-python-dateutil-2.9.0.post0]]
- [[qqk3nvvv8fwasvmadrwld6m8ii7m1anz-python3.13-azure-mgmt-subscription-3.1.1]]
- [[r7504iv7hylva6czjw1gjh31kb85i3r1-python3.13-boto3-1.40.4]]
- [[r9kr0hwdyzkl1gz9k4i9mip1jgl2w4c3-python3.13-sqlalchemy-2.0.42]]
- [[rzv5nysf1ws8zd8j10a6mdmg0ka50bqa-python3.13-authlib-1.6.1]]
- [[s2sd08xi2x65l8qlgx6svwczmjihf61f-python3.13-google-auth-oauthlib-1.2.2]]
- [[sfhwf0vh7svvb50lji587qpsq70gbfld-python3.13-flask-mail-0.10.0]]
- [[sq6bw021nr1ffgp4flnh0ksd82sfncpm-python3.13-azure-mgmt-resource-24.0.0]]
- [[swwhxdnkhx8q81vm3m58k5kmlgsm4b51-python3.13-pillow-11.3.0]]
- [[szg3ba84qxmpakq0bg1zwrdfrd6dgaiz-python3.13-flask-wtf-1.2.2]]
- [[szi85czajx1pvs7wvwpiv1yp84gis04j-python3.13-typer-0.16.0]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[wiymq0rb9pki1dcp8nvwj0gqd8x9ppw7-setuptools-build-hook]]
- [[wsgi40dj0aq73c9c3n07a295nbcmlm3i-python3.13-rich-14.1.0]]
- [[wv9w26srsjwjxrffr2y24xhjfjjxyzi8-python3.13-eventlet-0.40.0]]
- [[wx7mlag0926gbdvhxvadk0glscmi5gzg-python3.13-pytz-2025.2]]
- [[wysya321wrvzhc2mawxxcxzip01x50n7-python3.13-gssapi-1.9.0]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]
- [[zcixg6zmkalnwifid34xcz9c4f5sqlyh-python3.13-google-api-python-client-2.177.0]]

## 📁 Input Sources

- `/nix/store/glr4dahnal72fm0ci3yb6s7dk1wpz635-check-system-config-dir.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`
- `/nix/store/vld02c77s9s76fgbnqn0mgdpwj08sr6k-missing-hashes.json`
- `/nix/store/ya7al0x1dva7gllyjvh9a83zlbcn96dc-expose-setup.py.patch`

---
*Generated on 2025-09-27 12:01:25 UTC*
