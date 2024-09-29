# my-kernel-patches
Patches for the linux kernel

2024-09-29:
- remove bore5.3.0.patch  
  bore5.5.0.patch: mainline commit 3efc57369a0ce8f76bf0804f7e673982384e4ac9

2024-09-25:
- remove rc3 from bore5.5.0.patch

2024-09-24:
- update bore5.5.0.patch to 0001-linux6.11-bc9057da-bore5.5.0-rc3.patch

2024-09-23:
- updated bore5.5.0.patch to 0001-linux6.11-bc9057da-bore5.5.0-rc2.patch

2024-09-21:
- added bore5.5.0-rc1.patch for linux mainline  
  updated bore scheduler to 5.3.0 for linux mainline  
  renamed bore-scheduler-tip.patch to bore5.3.0.patch

2024-09-19:
- mainline commit 839c4f596f898edc424070dc8b517381572f8502  
  added nvidia-560.35.03.patch  
  - no longer needed: .output_poll_changed = nv_drm_output_poll_changed,

2024-09-17:
- bore scheduler: version 5.3.0-rc3  
  update to mainline commit 2f27fce67173bbb05d5a0ee03dae5c021202c912

2024-09-17:
- problem: WARNING: CPU: 3 PID: 845 at drivers/gpu/drm/drm_file.c:321 drm_open_helper  
  fix(?): drm_file.c.revert.patch (apply with patch -p1 -E -R)

- Bore Scheduler (by Masahito Suzuki)  
Try to make it work Ingo Molnar's tip branch (git://git.kernel.org/pub/scm/linux/kernel/git/tip/tip.git)  
or mainline kernel
