# my-kernel-patches
Patches for the linux kernel

2024-09-19:
- mainline commit 839c4f596f898edc424070dc8b517381572f8502
  added nvidia-560.35.03.patch
  no longer needed: .output_poll_changed = nv_drm_output_poll_changed,

2024-09-17:
- bore scheduler: version 5.3.0-rc3
  update to mainline commit 2f27fce67173bbb05d5a0ee03dae5c021202c912

2024-09-17:
- problem: WARNING: CPU: 3 PID: 845 at drivers/gpu/drm/drm_file.c:321 drm_open_helper
  fix(?): drm_file.c.revert.patch (apply with patch -p1 -E -R)

- Bore Scheduler (by Masahito Suzuki)
Try to make it work Ingo Molnar's tip branch (git://git.kernel.org/pub/scm/linux/kernel/git/tip/tip.git) or mainline kernel
