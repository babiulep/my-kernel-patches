# my-kernel-patches
Patches for the linux kernel

2024-09-17:
- bore scheduler update to mainline commit 2f27fce67173bbb05d5a0ee03dae5c021202c912
  (version 5.3.0-rc3)

2024-09-17:
- problem: WARNING: CPU: 3 PID: 845 at drivers/gpu/drm/drm_file.c:321 drm_open_helper
  fix(?): drm_file.c.revert.patch (apply with patch -p1 -E -R)

- Bore Scheduler (by Masahito Suzuki)
Fixes to ptr1337's bore-cachy-next (for CachyOS kernels) to make it work with
Ingo Molnar's tip branch (git://git.kernel.org/pub/scm/linux/kernel/git/tip/tip.git)
