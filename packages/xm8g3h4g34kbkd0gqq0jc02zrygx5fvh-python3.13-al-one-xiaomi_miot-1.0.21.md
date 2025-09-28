---
aliases:
  - home-assistant-custom-components.xiaomi_miot
tags:
  - license/unknown
  - maintainers/azuwis
  - outputs/out
---

# home-assistant-custom-components.xiaomi_miot

## 📝 Description

Xiaomi Miot For HomeAssistant depends on `ffmpeg` and `homekit`, example how to setup in NixOS `configuration.nix`:

```
{ config, lib, pkgs, ... }:
{
  services.home-assistant = {
    customComponents = [ pkgs.home-assistant-custom-components.xiaomi_miot ];
    extraComponents = [ "ffmpeg" "homekit" ];
  };
}
```


## 📋 Package Information

- **Name**: `home-assistant-custom-components.xiaomi_miot`
- **Version**: `1.0.21`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Automatic integrate all Xiaomi devices to HomeAssistant via miot-spec, support Wi-Fi, BLE, ZigBee devices
- **Homepage**: [https://github.com/al-one/hass-xiaomi-miot](https://github.com/al-one/hass-xiaomi-miot)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @azuwis


## 🔧 Build Information

- **Derivation Path**: `/nix/store/xm8g3h4g34kbkd0gqq0jc02zrygx5fvh-python3.13-al-one-xiaomi_miot-1.0.21.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/servers/home-assistant/custom-components/xiaomi_miot/package.nix:33`
- **Outputs**:
  - `out`:  `/nix/store/xm8g3h4g34kbkd0gqq0jc02zrygx5fvh-python3.13-al-one-xiaomi_miot-1.0.21`

## 🔗 Dependencies

- [[06a2j9jv7f40ihnra63q0xx99ry62h35-python-imports-check-hook.sh]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[5nnhidqdxck81ybxrn66wf6aplb679dk-python3.13-construct-2.10.70]]
- [[6kxaviwbgc66kjd9pdllbpyz4s72icnp-source]]
- [[7s7g039id3fdxw1f6dhnxg6qpqap64x8-wrap-python-hook]]
- [[88vyb2kgx9nypdqvc8jd5fbnsfh8m66s-python3.13-python-miio-0.5.12]]
- [[b2gcqyf6wr8k19l1h57cgybfm7plixkq-python-remove-bin-bytecode-hook]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[dadz4lh1m644qsy5fqhw6w0n23c0ccy1-python-namespaces-hook.sh]]
- [[g7k5bzddpyyhs490yw7x2j6wj63dlf24-python-catch-conflicts-hook]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[q0d4zbljfk7whd4fs6qbpal9krlvprm3-python3.13-micloud-0.6]]
- [[rrx7swmc9lrdy2npfm671p82yg2irra9-manifest-check-hook]]
- [[vm757gkx227mkr0maavvvba01mk1dyp1-python-remove-tests-dir-hook]]
- [[wg5y3m50pr5mjw7r51dlayap4rq4zlqx-python3.13-packaging-25.0]]
- [[z99vzf35iinh3dnh2g994wbcbjrv4siq-ensure-newer-sources-hook]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:05:39 UTC*
