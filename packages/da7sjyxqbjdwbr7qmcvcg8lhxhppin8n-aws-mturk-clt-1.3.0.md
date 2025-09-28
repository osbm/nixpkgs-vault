---
aliases:
  - aws_mturk_clt
tags:
  - not-available
  - license/unknown
  - outputs/out
---

# aws_mturk_clt

## 📝 Description

The Amazon Mechanical Turk is a crowdsourcing marketplace that
allows users (“requesters”) to submit tasks to be performed by
other humans (“workers”) for a small fee.  This package
contains command-line tools for submitting tasks, querying
results, and so on.

The command-line tools expect a file
<filename>mturk.properties<filename> in the current directory,
which should contain the following:

<screen>
access_key=[insert your access key here]
secret_key=[insert your secret key here]
service_url=http://mechanicalturk.amazonaws.com/?Service=AWSMechanicalTurkRequester
</screen>


## 📋 Package Information

- **Name**: `aws_mturk_clt`
- **Version**: `1.3.0`
- **Available**: ❌ No
- **Broken**: ✅ No
- **Description**: Command line tools for interacting with the Amazon Mechanical Turk
- **Homepage**: [https://requester.mturk.com/developer](https://requester.mturk.com/developer)
- **License**: `unknown`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/da7sjyxqbjdwbr7qmcvcg8lhxhppin8n-aws-mturk-clt-1.3.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/aw/aws_mturk_clt/package.nix:31`
- **Outputs**:
  - `out`:  `/nix/store/da7sjyxqbjdwbr7qmcvcg8lhxhppin8n-aws-mturk-clt-1.3.0`

## 🔗 Dependencies

- [[2zbgxn4cvsidk14ifh8vbdnm6v6cdalb-aws-mturk-clt-1.3.0.tar.gz]]
- [[47vzy8p7cx5qiqqqncylhwwlm4hjvkf2-openjdk-21.0.8+9]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:44:53 UTC*
