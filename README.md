# my-kernel-patches
Patches for the linux kernel

2024-09-17:
- bore scheduler: version 5.3.0-rc3
  update to mainline commit 2f27fce67173bbb05d5a0ee03dae5c021202c912

2024-09-17:
- problem: WARNING: CPU: 3 PID: 845 at drivers/gpu/drm/drm_file.c:321 drm_open_helper
  fix(?): drm_file.c.revert.patch (apply with patch -p1 -E -R)

- Bore Scheduler (by Masahito Suzuki)
Try to make it work Ingo Molnar's tip branch (git://git.kernel.org/pub/scm/linux/kernel/git/tip/tip.git) or mainline kernel
