---
aliases:
  - git-credential-manager
tags:
  - license/unknown
  - maintainers/999eagle
  - outputs/out
---

# git-credential-manager

## 📝 Description

git-credential-manager is a secure, cross-platform Git credential storage with authentication to GitHub, Azure Repos, and other popular Git hosting services.

> requires sandbox to be disabled on MacOS, so that
.NET can find `/usr/bin/codesign` to sign the compiled binary.
This problem is common to all .NET packages on MacOS with Nix.


## 📋 Package Information

- **Name**: `git-credential-manager`
- **Version**: `2.6.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Secure, cross-platform Git credential storage with authentication to GitHub, Azure Repos, and other popular Git hosting services
- **Homepage**: [https://github.com/git-ecosystem/git-credential-manager](https://github.com/git-ecosystem/git-credential-manager)
- **License**: `unknown`
- **Platforms**: `x86_64-linux`, `aarch64-linux`, `x86_64-darwin`, `aarch64-darwin`
## 👥 Maintainers

- @999eagle


## 🔧 Build Information

- **Derivation Path**: `/nix/store/wdi2ipc1qknsj3ajkd7vk7kdy2i1v657-git-credential-manager-2.6.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/applications/version-management/git-credential-manager/default.nix:59`
- **Outputs**:
  - `out`:  `/nix/store/wdi2ipc1qknsj3ajkd7vk7kdy2i1v657-git-credential-manager-2.6.1`

## 🔗 Dependencies

- [[078p9lz6l2bird8m9x561brqxvia2jl8-Avalonia.X11-11.1.3]]
- [[0fpvaap3ndghlffw9l7h5icavnirs2wq-dotnet-sdk-wrapped-8.0.414]]
- [[0l6z31mdwzcvhqgjhxvbwlxwfn1zz0v4-Microsoft.NETCore.DotNetHost-8.0.20]]
- [[0w07zhqqs4ps002831snix9g7mhpy65h-Microsoft.NETCore.App.Host.linux-x64-8.0.20]]
- [[13g8khfdnxwdl97lyyg4121jgvv2ih2r-Avalonia.Desktop-11.1.3]]
- [[1cc4qsl7260aqgw6gy9flwbyp6d62jav-runtime.linux-x64.Microsoft.NETCore.DotNetHostPolicy-8.0.20]]
- [[1dizz5l2rmniamjys9b4zi8xj5vah3ay-Avalonia.Themes.Fluent-11.1.3]]
- [[1dmjbsmav6a178a67d8azmxbswqmrhgz-SkiaSharp-2.88.8]]
- [[1ssax255z03n6flk73rp52p491hfswbi-runtime.linux-x64.Microsoft.NETCore.DotNetAppHost-8.0.20]]
- [[24bd5q7q32914wnjxw2qq9pdpqasah75-Microsoft.NETCore.App.Crossgen2.linux-x64-8.0.20]]
- [[2cmq73q4ilk32hribz8c0mg9g6xkap6m-password-store-1.7.4]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[2rj2hriykm83rh49nyw4b2dc9xyzh80j-System.Security.Cryptography.ProtectedData-4.5.0]]
- [[2v2b1cd9anb0bgws3fnfl9pq6n1my99b-Microsoft.Identity.Client.Extensions.Msal-4.65.0]]
- [[327zqmnlysil38g888vca06mjm3j8zsj-Microsoft.IdentityModel.Abstractions-6.35.0]]
- [[43lbaa0wp1y19lnbpm7rglnjgcpj1358-HarfBuzzSharp.NativeAssets.WebAssembly-7.3.0.2]]
- [[55vpbjli0wv39qn7awvmgdyl4bws5kiv-System.Numerics.Vectors-4.5.0]]
- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[6i2jic85krpll6jsyclwwsh617n61m3d-gnupg-2.4.8]]
- [[6wc5jyx0q9z71njicmj6rl6b1lvcfl0d-System.Runtime.CompilerServices.Unsafe-6.0.0]]
- [[70yqhjvshwfh6bgc039hyp73cd7lvhbd-Microsoft.DotNet.ILCompiler-8.0.20]]
- [[70yw303zv6ccnfimmh823bijxz0bgnw9-runtime.linux-x64.Microsoft.DotNet.ILCompiler-8.0.20]]
- [[95cpajl7z00dfly0vbh16nkwiyxx5h78-dotnet-runtime-wrapped-8.0.20]]
- [[9kna75211ym9ix1g38p7alxdcl7rp38w-SkiaSharp.NativeAssets.WebAssembly-2.88.8]]
- [[9ly14w43lzhryadjwgxgbhm3f7w14w79-SkiaSharp.NativeAssets.Win32-2.88.8]]
- [[9n191b4c6gq98zlrjcj8gsp8dizmrzjs-Avalonia.Win32-11.1.3]]
- [[agnk4m5xfimkzhzvvq7fnz9wsfy6840n-Microsoft.AspNetCore.App.Ref-8.0.20]]
- [[amclw3820qz9j5aymsxv95ljn2lblx5q-Avalonia.FreeDesktop-11.1.3]]
- [[b3sh2p4k874npg1kv4axvf8y8yn16qwm-Microsoft.NETCore.DotNetHostPolicy-8.0.20]]
- [[b7mpfr535h13p9s9j26p2k1pm9pjbakf-nss-cacert-3.115]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[cb2w1l3qgypbp01fxgaj0615wn113v09-Avalonia.Angle.Windows.Natives-2.1.22045.20230930]]
- [[cdj1l5dwgv3361s5q42a4xpvccxgjj0j-Avalonia.Diagnostics-11.1.3]]
- [[ckwg712kj7bsv4b9v30pvclzriijbcnw-Avalonia.Controls.ColorPicker-11.1.3]]
- [[dqhc9f0svrjkvf0b5ryddri2zwk9qav3-HarfBuzzSharp.NativeAssets.Linux-7.3.0.2]]
- [[fs1hf03ig6n6misbrh1kx40mwwzcidyy-MicroCom.Runtime-0.11.0]]
- [[gpvfg0k5h69b4ccgh58nirvba773462x-HarfBuzzSharp-7.3.0.2]]
- [[h1w38l103n7id0w96j24ipivxxfylxrs-System.Diagnostics.DiagnosticSource-6.0.1]]
- [[hj1vlax27ja70ygvaabgqhghj2pqgprf-HarfBuzzSharp.NativeAssets.macOS-7.3.0.2]]
- [[hkib530yfaz8x7isab7l42m1b9bmc9xi-System.IO.Pipelines-6.0.0]]
- [[i3xx63h6aa9wy85apqs9gnc7j93v2a5b-Microsoft.NETCore.DotNetAppHost-8.0.20]]
- [[is4aysmdjs7512nzangg3m0c6fy14nih-Avalonia.Native-11.1.3]]
- [[ispmc5bzv6vgz0g9sfvvvwriv5hawh6z-libsecret-0.21.7]]
- [[jaln0wri2sd9fp78s4kz17sirmmrh04y-HarfBuzzSharp.NativeAssets.Win32-7.3.0.2]]
- [[jhdamhg85ivjyqrbra6zq7l71i4zc928-Microsoft.Identity.Client-4.65.0]]
- [[k57s2574a7r3sxyrmgs6jldz1hbrmsj8-SkiaSharp.NativeAssets.Linux-2.88.8]]
- [[khnnn9ixbib81bb1y76vdappz2x3lhmn-Avalonia.BuildServices-0.0.29]]
- [[kq2lp3dbbxayqb8yscb7d8sfgvdjg3vh-Avalonia-11.1.3]]
- [[li55swjwqqlfychzdik2li7gm1l9id2h-Tmds.DBus.Protocol-0.16.0]]
- [[m1isj3laxnwnwcbajdgsmn87qdsay3i0-Avalonia.Skia-11.1.3]]
- [[ns0jd9bkmzn7ylzjfd7fq2v57vr4z6xq-Avalonia.Remote.Protocol-11.1.3]]
- [[pi99g86jk3jh3fd1fm21z8b5492hdjdx-icu4c-76.1]]
- [[r57gf6rbl16515s3cqwhvf4qjfhfy12k-Microsoft.NETCore.DotNetHostResolver-8.0.20]]
- [[rans3ag23hly2f81730r012xh1b5gqbl-runtime.linux-x64.Microsoft.NETCore.DotNetHostResolver-8.0.20]]
- [[s4kvgv8gbkfwic955khq27sgwr82ds6p-SkiaSharp.NativeAssets.macOS-2.88.8]]
- [[sjsk0lprcrjbybbx5qrc49brqigf99r4-source]]
- [[v19fhdgcp8yhzp838vx9ji9w4iv7nlpf-Avalonia.Themes.Simple-11.1.3]]
- [[w8mzxakvm5rv8p9whf1r6vgkp9ifa5nr-Microsoft.NETCore.App.Runtime.linux-x64-8.0.20]]
- [[wl38fzhnmkhc9g9bdjnml0b0llvnq1mv-runtime.linux-x64.Microsoft.NETCore.DotNetHost-8.0.20]]
- [[wpnly1fiwh0jb8xaclimldxy1clm96x9-Microsoft.NET.ILLink.Tasks-8.0.20]]
- [[xyw5hd2mi8la2bw59kmb3mm0ix9xjx3z-Microsoft.NETCore.App.Ref-8.0.20]]
- [[y3bwpaxyl2268m36izzlx51b07afkjmh-dotnet-hook]]
- [[y97rd4di3ig9ibqan02pxhspldjp1x6y-System.CommandLine-2.0.0-beta4.22272.1]]
- [[yyw6nzfcdckb36blm5mf5b5mss1m9asq-git-2.51.0]]
- [[z6wvsh18zdpx0ml9j3n5qa1icjmf4vfy-Avalonia.Controls.DataGrid-11.1.3]]
- [[zb0d3y134lhfpd10a8h6prfgffyz0yb7-Microsoft.AspNetCore.App.Runtime.linux-x64-8.0.20]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:02:31 UTC*
