---
aliases:
  - grub2_efi
tags:
  - license/unknown
  - outputs/debug
  - outputs/out
---

# grub2_efi

## 📝 Description

GNU GRUB is a Multiboot boot loader. It was derived from GRUB, GRand
Unified Bootloader, which was originally designed and implemented by
Erich Stefan Boleyn.

Briefly, the boot loader is the first software program that runs when a
computer starts.  It is responsible for loading and transferring
control to the operating system kernel software (such as the Hurd or
the Linux).  The kernel, in turn, initializes the rest of the
operating system (e.g., GNU).


## 📋 Package Information

- **Name**: `grub2_efi`
- **Version**: `2.12`
- **Available**: ✅ Yes
- **Broken**: ✅ No
- **Description**: GNU GRUB, the Grand Unified Boot Loader
- **Homepage**: [https://www.gnu.org/software/grub/](https://www.gnu.org/software/grub/)
- **License**: `unknown`
- **Platforms**: `aarch64-linux`, `armv7l-linux`, `i686-linux`, `loongarch64-linux`, `riscv32-linux`, `riscv64-linux`, `x86_64-linux`

## 🔧 Build Information

- **Derivation Path**: `/nix/store/54h0d9dm7qqxbbcrv8ggk81ssi4zmja7-grub-2.12.drv`
- **Source Position**: `/nix/store/ns30sqxb36k8jrds8z18rv96bpnwc60d-source/pkgs/tools/misc/grub/default.nix:651`
- **Outputs**:
  - `debug`:  `/nix/store/54h0d9dm7qqxbbcrv8ggk81ssi4zmja7-grub-2.12`
  - `out`:  `/nix/store/54h0d9dm7qqxbbcrv8ggk81ssi4zmja7-grub-2.12`

## 🔗 Dependencies

- [[0id87llnnfsd1l3pp88hnxa40c63lirk-44_commands_test_stack_overflow_due_to_unlimited_recursion_depth.patch]]
- [[0v3ymch5lilz8zna65p40ba7sljlbzca-21_kern_file_ensure_file_data_is_set.patch]]
- [[0y20y5glzrd67xskzh9vjindzjl1jiiv-bison-3.8.2]]
- [[10zvn2kpfxq1f0qm39613pva7c9kkkyi-26_kern_partition_limit_recursion_in_part_iterate.patch]]
- [[1amrjc6x5gj69q1idvlvwbjkv0z5v2xf-51_disk_prevent_overflows_when_allocating_memory_for_arrays.patch]]
- [[1lsckm506km92v5qz9kazlqsn1hfkj48-03_CVE-2024-45782_CVE-2024-56737.patch]]
- [[1pigazmvkz8pm7jb7ck9x86g131gchzf-32_CVE-2024-45774.patch]]
- [[257k0vnqp1xjgyrpc5as1r0nl7s4yv71-python3-3.13.7]]
- [[2xxq98wwfvsxb3vp4a5vcnbxh213wpj3-46_commands_memrw_disable_memory_reading_in_lockdown_mode.patch]]
- [[2yszvka2i1d29ny08llg1sscyjjvp6yh-15_fs_ntfs_fix_out-of-bounds_read.patch]]
- [[2z8srdm63cgdqbkrzh3rx3gs2q5rxyq8-09_fs_iso9660_fix_invalid_free.patch]]
- [[3jd6v3c57zfs9531dqg08mhwv9j9qcxf-23_prerequisite_5_cryptodisk_wipe_out_the_cached_keys_from_protectors.patch]]
- [[3x9b536jpi37ckghfmn3wprwwzzcgvaw-ncurses-6.5]]
- [[4b1vdpfw834rxgpacv9yn62yfdadc089-25_kern_disk_limit_recursion_depth.patch]]
- [[4frm7i27ilzvdsn0c8dkfmlbswgzv9y9-28_net_unregister_net_default_ip_and_net_default_mac_variables_hooks_on_unload.patch]]
- [[4izdplx4avfjqx4bw93kmqk1g10fm6k4-52_disk_check_if_returned_pointer_for_allocated_memory_is_NULL.patch]]
- [[4lph6fb7qkzrq4c3k13qqfidl2h25s7c-04_fs_tar_initialize_name_in_grub_cpio_find_file.patch]]
- [[4lyfb9kbjwrj37jmi8j4q12mz5yqfy0b-12_fs_jfs_use_full_40_bits_offset_and_address_for_data_extent.patch]]
- [[4ww354nm4b7nn00k3n2nrn3vvn3rg255-fs_ext2_rework_out-of-bounds_read_for_inline_and_external_extents.patch]]
- [[53h9li59iw52mypkywdb13w683m356rb-73_loader_i386_bsd_use_safe_math_to_avoid_underflow.patch]]
- [[571bmnwfpqksyhmapwcilq0ba72gff1j-31_net_tftp_fix_stack_buffer_overflow_in_tftp_open.patch]]
- [[5dr4xann7g051a2r065cbg22rjaixmia-23_prerequisite_2_disk_cryptodisk_allow_user_to_retry_failed_passphrase.patch]]
- [[5hnya904hc9qcry3sypbnylc7gsf5j6q-07_CVE-2024-45783.patch]]
- [[5k9q9bkphkw35wz3b8p7rrjwq6kaxq9h-45_CVE-2025-1118.patch]]
- [[5pk1c33sk3d4zpbn4s0ng1ja4xww1bl4-freetype-2.13.3]]
- [[6sb10778xa7j1arn5k62a34cyp7dkj89-67_misc_ensure_consistent_overflow_error_messages.patch]]
- [[70cxv0psdwvs79higy5m188k96gh1swm-23_prerequisite_3_cryptodisk_support_key_protectors.patch]]
- [[7516ajzxxfwrpmi6j540na2cs90lnhs5-02_CVE-2024-45781.patch]]
- [[77q0d4kxyf2r7m0h3rlkvnprj388r5c5-29_net_remove_variables_hooks_when_interface_is_unregisted.patch]]
- [[7j8ccrapvdp2v8rxvzcdwgaxbn1iyn9x-63_net_check_if_returned_pointer_for_allocated_memory_is_NULL.patch]]
- [[7kszl9hcpf5zh5mg8prjlf10pdcixv0i-11_fs_jfs_fix_oob_read_caused_by_invalid_dir_slot_index.patch]]
- [[7ys6vrd29swy0hb42rbhrc1sbsk4cq1g-autoconf-2.72]]
- [[82mw0nl5kb1zw36l4s4d0pdlfiadwlss-automake-1.18.1]]
- [[8bk0s9hp267kv3khm8zkx9xmn0l74zls-lvm2-2.03.33]]
- [[8byci7l69y5r474c447hjg6vp8k9xk5h-64_fs_sfs_check_if_allocated_memory_is_NULL.patch]]
- [[8ppbj5i1gmjlbshwk02nz6hh2ghqs0d9-54_fs_use_safe_math_macros_to_prevent_overflows.patch]]
- [[8x5xcg8jn5p01v0i4v1kmh2vj81dqqpv-39_CVE-2025-0622.patch]]
- [[91n9j5a8n4b53p1hkncpqbdqkf1dbxc2-30_CVE-2025-0624.patch]]
- [[92clabbix8ycz5y3m2nbn96gnybn2b6r-59_fs_zfs_check_if_returned_pointer_for_allocated_memory_is_NULL.patch]]
- [[9731glgbnvnapv7d1l62v6knsaix9q6s-20_fs_xfs_ensuring_failing_to_mount_sets_a_grub_errno.patch]]
- [[a5llcyy0393fhn1y5grkpvd9ad59zwf8-unifont-16.0.03]]
- [[bjpfk0vavj0z54m12s1l36hhxi3a32zz-70_kern_partition_add_sanity_check_after_grub_strtoul_call.patch]]
- [[bjsb6wdjykafnkixq156qdvmxhsm2bai-bash-5.3p3]]
- [[ca5d4l2v9lka2n6gzzpgmkl8a4da0d7b-53_disk_ieee1275_ofdisk_call_grub_ieee1275_close_when_grub_malloc_fails.patch]]
- [[cwlpy97cgbfw0nd0pz3baam87bakz7pj-grub]]
- [[dgl0dczsv73rxffpsnx68scj18aphk2k-69_normal_menu_use_safe_math_to_avoid_an_integer_overflow.patch]]
- [[dqz0bjrjh2b6ddqij2rq20ays5fh33h6-56_fs_prevent_overflows_when_assigning_returned_values_from_read_number.patch]]
- [[dwgy75dbif3dchh4vnps0kmib7dp4zb1-gnulib-9f48fb9]]
- [[ffnmprcl79554fv3958hwjj0l7jx77ij-72_loader_i386_linux_cast_left_shift_to_grub_uint32_t.patch]]
- [[frk2a90zvfhjy1d14vxmrr0jyh41cwfc-57_fs_zfs_use_safe_math_macros_to_prevent_overflows.patch]]
- [[ggagm8739wac3hl5qna0k9rsi4q7g3km-37_commands_ls_fix_NULL_dereference.patch]]
- [[h91phv8458g6l4ic425l62xd7p9vxxil-68_bus_usb_ehci_define_GRUB_EHCI_TOGGLE_as_grub_uint32_t.patch]]
- [[h93gnc8inw8d41fiz6jip1ix32yamg49-41_CVE-2024-45776.patch]]
- [[i4x2hgjq7w72kvzmpp55yzkwqjjrby8f-23_prerequisite_1_key_protector_add_key_protectors_framework.patch]]
- [[i9kj1nhzkg91xsq8ny4z4hipl0b42kad-gcc-wrapper-14.3.0]]
- [[ibsmlqcxm91s0xm17j2p5fa1pgsjxdvj-source]]
- [[imlvmhvaajbpq2a92jibafn41qj8gqa2-65_script_execute_fix_potential_underflow_and_NULL.patch]]
- [[iqb95y7r9ci6fbv4rfg9i9h56l2cx5wq-43_CVE-2025-0690.patch]]
- [[iygxhg4q7g1y9n6n6wjyiq13jhwx53ks-58_fs_zfs_prevent_overflows_when_allocating_memory_for_arrays.patch]]
- [[jgzn4iyjlpkalmdkzfpqdn4vc6v7vald-71_kern_misc_add_sanity_check_after_grub_strtoul_call.patch]]
- [[ji56v9i7bdf14w53nxy71cpr8rrrvmma-fuse-2.9.9]]
- [[lvdvlk7cwad5mna0wfpz8jllb30jdj1n-pkg-config-wrapper-0.29.2]]
- [[lzza86b7jp5f09ikvknmj223c8nchs1a-55_CVE-2025-0678_CVE-2025-1125.patch]]
- [[m0h8vm7wnxqmzy77yph902p607lx7np5-gettext-0.25.1]]
- [[m2jymp21f3h46p9j6nhihxn12zvd9pyv-05_CVE-2024-45780.patch]]
- [[mam6l15gjjjr96r1mq9a8cm5z09sdy71-48_CVE-2024-45778_CVE-2024-45779.patch]]
- [[mf26w0c6kv13y880vvznxx1gnfb4j39m-60_fs_zfs_add_missing_NULL_check_after_grub_strdup_call.patch]]
- [[mqln4i09l8dxlf8iz9pymll9c65jiq9h-61_net_use_safe_math_macros_to_prevent_overflows.patch]]
- [[msdjw0vq553gdsjgj0g6226cfdvfnb5a-24_disk_loopback_reference_tracking_for_the_loopback.patch]]
- [[n1094mb1mfbgz7c6z04f06smgidni26i-libusb-compat-0.1.8]]
- [[n1nikzgv3a92xq4vyv79y96p653m06fb-22_kern_file_implement_filesystem_reference_counting.patch]]
- [[nqib6k90ayq7krk0knlf02yx4n8pisg8-23_prerequisite_4_cryptodisk_fallback_to_passphrase.patch]]
- [[nrhizkfylpc0v2szg6w074b9dfni91d9-16_fs_ntfs_track_the_end_of_the_MFT_attribute_buffer.patch]]
- [[nz4a0cj9w7as9xfbj2l5m0fay9i626b1-13_fs_jfs_inconsistent_signed_unsigned_types_usage.patch]]
- [[nzmz51wd8xs4a74afrz51hsxfbvjzghs-19_fs_xfs_fix_out-of-bounds_read.patch]]
- [[p1v3j013p7w5rzfmvwl39301mf4if1wv-10_fs_jfs_fix_oob_read_jfs_getent.patch]]
- [[p76r0cwlf6k97ibprrpfd8xw0r8wc3nx-stdenv-linux]]
- [[p7ljy5yls04pk6zv7rq8241ky5rqhkng-62_net_prevent_overflows_when_allocating_memory_for_arrays.patch]]
- [[pmm98c2fca7ssq8gwjzcdqx6bpkblkl9-47_commands_hexdump_disable_memory_reading_in_lockdown_mode.patch]]
- [[q8da6spb48z3pzhpr1crzjxgw9a3axsk-66_osdep_unix_getroot_fix_potential_underflow.patch]]
- [[q9dyf4wynims7fsb70s09dfcg0a50p6w-42_CVE-2024-45777.patch]]
- [[qq839ab700wh2y0bzv9qlnqsh9pha035-35_kern_dl_check_for_the_SHF_INFO_LINK_flag_in_grub_dl_relocate_symbols.patch]]
- [[rkqgmxn73sx301ni1yncm8j0xsgmp2gj-36_CVE-2024-45775.patch]]
- [[sv8lxxb30bqw2b360ni6rsp89mg2dvbp-libtool-2.5.4]]
- [[v28sdl3535sxb6a71z5faqdzbns9pv0h-bash-interactive-5.3p3]]
- [[v55j29k4fidsq2ivys3jrq68gz4y9dzf-40_CVE-2025-0622.patch]]
- [[vb2kwkfnigrigp8m9m8nzmm3alg7wgx4-17_fs_ntfs_use_a_helper_function_to_access_attributes.patch]]
- [[vgxkazgin4c6z863bj3il9mmil36jb9p-33_kern_dl_fix_for_an_integer_overflow_in_grub_dl_ref.patch]]
- [[vqgmfx2waa6y4x97q6v4j48h4szxpxyx-23_CVE-2024-49504.patch]]
- [[wafqby4089vkq19a4n9sgxbrhvwhsbwp-14_fs_ext2_fix_out-of-bounds_read_for_inline_extent.patch]]
- [[wj9cymvqzyavz1g92sa0cqlxz6lvnf73-01_implement_grub_strlcpy.patch]]
- [[wl9zm6bk73frrfkgyr6h8acns0745jzb-50_disk_use_safe_math_macros_to_prevent_overflows.patch]]
- [[wp82523m33ykvzkjclyy21vxzad0y5as-help2man-1.49.3]]
- [[wy61x67y125m36dp7l7xhzqbi30mxg1d-flex-2.6.4]]
- [[x17vw9q11mairr0skk308kl5rpa7807w-38_CVE-2025-0622.patch]]
- [[xnn335blr27q8h9dg3d6696kwgxpz8ag-08_fs_iso9660_grub_errno_mount_fails.patch]]
- [[xp6fz8gjnxivdphsgz06vbjcjzi89kln-27_script_execute_limit_the_recursion_depth.patch]]
- [[ydp8njviszc8pxlh63j420sj6iabdwxz-06_fs_f2fs_grub_errno_mount_fails.patch]]
- [[yyna9hb60605n7307ykrijmcwmdd4jj4-23_prerequisite_6_cli_lock_add_build_option_to_block_command_line_interface.patch]]
- [[zz4rj75i6sd4sjk9ca4yahpp4llzz09k-49_CVE-2025-0677_CVE-2025-0684_CVE-2025-0685_CVE-2025-0686_CVE-2025-0689.patch]]

## 📁 Input Sources

- `/nix/store/fg92ym9ifqwggcxk3ynkv2ip4vwqkh69-add-hidden-menu-entries.patch`
- `/nix/store/inn8vk1qhayb7z9929hv6fnc5ks88nr4-fix-bash-completion.patch`
- `/nix/store/l622p70vy8k5sh7y5wizi5f2mic6ynpg-source-stdenv.sh`
- `/nix/store/r989dk196nl9frhnfsa1lb7knhbyjxw6-separate-debug-info.sh`
- `/nix/store/shkw4qm9qcw5sc5n1k5jznc83ny02r39-default-builder.sh`

---
*Generated on 2025-09-27 11:58:13 UTC*
