---
aliases:
  - lambda-lisp
tags:
  - license/unknown
  - maintainers/cafkafk
  - outputs/out
---

# lambda-lisp

## 📝 Description

LambdaLisp is a Lisp interpreter written as a closed untyped lambda calculus term.
It is written as a lambda calculus term LambdaLisp = λx. ... which takes a string
x as an input and returns a string as an output. The input x is the Lisp program
and the user's standard input, and the output is the standard output. Characters
are encoded into lambda term representations of natural numbers using the Church
encoding, and strings are encoded as a list of characters with lists expressed as
lambdas in the Mogensen-Scott encoding, so the entire computation process solely
consists of the beta-reduction of lambda terms, without introducing any
non-lambda-type object.


## 📋 Package Information

- **Name**: `lambda-lisp`
- **Version**: `2022-08-18`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Lisp interpreter written in untyped lambda calculus
- **Homepage**: [https://github.com/woodrush/lambdalisp](https://github.com/woodrush/lambdalisp)
- **License**: `unknown`
- **Platforms**: `x86_64-linux`
## 👥 Maintainers

- @cafkafk


## 🔧 Build Information

- **Derivation Path**: `/nix/store/yyxygi8qagwnfi96iyzhmkqhfnkpz9a2-lambda-lisp-blc-2022-08-18.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/la/lambda-lisp/package.nix:66`
- **Outputs**:
  - `out`:  `/nix/store/yyxygi8qagwnfi96iyzhmkqhfnkpz9a2-lambda-lisp-blc-2022-08-18`

## 🔗 Dependencies

- [[abp1w9g0k2476s5a120y5ya1n4v4xl81-Blc.S?v=2]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[gxp9dl9fl91b2k7zv5bcdsb9cf2yigpx-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[zvkm6hy9gbv8ip0ifljv9iyz6iaymbkq-flat.lds]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:12:23 UTC*
