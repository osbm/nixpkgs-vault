---
aliases:
  - gnomeExtensions.dynamic-panel
tags:
  - license/unknown
  - maintainers/honnip
  - outputs/out
---

# gnomeExtensions.dynamic-panel

## 📝 Description

Dynamic Top Panel
Originally inspired by the floating panel design in KDE Plasma 6, it presents a translucent floating bar effect when there are no windows nearby, and a solid panel style when windows are close. It supports Gnome's dark and light mode switching. You can set custom colors for dark and light modes respectively. And there are more settings!

Floating Mode
When there are no windows near the top panel, it will be in floating mode.Floating mode has a translucent effect and a built-in simple blur effect. if you want a more advanced and more controllable blur effect, it is recommended to use Blur my shell's static pipeline for the panel. Blur my shell's dynamic mode will not have rounded corners, which is a problem with Blur my shell.

Solid Mode
When any window is close enough (almost touching) to the top panel, the top panel will become an opaque dock (same as the default in Gnome, but you can apply custom colors to it), which can better blend with maximized windows, unlike themes that are always floating and have a "light leakage" phenomenon.

Special Thanks (in no particular order)
Thanks to Gonzague/Paul Fauchon's Transparent Top Bar (Adjustable transparency) for the idea, the implementation of window proximity detection largely refers to this extension
Thanks to Google Gemini for the help provided in the research and learning of Gjs

Known Issue
GNOME panel experiences brief flickering during workspace transitions or when returning from the overview. This is caused by GNOME forcibly resetting panel styles during these actions. As this is an underlying GNOME behavior, there is currently no external fix available. Therefore, this flickering issue is listed as a known and temporarily unresolvable problem.

👇  See what's new!  Update logs are available on GitHub Releases 👇

動態頂部面板
最初靈感來源於 KDE Plasma 6 的懸浮面板的設計，在附近沒有視窗時呈現半透明懸浮條效果，而當視窗靠近時則呈現實色面板的樣式。支援 Gnome 的暗色模式和亮色模式切換。可針對暗色和亮色模式分別設定自訂顏色。還有更多設定！

懸浮模式
當頂部面板附近沒有視窗時，會呈現懸浮模式。懸浮模式有半透明效果，內建簡易模糊效果，如果想要更高級和細緻的模糊效果，建議搭配 Blur my shell 對於面板的靜態 pipeline 使用。Blur my shell 動態模式會沒有圓角，這是 Blur my shell 的問題。

實體模式
當有任何視窗足夠靠近（幾乎接觸）頂部面板時，頂部面板將會變為不透明的停靠欄（和 Gnome 默認的一樣，但你可以對其應用自訂顏色），與最大化視窗可以更好的融合，而不像主題一樣始終懸浮會有「漏光」的現象。

特別鳴謝（排名不分先後）
感謝 Gonzague/Paul Fauchon 的 Transparent Top Bar (Adjustable transparency) 的思路，對視窗靠近的判定實現思路大量參考了此擴充功能
感謝 Google Gemini 在研究和學習 Gjs 過程中提供的幫助

已知問題
GNOME面板在工作區切換或從概觀視圖返回時，會短暫閃爍。這是由於GNOME在這些操作中強制重置面板樣式所致。由於這是GNOME的底層行為，目前無法透過外部方式解決，因此此閃爍問題被列為已知且暫無法修復的問題。

👇更新日誌請到GitHub的Releases查看👇

## 📋 Package Information

- **Name**: `gnomeExtensions.dynamic-panel`
- **Version**: `40`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Dynamic Top Panel
- **Homepage**: [https://extensions.gnome.org/extension/7284/dynamic-panel/](https://extensions.gnome.org/extension/7284/dynamic-panel/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`
## 👥 Maintainers

- @honnip


## 🔧 Build Information

- **Derivation Path**: `/nix/store/701g1fxlgs6x9wqzrbpwk7jkblxfhx81-gnome-shell-extension-dynamic-panel-40.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/desktops/gnome/extensions/buildGnomeExtension.nix:61`
- **Outputs**:
  - `out`:  `/nix/store/701g1fxlgs6x9wqzrbpwk7jkblxfhx81-gnome-shell-extension-dynamic-panel-40`

## 🔗 Dependencies

- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[mjg574y35jj387b6f4mkax22lkl5pyvz-source]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:14:39 UTC*
