---
aliases:
  - auto-multiple-choice
tags:
  - license/unknown
  - maintainers/thblt
  - outputs/out
---

# auto-multiple-choice

## 📝 Description

Create, manage and mark multiple-choice questionnaires.
auto-multiple-choice features automated or manual formatting with
LaTeX, shuffling of questions and answers and automated marking using
Optical Mark Recognition.

Questionnaires can be created using either a very simple text syntax,
AMC-TXT, or LaTeX. In the latter case, your TeXLive installation must
be combined with this package.  This can be done in configuration.nix
as follows:

<screen>
…
environment.systemPackages = with pkgs; [
  auto-multiple-choice
  (texlive.combine {
    inherit (pkgs.texlive) scheme-full;
    inherit auto-multiple-choice;
  })
];
</screen>

For usage instructions, see documentation at the project's homepage.


## 📋 Package Information

- **Name**: `auto-multiple-choice`
- **Version**: `1.7.0`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Create and manage multiple choice questionnaires with automated marking
- **Homepage**: [https://www.auto-multiple-choice.net/](https://www.auto-multiple-choice.net/)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `aarch64-genode`, `i686-genode`, `x86_64-genode`, `x86_64-solaris`, `javascript-ghcjs`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `mmix-mmixware`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `aarch64_be-none`, `aarch64-none`, `arm-none`, `armv6l-none`, `avr-none`, `i686-none`, `microblaze-none`, `microblazeel-none`, `mips-none`, `mips64-none`, `msp430-none`, `or1k-none`, `m68k-none`, `powerpc-none`, `powerpcle-none`, `riscv32-none`, `riscv64-none`, `rx-none`, `s390-none`, `s390x-none`, `vc4-none`, `x86_64-none`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`, `wasm64-wasi`, `wasm32-wasi`, `aarch64-windows`, `x86_64-windows`, `i686-windows`
## 👥 Maintainers

- @thblt


## 🔧 Build Information

- **Derivation Path**: `/nix/store/x82w30xbkzhh4scj40ms675m514ccd0i-auto-multiple-choice-1.7.0.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/au/auto-multiple-choice/package.nix:149`
- **Outputs**:
  - `out`:  `/nix/store/x82w30xbkzhh4scj40ms675m514ccd0i-auto-multiple-choice-1.7.0`

## 🔗 Dependencies

- [[02l2mwk9x35ww8hq6m836yrcy0ma7js8-wayland-1.24.0]]
- [[19h9aidban2f7d930fsf9jiwiwf90s0s-perl5.40.0-libwww-perl-6.72]]
- [[1j90z3lj3fn4fahaishwg9blnrjw181g-zlib-1.3.1]]
- [[1jgyc8pm0h5lnk0imm0bs3fhshis2hr2-cups-2.4.12]]
- [[1l1lk431imzsf7jhqxqkf5kcj4p4da8p-libtiff-4.7.0]]
- [[1n65w45czpxk1x4zk08ihvi2af6pqv1y-perl5.40.0-XML-NamespaceSupport-1.12]]
- [[1nrxibs30119flwnrds4wbfkmmsrxqw1-perl5.40.0-File-Listing-6.16]]
- [[28phnmnqgzmkqlby0znahvp3bgx6d6vv-dbus-1.14.10]]
- [[2bbbf4kb612sdcxn5cwyx6b4ip23j0qw-fribidi-1.0.16]]
- [[2fbx94cnniix1a6h9b265icc5syn829m-libxfixes-6.0.1]]
- [[2jbjfm0s7c03a7mylffys7n228vs64rz-make-shell-wrapper-hook]]
- [[2sgql247rkyqmnad6gl3pwmq6gsy13wz-libjpeg-turbo-3.1.1]]
- [[2y894pl1hdnqpp11v6h8jhp65pka8zxf-dblatex-0.3.12]]
- [[3aflm58fw2kw8nkcnns7h4lgmrdf5hp8-xorgproto-2024.1]]
- [[3x5bmlv641xm5s1hk1nj4ffr0nk7vw2p-wayland-protocols-1.45]]
- [[3y6m1lpnqflf0nvpyqzcssrrlcn20dw7-perl5.40.0-Image-Magick-7.1.2-3]]
- [[474kivdzi525za8vzpgr0ils1k0qf8r3-wrap-gapps-hook]]
- [[4935gwwyzsca9ffwgcqmzwip86wqzzmn-perl5.40.0-Clone-Choose-0.010]]
- [[4bi6scsk9zihlvzwkvz7h7yg5r92c97j-perl5.40.0-Clone-0.46]]
- [[4dq8np7c2mimniwl3if93g7ncz1cjr4r-gtk+3-3.24.49]]
- [[4ggmmaz96iznkln4990pdfigsnsi5vl7-perl5.40.0-HTML-Tagset-3.20]]
- [[5fnl19ibazlhzcrmxg56s11v29rw1cqc-gmp-with-cxx-6.3.0]]
- [[5hlv8fwawr6lqhrh1kdh3p9rim3s2h6g-perl5.40.0-ExtUtils-Depends-0.8001]]
- [[5pk1c33sk3d4zpbn4s0ng1ja4xww1bl4-freetype-2.13.3]]
- [[5xp4rnzsrcihrxpzdfm19ax7bynlqz6m-graphicsmagick-1.3.45]]
- [[68fmrnk9c3n0myl3g4cwfqpww5s4iwb9-perl5.40.0-Glib-1.3294]]
- [[75a4kav1hsxmg1sja8sjsmh75scv6r4h-perl5.40.0-HTTP-Cookies-6.10]]
- [[761d6f8hhrvq2qrbqc6ygxr3x34img28-libglvnd-1.7.0]]
- [[7xxwyy45phx4y8i57f0s1ayxvqci0jvv-perl5.40.0-URI-5.21]]
- [[8fprw65xdpxhpfvbis3n521ds798vwxp-fontconfig-2.16.2]]
- [[a11zhx32xg78ffjgam489wrkd6k1fc87-libxrender-0.9.12]]
- [[b2p3arix3p89xavn4588ihs6jm703kzi-perl5.40.0-XML-Writer-0.900]]
- [[b7g7w8fpp6xqbq6z76rdyr1g5jww7f81-libffi-3.5.1]]
- [[bfrhypf8s25npqqk6h8hi5qyr3apb3vr-gdk-pixbuf-2.42.12]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[chl48bxv5z21jdd89hyf9q1m0ncgypl2-perl5.40.0-gettext-1.07]]
- [[d99f4z55b6p4hx1wfl4r6d6i0zi5bh7m-libxext-1.3.6]]
- [[dkssw3csslvbv7cb9mrmfccns92l65c5-pango-1.56.3]]
- [[dzbflnx51h460iv9b70crbgrnxia7m6w-graphite2-1.3.14]]
- [[fmcl48pl1yd2dj0i667whqy578xlns7z-at-spi2-core-2.56.2]]
- [[fn3qzknrq49vl0qvpd7gsjn6rya4wqqh-perl5.40.0-XML-Twig-3.52]]
- [[gifi4rwvhm4wj1a9slpl24d9d4g98sm8-perl5.40.0-Archive-Zip-1.68]]
- [[gjhm034m0k4bfbr1l7a0i3yn22masc9g-netpbm-11.11.1]]
- [[glca1gx472ps9qlivbdf7z5jdcdnsp9l-glib-2.84.4]]
- [[hh434ir0646mndg79pj3jnp5w8fkfn2x-perl5.40.0-ExtUtils-PkgConfig-1.16]]
- [[hldpdrxz067hmpbvd6jc00ssvf2y02z1-libsm-1.2.6]]
- [[i7j0fsnp96z0nz7bkwadffiwb1zym3zb-perl5.40.0-XML-SAX-1.02]]
- [[ii8nj1lzpdiydqxqslq7y3lbmwlzsxh3-hicolor-icon-theme-0.18]]
- [[ilky15hn83zp9cxkh8bq41ph6nn2j61n-brotli-1.1.0]]
- [[imwa73v5mnia95zg7pyx9v0y2vsy3yp7-libXft-2.3.9]]
- [[j7gxy3359pbnn9sgds98qfa8v84lxfrh-perl5.40.0-HTTP-Date-6.06]]
- [[jg44bq1nkj2jw4jksqlvpbip55z4d59r-perl5.40.0-WWW-RobotRules-6.02]]
- [[jqqc83j9v460xa1qlp77ky52gbqg5af8-gobject-introspection-wrapped-1.84.0]]
- [[k2lm2qkl0haj7vph5sa2r97my0ah0q1b-libxslt-1.1.43]]
- [[kcczlhw9ld19r7pbfcc2y7nx1y25yf5m-perl5.40.0-XML-Simple-2.25]]
- [[kgdq9f42qlk24s461xvbqi12gcl3krry-libxcb-1.17.0]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[lwl0b9gy8l7r0afvb5j9lzvr69vkqbal-perl5.40.0-HTML-Parser-3.81]]
- [[m0h8vm7wnxqmzy77yph902p607lx7np5-gettext-0.25.1]]
- [[mh835h1mhbqinppdi3ggz9f28b87f0vz-libnotify-0.8.6]]
- [[mnrmssnyxgcnv732zhrcxn0ygv0qdjkz-perl5.40.0-OpenOffice-OODoc-2.125]]
- [[mzg1vkyzabv01ja719b3zj9hzwkzhyk2-libpng-apng-1.6.49]]
- [[n28yagg9slmvc9apapvwszs914w4kdsf-poppler-glib-25.07.0]]
- [[n5lii7y4b1nk1xh65dg4lvw5d92y4j9m-perl5.40.0-TimeDate-2.33]]
- [[ncwfwpdzk937skayjxm8fivvfaw0f0fl-libXcomposite-0.4.6]]
- [[nimxv9jqla9w3ipfx3q544037a64g9hi-pixman-0.46.2]]
- [[nncd4f9vl1alqwmiff6a138ppbsgbp5l-libx11-1.8.12]]
- [[p07fwgas5yxbvqq562rmfwqd7adwcha4-gsettings-desktop-schemas-48.0]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[pasdgphxm21zciq62qw7bb0vwfdifmvn-glibc-iconv-2.40]]
- [[plv2p4vi2d0bzxjfzii8mqips3f8qc62-perl5.40.0-Hash-Merge-0.302]]
- [[pmqrfw6g8vn1jlyb184xxsazg3cmp84q-perl5.40.0-Net-HTTP-6.23]]
- [[pv2z7y59x6s50hyw7pc7cx3rmip6jyyz-perl5.40.0-XML-SAX-Base-1.09]]
- [[q42jp9n73ljhdxji0gmji3p9864y0cjv-perl5.40.0-XML-SAX-Expat-0.51]]
- [[q47lq4zkxkjhilb64lplfg9pv932n506-libxau-1.0.12]]
- [[qfl1wjxrcshqcbv5i0zhbs1bpay9ivck-perl5.40.0-HTTP-Negotiate-6.01]]
- [[qqmk5l3fq2k4wz8pk2jll640n8c9i508-libice-1.1.2]]
- [[qzl8kni5a4xh81ampjh16cj72gkw4j4b-expat-2.7.1]]
- [[riz7jd6hvqpxzxgyhj76ianh96sxhvz4-gnumake-4.4.1]]
- [[rvsgycjzldbgg1l9f6bxrdncx02va128-libxrandr-1.5.4]]
- [[s2yr49i6v0a50zz5y5qxyzzkdzc3y6hx-libXdamage-1.1.6]]
- [[sj9wrrdpg5k9hfgp76sk0w1j5a65b78p-perl5.40.0-Glib-Object-Introspection-0.051]]
- [[sk7hsnfadb0z6zry6j6afbbkhmag5k3s-perl5.40.0-HTTP-CookieJar-0.014]]
- [[v7fq90f3gm3bqaj7ynsdij4wm5g9ac81-perl5.40.0-Try-Tiny-0.31]]
- [[vbk5sg0cbm5p2dngrnqjs7d50d171qj8-perl5.40.0-IO-HTML-1.004]]
- [[vcj5qkzdn6nky17xscc6qmax9grgp1vk-perl5.40.0-LWP-MediaTypes-6.04]]
- [[vqd433c35v8x4k6dwzklcsmpixmrqsa4-perl5.40.0-Encode-Locale-1.05]]
- [[vv61c1za91aflfqswyc5aif6hh2mrngx-auto-multiple-choice_1.7.0_dist.tar.gz]]
- [[vw9ps5df26syym597i1m4dv4fpf3m7wg-librsvg-2.60.0]]
- [[vwhc7pjh7shcbgc2qgda5b0hrx9frq66-opencv-4.12.0]]
- [[vww2w4bppjkr8spz5gcq5hkr98pf85zs-cairo-1.18.4]]
- [[vzdkmlzkd3xkw3agi9navfhp1cmqb0gv-perl5.40.0-Cairo-GObject-1.005]]
- [[vzja73jxbrjp0c6hxzkkbizc1v48n0xn-libxcursor-1.2.3]]
- [[wpihbsfa3wmb9cfnl7fq8vk5413n5q0f-perl5.40.0-Text-CSV-2.03]]
- [[x0rky2706kqng5va42lsxc0rvipfh0s2-perl5.40.0-DBI-1.644]]
- [[x4qccy6spdg30hj7s76pdjymyv9a6s8d-perl5.40.0-DBD-SQLite-1.74]]
- [[xsh1xzh45dh4z7s7aj6vvm8b267p3n6v-libXi-1.8.2]]
- [[xzi8vwhqjkk3897fdmi6ib81iy93yw9y-harfbuzz-11.2.1]]
- [[y03p9qd9pi8hwdgbwx221akmm1ypp0bm-perl5.40.0-Cairo-1.109]]
- [[y4lfwlviqzkdrk9973a02vpl0fk4h1vy-bzip2-1.0.8]]
- [[y8dsx6104ilm8kbx9hhqwd7kzzwa1v7h-perl5.40.0-XML-Parser-2.46]]
- [[yj2w5ka3nhh7l3bwrqrxc7cnbhpahvr1-perl5.40.0-Gtk3-0.038]]
- [[z4f1zlj7r2571kc76gfm4ysi29082mcq-perl5.40.0-HTTP-Message-6.45]]
- [[z5mbb6mvbc8p89rfcwgx27xfmkzzrv4b-libXinerama-1.1.5]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:42:52 UTC*
