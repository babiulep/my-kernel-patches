
## 2025-12-29
* sync 6.19 patches

## 2025-12-20
* New NVIDIA patch for 6.19
* Added several kernel patches for 6.19
* Create directories for kernel versions 6.18 and 6.19

## 2025-12-17
* Be careful using these NVIDIA patches for the upcoming kernel 6.19
* A lot has changed since and your (dkms) build will probably fail...

## 2025-12-14
* show my preferred order of patches
* sync patches with 6.18.1

## 2025-11-22
* sync patches with 6.18-rc7

## 2025-11-06:
* remove branch 6.17
* include 6.18 patches when applying 6.19 patches!

## 2025-11-05:
* NVIDIA: add new folder 6.19 for linux-next patches
* add drm_error.patch for linux next 20251105

## 2025-10-30:
* add dma.patch for linux next 20251030

## 2025-10-27:
* In linux-next Eric Biggers has [changed the BLAKE2b library API](https://lore.kernel.org/all/20251018043106.375964-1-ebiggers@kernel.org/)
* A patch for the dkms version of the amneziawg kernel module is added:
  AMNEZIAWG/blake2s.patch

## 2025-10-26:
* rearrange patches
* 'module_fix.patch' no longer needed
* LINUX-TIP: add 'in_irq.patch': ['in_irq' has changed into 'in_hardirq'](https://lore.kernel.org/all/176133511760.2601451.11756138328464524645.tip-bot2@tip-bot2/)

## 2025-10-24:
* 'module_fix.patch' included in source tree

## 2025-10-22:
* LINUX-NEXT: 'state.patch' fix for NVIDIA (tested with 580.95.05)
* 'module_fix.patch' for TIP & NEXT branches
* add working 'adios' (v3) patch for linux-6.18

## 2025-10-19:
* updates for upcoming 6.18-rc2

## 2025-09-06:
* remove BORE patch
* update patches (offsets)
* add new adios (version 3)

## 2025-08-20:
* revert adios fix
* fix adios patch for 6.17

## 2025-08-12:
* NVIDIA GPL issues patch
* BORE scheduler patch for 6.17

## 2025-08-08:
* NVIDIA for next/6.17 fix

## 2025-08-05:
* NVIDIA: patch for linux kernel next/6.17 for 580.65.06

## 2025-07-31:
* adios: fix for linux-next >= 2025073 in NEXT_PATCHES

## 2025-07-30:
* Split patches:
* PATCHES: 6.16
* NEXT_PATCHES: next/6.17
* New NVIDIA patch for linux kernel next/6.17
  (tested with versions 575.57.08 and 575.64.03)

## 2025-06-02:
* Total patch with:
  ADIOS
  bbr3
  zram-ir
  polly
  mitigate off
  and cleanup

## 2024-05-08:
* KBUILD_CFLAGS fix when use clang compiler

## 2025-05-07:
* add clear patch for 6.15-rcX

## 2025-05-02:
* updated NVIDIA patches for version 575.51.03

## 2025-04-08:
* simplified NVIDIA patch for 6.15-rc1

## 2025-04-07:
* more changes needed for NVIDIA modules

## 2025-04-05:
* tentative nvidia patch for 6.15:
  tested with nvidia-570.124.06
* update adios patch

## 2025-03-23:
* update patches

## 2025-01-16:
* update patches

## 2025-01-13:
* update patches

## 2025-01-12:
* update patches

## 2024-12-24:
* bore 5.9.4 for linux-tip

## 2024-12-24:
* added Jens Axboe Uncached Buffered I/O patch for 6.13-tip
* updated bore scheduler for tip branch to 5.7.14

## 2024-12-23:
* freeze because of usb bug in tree: solved
* patches updated for 6.13.x

## 2024-12-02:
* some patches make the system freeze?
* moved to TO_TEST

## 2024-11-30:
* add ipu6 fix
* add usb/thunderbolt patch (6.13)
* add driver-core patch from GKH (6.13)
* add nfs-client patch (6.13)
* update bore scheduler from 5.7.3 to 5.7.4
* add rtc patch (6.13)

## new branch added:
* patches for 6.12.x from various sources
* plus backports from 6.13
* please apply patches in order...
