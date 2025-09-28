---
aliases:
  - decode-spam-headers
tags:
  - license/unknown
  - outputs/doc
  - outputs/out
---

# decode-spam-headers

## 📝 Description

Whether you are trying to understand why a specific e-mail ended up in
SPAM/Junk for your daily Administrative duties or for your Red-Team
Phishing simulation purposes, this script is there for you to help!

This tool accepts on input an *.EML or *.txt file with all the SMTP
headers. It will then extract a subset of interesting headers and using
105+ tests will attempt to decode them as much as possible.

This script also extracts all IPv4 addresses and domain names and performs
full DNS resolution of them.

Resulting output will contain useful information on why this e-mail might
have been blocked.


## 📋 Package Information

- **Name**: `decode-spam-headers`
- **Version**: `2022-09-22-unreleased`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Script that helps you understand why your E-Mail ended up in Spam
- **Homepage**: [https://github.com/mgeeky/decode-spam-headers/](https://github.com/mgeeky/decode-spam-headers/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `x86_64-darwin`, `aarch64-darwin`, `i686-cygwin`, `x86_64-cygwin`, `aarch64-windows`, `x86_64-windows`, `i686-windows`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/361qspiwkringpxgjjfj0gp9kvd9p5ab-decode-spam-headers-2022-09-22-unreleased.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/de/decode-spam-headers/package.nix:47`
- **Outputs**:
  - `doc`:  `/nix/store/361qspiwkringpxgjjfj0gp9kvd9p5ab-decode-spam-headers-2022-09-22-unreleased`
  - `out`:  `/nix/store/361qspiwkringpxgjjfj0gp9kvd9p5ab-decode-spam-headers-2022-09-22-unreleased`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bwfqjiv502l4s53ylsvkx124aqm1dii4-python3.13-tldextract-5.3.0]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[ky629l5wqywcf8j030mln0nwfqgjp8zw-python3.13-dnspython-2.7.0]]
- [[mrvh93zg11zgyqpmndapq212d8lpizkv-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qfic53kbch2jqpl9i31yf9a35i340f2b-python3.13-python-dateutil-2.9.0.post0]]
- [[rk90alywyq65nz9kfs8daj52y946qi69-python3.13-colorama-0.4.6]]
- [[rs3h8g5y8rznyb4k64hgvzvp3jgsr5b8-python3.13-requests-2.32.4]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[wg5y3m50pr5mjw7r51dlayap4rq4zlqx-python3.13-packaging-25.0]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:41:30 UTC*
