---
aliases:
  - apg
tags:
  - license/unknown
  - outputs/out
---

# apg

## 📝 Description

 APG (Automated Password Generator) is the tool set for random
 password generation.

 Standalone version

   Generates some random words of required type and prints them
   to standard output.

 Network version

   APG server: When client's request is arrived generates some
   random words of predefined type and send them to client over
   the network (according to RFC0972).

   APG client: Sends the password generation request to the APG
   server, wait for generated Passwords arrival and then prints
   them to the standard output.

Advantages

  * Built-in ANSI X9.17 RNG (Random Number Generator) (CAST/SHA1)
  * Built-in password quality checking system (it has support for
    Bloom filter for faster access)
  * Two Password Generation Algorithms:
      1. Pronounceable Password Generation Algorithm (according to
         NIST FIPS 181)
      2. Random Character Password Generation Algorithm with 35
         configurable modes of operation
  * Configurable password length parameters
  * Configurable amount of generated passwords
  * Ability to initialize RNG with user string
  * Support for /dev/random
  * Ability to crypt() generated passwords and print them as
    additional output
  * Special parameters to use APG in script
  * Ability to log password generation requests for network version
  * Ability to control APG service access using tcpd
  * Ability to use password generation service from any type of box
    (Mac, WinXX, etc.) that connected to network
  * Ability to enforce remote users to use only allowed type of
    password generation


## 📋 Package Information

- **Name**: `apg`
- **Version**: `2015-01-29`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Tools for random password generation
- **Homepage**: [https://github.com/wilx/apg](https://github.com/wilx/apg)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/zcv3xqbar331lad9a5k3i4wvb0hisgcv-apg-unstable-2015-01-29.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ap/apg/package.nix:24`
- **Outputs**:
  - `out`:  `/nix/store/zcv3xqbar331lad9a5k3i4wvb0hisgcv-apg-unstable-2015-01-29`

## 🔗 Dependencies

- [[4r0306z3awpyxpmnif26dxxhq05rl5g3-source]]
- [[7d5p0ip9nd3aj3r1a2pmhsxxizqqnis8-openssl-3.5.1]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fdsiavmafjqslhcim9zz4xlnqpkzqjz8-autoreconf-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:50:15 UTC*
