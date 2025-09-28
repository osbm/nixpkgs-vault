---
aliases:
  - epsonscan2
tags:
  - license/unknown
  - maintainers/james-atkins
  - outputs/out
---

# epsonscan2

## 📝 Description

The Epson Scan 2 scanner driver, including optional non-free plugins such
as OCR and network scanning.

To use the SANE backend:
```nix
{
  hardware.sane.extraBackends = [ pkgs.epsonscan2 ];
}
```

Overrides can be used to customise this package. For example, to enable
non-free plugins and disable the Epson GUI:
```nix
pkgs.epsonscan2.override {
  withNonFreePlugins = true;
  withGui = false;
}
```


## 📋 Package Information

- **Name**: `epsonscan2`
- **Version**: `6.7.70.0-01-2025`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Epson Scan 2 scanner driver for many modern Epson scanners and multifunction printers
- **Homepage**: [https://support.epson.net/linux/en/epsonscan2.php](https://support.epson.net/linux/en/epsonscan2.php)
- **License**: `unknown`
## 👥 Maintainers

- @james-atkins


## 🔧 Build Information

- **Derivation Path**: `/nix/store/67pi95rgxkrf5dh4pdfylj7pw82dvwwh-epsonscan2-6.7.70.0-01-2025.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ep/epsonscan2/package.nix:151`
- **Outputs**:
  - `out`:  `/nix/store/67pi95rgxkrf5dh4pdfylj7pw82dvwwh-epsonscan2-6.7.70.0-01-2025`

## 🔗 Dependencies

- [[0dyaxjhz2kj25fissh5yj32khwz8crrz-qtbase-5.15.17]]
- [[0nvk6aw3bvbfj52s86ac0jj6gz38vq86-epsonscan2.desktop]]
- [[1l1lk431imzsf7jhqxqkf5kcj4p4da8p-libtiff-4.7.0]]
- [[2sgql247rkyqmnad6gl3pwmq6gsy13wz-libjpeg-turbo-3.1.1]]
- [[4l7f6gmx2x3nl78lmcdbk7h6mdiv76zn-killall-psmisc-23.7]]
- [[6naj1xz5nqf240hf9lfv6a8vdgddd0xq-0002-Fix-crash.patch]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[fq23lcwc1p6ww77gxriaa7n57wva6mag-copy-desktop-items-hook]]
- [[fy9wjrqf0pzd5x3rvy665v50ff747wfd-libusb-1.0.29]]
- [[gq1x7r7fl6r3w50rrwba6y26xg1nqw70-imagemagick-7.1.2-3]]
- [[mzg1vkyzabv01ja719b3zj9hzwkzhyk2-libpng-apng-1.6.49]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[qn9argmfkx5j3gzmkzsp6zmiyxp93arc-boost-1.86.0]]
- [[r2db2qh3wxwmqd0615pzcixjcirgvj12-wrap-qt5-apps-hook]]
- [[shg1p5n6k4812rsa0va12n82dgx9dpfs-0003-Use-XDG-open-to-open-the-directory.patch]]
- [[x934vggr8b9f4fwr17wmwf3j4mz5aqaa-source]]
- [[yvf1q8rdxqwwrkjfhngpb9ljrs8jkkkr-0004-Fix-a-crash-on-an-OOB-container-access.patch]]

## 📁 Input Sources

- `/nix/store/4js7vns38g561zn4i7v2v0fkk9p7hjfh-gcc14.patch`
- `/nix/store/jzd2w2cwsb65jzyfzqndrm1vpj27sylw-build.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:52:56 UTC*
