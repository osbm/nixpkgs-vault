---
aliases:
  - gromacsDoubleMpi
tags:
  - license/unknown
  - maintainers/sheepforce
  - maintainers/markuskowa
  - outputs/dev
  - outputs/man
  - outputs/out
---

# gromacsDoubleMpi

## 📝 Description

GROMACS is a versatile package to perform molecular dynamics,
i.e. simulate the Newtonian equations of motion for systems
with hundreds to millions of particles.

It is primarily designed for biochemical molecules like
proteins, lipids and nucleic acids that have a lot of
complicated bonded interactions, but since GROMACS is
extremely fast at calculating the nonbonded interactions (that
usually dominate simulations) many groups are also using it
for research on non-biological systems, e.g. polymers.

GROMACS supports all the usual algorithms you expect from a
modern molecular dynamics implementation, (check the online
reference or manual for details), but there are also quite a
few features that make it stand out from the competition.

See: https://www.gromacs.org/about.html for details.


## 📋 Package Information

- **Name**: `gromacsDoubleMpi`
- **Version**: `2025.3`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: Molecular dynamics software package
- **Homepage**: [https://www.gromacs.org](https://www.gromacs.org)
- **License**: `unknown`
- **Platforms**: `i686-cygwin`, `x86_64-cygwin`, `x86_64-darwin`, `aarch64-darwin`, `i686-freebsd`, `x86_64-freebsd`, `aarch64-freebsd`, `x86_64-solaris`, `aarch64-linux`, `armv5tel-linux`, `armv6l-linux`, `armv7a-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `m68k-linux`, `microblaze-linux`, `microblazeel-linux`, `mips-linux`, `mips64-linux`, `mips64el-linux`, `mipsel-linux`, `powerpc-linux`, `powerpc64-linux`, `powerpc64le-linux`, `riscv32-linux`, `riscv64-linux`, `s390-linux`, `s390x-linux`, `x86_64-linux`, `aarch64-netbsd`, `armv6l-netbsd`, `armv7a-netbsd`, `armv7l-netbsd`, `i686-netbsd`, `m68k-netbsd`, `mipsel-netbsd`, `powerpc-netbsd`, `riscv32-netbsd`, `riscv64-netbsd`, `x86_64-netbsd`, `i686-openbsd`, `x86_64-openbsd`, `x86_64-redox`
## 👥 Maintainers

- @sheepforce
- @markuskowa


## 🔧 Build Information

- **Derivation Path**: `/nix/store/21ih1zq9sg1dhcnd5xmsal5zz2jj4jhv-gromacs-2025.3.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/applications/science/molecular-dynamics/gromacs/default.nix:150`
- **Outputs**:
  - `dev`:  `/nix/store/21ih1zq9sg1dhcnd5xmsal5zz2jj4jhv-gromacs-2025.3`
  - `man`:  `/nix/store/21ih1zq9sg1dhcnd5xmsal5zz2jj4jhv-gromacs-2025.3`
  - `out`:  `/nix/store/21ih1zq9sg1dhcnd5xmsal5zz2jj4jhv-gromacs-2025.3`

## 🔗 Dependencies

- [[07kg314qv8il263lmadzl0bm7qjnm2fy-blas-3]]
- [[085xlrjn483h686si07j1k4s89hakmgz-fftw-double-3.3.10]]
- [[6cdbiry5rgbbn5hsm5di8nqijfqypi11-openmpi-5.0.8]]
- [[9j8w4bcicjkza42lizkrrx7sb6jw2qik-cmake-3.31.7]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[ih57yrmkwrj6pikq7kwb2pfkk2ji2mxd-hwloc-2.12.2]]
- [[lhw9cl3zbzmb2zj7fpi8dhxf930h9253-perl-5.40.0]]
- [[mzy2lpnkdfx1vq8gp5i4d9mbqvr3nz0l-gromacs-2025.3.tar.gz]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[wqcsrz1g6q6jqb5h2f33p94b330z5pvw-lapack-3]]

## 📁 Input Sources

- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/rn7pjbrr5jj3rg8jl42nna9k40iiqmv5-pkgconfig-2025.patch`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:57:54 UTC*
