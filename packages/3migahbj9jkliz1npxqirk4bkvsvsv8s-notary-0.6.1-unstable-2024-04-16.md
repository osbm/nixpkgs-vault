---
aliases:
  - notary
tags:
  - license/unknown
  - maintainers/vdemeester
  - outputs/out
---

# notary

## 📝 Description

The Notary project comprises a server and a client for running and
interacting with trusted collections. See the service architecture
documentation for more information.

Notary aims to make the internet more secure by making it easy for people
to publish and verify content. We often rely on TLS to secure our
communications with a web server which is inherently flawed, as any
compromise of the server enables malicious content to be substituted for
the legitimate content.

With Notary, publishers can sign their content offline using keys kept
highly secure. Once the publisher is ready to make the content available,
they can push their signed trusted collection to a Notary Server.

Consumers, having acquired the publisher's public key through a secure
channel, can then communicate with any notary server or (insecure) mirror,
relying only on the publisher's key to determine the validity and
integrity of the received content.


## 📋 Package Information

- **Name**: `notary`
- **Version**: `0.6.1-unstable-2024-04-16`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Project that allows anyone to have trust over arbitrary collections of data
- **Homepage**: [https://github.com/theupdateframework/notary](https://github.com/theupdateframework/notary)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @vdemeester


## 🔧 Build Information

- **Derivation Path**: `/nix/store/3migahbj9jkliz1npxqirk4bkvsvsv8s-notary-0.6.1-unstable-2024-04-16.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/no/notary/package.nix:31`
- **Outputs**:
  - `out`:  `/nix/store/3migahbj9jkliz1npxqirk4bkvsvsv8s-notary-0.6.1-unstable-2024-04-16`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pinnhq1cqf76zgvqviyzlrcv5vf8s71l-source]]
- [[pxn4bbdbwd25r02kvp7a1jp3fjykrb65-go-1.25.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:25:30 UTC*
