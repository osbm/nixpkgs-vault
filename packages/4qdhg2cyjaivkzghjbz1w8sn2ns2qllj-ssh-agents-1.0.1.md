---
aliases:
  - ssh-agents
tags:
  - license/unknown
  - maintainers/kalbasit
  - outputs/out
---

# ssh-agents

## 📝 Description

The SSH agent is usually spawned by running eval $(ssh-agent), however this
spawns a new SSH agent at every invocation. This project provides an
ssh-agent wrapper called ssh-agents that is capable of spawning an SSH
agent and caching the environment variables for later invocation.

Features
- One SSH agent across all terminals
- Add all un-encrypted SSH keys to the agent upon spawning. Please note
  that encrypted SSH keys can only be added via ssh-add after having
  started the agent.
- Ability to have different keys in different agents for security purposes.
- Multiple SSH agents
- To use multi-SSH agents, start ssh agent with the --name flag. The
  given name is expected to be a folder under ~/.ssh/name containing the
  keys to include in the agent.


## 📋 Package Information

- **Name**: `ssh-agents`
- **Version**: `1.0.1`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Spawn and maintain multiple ssh-agents across terminals
- **Homepage**: [https://github.com/kalbasit/ssh-agents](https://github.com/kalbasit/ssh-agents)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @kalbasit


## 🔧 Build Information

- **Derivation Path**: `/nix/store/4qdhg2cyjaivkzghjbz1w8sn2ns2qllj-ssh-agents-1.0.1.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/by-name/ss/ssh-agents/package.nix:21`
- **Outputs**:
  - `out`:  `/nix/store/4qdhg2cyjaivkzghjbz1w8sn2ns2qllj-ssh-agents-1.0.1`

## 🔗 Dependencies

- [[6dg1vi55ynf4dmkmmcn945pwdz010s34-stdenv-linux]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[nxc32whngaimj0jbs9p258vizsl4q6ja-source]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 12:51:24 UTC*
