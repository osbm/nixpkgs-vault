---
aliases:
  - nemo-seahorse
tags:
  - license/unknown
  - maintainers/bobby285271
  - maintainers/mkg20001
  - outputs/out
---

# nemo-seahorse

## 📝 Description

You can add the extension to nemo using the following configuration:
```nix
{
  environment.systemPackages = with pkgs; [
    (nemo-with-extensions.override {
      extensions = [ nemo-seahorse ];
    })
  ];

  services.dbus.packages = with pkgs; [
    libcryptui
  ];

  services.desktopManager.gnome.extraGSettingsOverridePackages = with pkgs; [
    nemo
    gcr
    libcryptui
    nemo-seahorse
  ];
}
```


## 📋 Package Information

- **Name**: `nemo-seahorse`
- **Version**: `6.4.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Nemo seahorse extension
- **Homepage**: [https://github.com/linuxmint/nemo-extensions/tree/master/nemo-seahorse](https://github.com/linuxmint/nemo-extensions/tree/master/nemo-seahorse)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @bobby285271
- @mkg20001


## 🔧 Build Information

- **Derivation Path**: `/nix/store/6r4ip5065hxnymc0hzfw9zn5vlay7wwy-nemo-seahorse-6.4.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ne/nemo-seahorse/package.nix:60`
- **Outputs**:
  - `out`:  `/nix/store/6r4ip5065hxnymc0hzfw9zn5vlay7wwy-nemo-seahorse-6.4.0`

## 🔗 Dependencies

- [[2qc1404yli6scnns5c56l6v3810nxr98-gpgme-1.24.3]]
- [[4dq8np7c2mimniwl3if93g7ncz1cjr4r-gtk+3-3.24.49]]
- [[6i2jic85krpll6jsyclwwsh617n61m3d-gnupg-2.4.8]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[g3rfsiz7x8mv478vn9frbqlj9wcvqavy-nemo-6.4.5]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[hcyf24kf52p5ib5q0zvl1nxvhh7q5kfd-dbus-glib-0.114]]
- [[i2xjnpbmvhvvw8vkww0cjidqazxhl83a-gcr-3.41.2]]
- [[i64fh03ivds4cnp6sfbpx8532sazidha-ninja-1.13.1]]
- [[ipxbzx536p60apc52x6xs874r8n8rf41-libcryptui-3.12.2]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[mh835h1mhbqinppdi3ggz9f28b87f0vz-libnotify-0.8.6]]
- [[n31fm2bp2ws1z4qamr3zidij4in8a362-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[vil1lgkgw08q1v97kr8c8sbsgix3ad3k-meson-1.9.0]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:17:00 UTC*
