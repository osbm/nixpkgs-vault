---
aliases:
  - wordlists
tags:
  - license/unknown
  - maintainers/Pamplemousse
  - maintainers/h7x4
  - outputs/out
---

# wordlists

## 📝 Description

The `wordlists` package provides two scripts. One is called {command}`wordlists`,
and it will list a tree of all the wordlists installed. The other one is
called {command}`wordlists_path` which will print the path to the nix store
location of the lists. You can for example do
{command}`$(wordlists_path)/rockyou.txt` to get the location of the
[rockyou](https://en.wikipedia.org/wiki/RockYou#Data_breach)
wordlist. If you want to modify the available wordlists you can override
the `lists` attribute`. In your nixos configuration this would look
similiar to this:

```nix
environment.systemPackages = [
  (pkgs.wordlists.override { lists = with pkgs; [ rockyou ] })
]
```

you can use this with nix-shell by doing:
{command}`nix-shell -p 'wordlists.override { lists = with (import <nixpkgs> {}); [ nmap ]; }'
If you want to add a new package that provides wordlist/s the convention
is to copy it to {file}`$out/share/wordlists/myNewWordlist`.


## 📋 Package Information

- **Name**: `wordlists`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Collection of wordlists useful for security testing
- **License**: `unknown`
## 👥 Maintainers

- @Pamplemousse
- @h7x4


## 🔧 Build Information

- **Derivation Path**: `/nix/store/af20nswkj256fgnzsx4aldads32vsd1n-wordlists.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/wo/wordlists/package.nix:50`
- **Outputs**:
  - `out`:  `/nix/store/af20nswkj256fgnzsx4aldads32vsd1n-wordlists`

## 🔗 Dependencies

- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[b9qysiyn18b45qigmnis627i6hxqx2rj-wordlists]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[bnbwi3a3fibvl518mmdcm41bc5ba71f1-lndir-1.0.5]]
- [[lx4n9klvindd5sniax6lnhs45cyns4p7-wordlists_path]]
- [[ma9vk50jqbj82sygyndjgj7m2zwd88hx-wordlists-collection]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 13:15:22 UTC*
