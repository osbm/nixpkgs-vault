---
aliases:
  - gatk
tags:
  - license/unknown
  - maintainers/apraga
  - outputs/out
---

# gatk

## 📝 Description

The GATK is the industry standard for identifying SNPs and indels in germline
DNA and RNAseq data. Its scope is now expanding to include somatic short variant
calling, and to tackle copy number (CNV) and structural variation (SV). In
addition to the variant callers themselves, the GATK also includes many
utilities to perform related tasks such as processing and quality control of
high-throughput sequencing data, and bundles the popular Picard toolkit.

These tools were primarily designed to process exomes and whole genomes
generated with Illumina sequencing technology, but they can be adapted to handle
a variety of other technologies and experimental designs. And although it was
originally developed for human genetics, the GATK has since evolved to handle
genome data from any organism, with any level of ploidy.


## 📋 Package Information

- **Name**: `gatk`
- **Version**: `4.6.2.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Wide variety of tools with a primary focus on variant discovery and genotyping
- **Homepage**: [https://gatk.broadinstitute.org/hc/en-us](https://gatk.broadinstitute.org/hc/en-us)
- **License**: `unknown`
## 👥 Maintainers

- @apraga


## 🔧 Build Information

- **Derivation Path**: `/nix/store/3jd25v1l7s1g7jyh48ckpvi887mra1yd-gatk-4.6.2.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ga/gatk/package.nix:35`
- **Outputs**:
  - `out`:  `/nix/store/3jd25v1l7s1g7jyh48ckpvi887mra1yd-gatk-4.6.2.0`

## 🔗 Dependencies

- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[3n815yx2isklf6lq4lilf9f0cgaskydr-source]]
- [[47vzy8p7cx5qiqqqncylhwwlm4hjvkf2-openjdk-21.0.8+9]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:55:05 UTC*
