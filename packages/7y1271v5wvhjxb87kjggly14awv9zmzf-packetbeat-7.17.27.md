---
aliases:
  - packetbeat
tags:
  - license/unknown
  - maintainers/fadenb
  - maintainers/basvandijk
  - maintainers/dfithian
  - outputs/out
---

# packetbeat

## 📝 Description

Packetbeat is an open source network packet analyzer that ships the
data to Elasticsearch.

Think of it like a distributed real-time Wireshark with a lot more
analytics features. The Packetbeat shippers sniff the traffic between
your application processes, parse on the fly protocols like HTTP, MySQL,
PostgreSQL, Redis or Thrift and correlate the messages into transactions.


## 📋 Package Information

- **Name**: `packetbeat`
- **Version**: `7.17.27`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Network packet analyzer that ships data to Elasticsearch
- **Homepage**: [https://www.elastic.co/products/beats](https://www.elastic.co/products/beats)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @fadenb
- @basvandijk
- @dfithian


## 🔧 Build Information

- **Derivation Path**: `/nix/store/7y1271v5wvhjxb87kjggly14awv9zmzf-packetbeat-7.17.27.drv`
- **Outputs**:
  - `out`:  `/nix/store/7y1271v5wvhjxb87kjggly14awv9zmzf-packetbeat-7.17.27`

## 🔗 Dependencies

- [[7395sqanx3w55cy8k3y50f8i69ik8wci-libpcap-1.10.5]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]
- [[s8qv6vaw2f87vilj6pc7fiflxdg0rq25-packetbeat-7.17.27-go-modules]]
- [[w79gx9ddi8arwdc7q7pfp71zyyscg139-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:06:06 UTC*
