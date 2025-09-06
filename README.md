# my-kernel-patches
Patches for the linux kernel

2025-09-06:
- remove BORE patch  
- update patches (offsets)  
- add new adios (version 3)

2025-08-20:
- revert adios fix  
- fix adios patch for 6.17

2025-08-12:
- NVIDIA GPL issues patch  
- BORE scheduler patch for 6.17

2025-08-08:
- NVIDIA for next/6.17 fix 

2025-08-05:
- NVIDIA: patch for linux kernel next/6.17 for 580.65.06

2025-07-31:
- adios: fix for linux-next >= 2025073 in NEXT_PATCHES

2025-07-30:
- Split patches:  
- PATCHES: 6.16  
- NEXT_PATCHES: next/6.17  
- New NVIDIA patch for linux kernel next/6.17
  (tested with versions 575.57.08 and 575.64.03)

2025-06-02:
- Total patch with:  
  ADIOS  
  bbr3  
  zram-ir  
  polly  
  mitigate off  
  and cleanup

2024-05-08:
- KBUILD_CFLAGS fix when use clang compiler

2025-05-07:
- add clear patch for 6.15-rcX

2025-05-02:
- updated NVIDIA patches for version 575.51.03

2025-04-08:
- simplified NVIDIA patch for 6.15-rc1

2025-04-07:
- more changes needed for NVIDIA modules

2025-04-05:
- tentative nvidia patch for 6.15:  
  tested with nvidia-570.124.06
- update adios patch

2025-03-23:
- update patches

2025-01-16:
- update patches

2025-01-13:
- update patches

2025-01-12:
- update patches

2024-12-24:
- bore 5.9.4 for linux-tip

2024-12-24:
- added Jens Axboe Uncached Buffered I/O patch for 6.13-tip  
  updated bore scheduler for tip branch to 5.7.14

2024-12-23:
- freeze because of usb bug in tree: solved  
  patches updated for 6.13.x

2024-12-02:
- some patches make the system freeze?  
  moved to TO_TEST

2024-11-30:
add ipu6 fix  
add usb/thunderbolt patch (6.13)  
add driver-core patch from GKH (6.13)  
add nfs-client patch (6.13)  
update bore scheduler from 5.7.3 to 5.7.4  
add rtc patch (6.13)

new branch added:  
- patches for 6.12.x from various sources  
- plus backports from 6.13  
- please apply patches in order...
