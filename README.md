# my-kernel-patches
## Patches for the linux kernel

- [README 2025](README2025.md) 

## 2026-03-20
* TIP+NEXT: add kbuild patch
* TIP+NEXT: sync patches

## 2026-03-19
* NEXT: remove POC selector (for now...)
* TIP: update Camsyses to v0.2.6
* TIP: update zstd
* TIP+NEXT: add mglru patch

## 2026-03-18
* NEXT: update Camsyses to v0.2.6
* NEXT: update zstd
* NEXT: add mglru patch

## 2026-03-16
* TIP+MEXT: update patches

## 2026-03-15
* TIP: added [Cambyses Migration Selector](https://github.com/firelzrd/cambyses) v0.1.0 by Masahito Suzuki  
  (had to disable SIMD when using Clang, works with GCC)

## 2026-03-14
* TIP: ported firelzrd's [kcompressd-unofficial](https://github.com/firelzrd/kcompressd-unofficial) patch
* TIP: downgrade BORE: from v6.7.3 to v6.6.2

## 2026-03-09
* TIP+NEXT: remove objtool patch

## 2026-03-08
* NEXT: updated patches for next-20260306
* TIP: update re-swappiness: v1.2
* TIP: added le9uo patch

## 2026-03-06
* TIP: update nap: v0.2.0r2 (fixes clang compilation)
* TIP: update POC: v2.2.8
* TIP: update BORE: v6.7.3

## 2026-03-01
* TIP: upgrade nap: v0.1.6 (one for use with gcc, one for clang)
* TIP: upgrade POC selector: v2.2.5

## 2026-02-28
* TIP: upgrade to nap v0.1.2

## 2026-02-27
* split patches between NEXT and TIP
* TIP+NEXT: upgrade POC selector patches to 2.2.0
* TIP+NEXT: added nap-v0.1.0.patch (only compiles when using GCC)
* TIP+NEXT: added Reflex-CPUFreq-Governor-v0.2.2.patch
* TIP: added re-swappiness-v1.1.patch
* TIP: add fix for unused variables in re-swappiness-v1.1.patch

## 2026-02-23
* add bbr3 and block (mq & bfq) patches

## 2026-02-17
* one NVIDIA patch for TIP & NEXT trees

## 2026-02-17
* upgrade ADIOS from 3.1.9 to 3.1.11

## 2026-02-16
* fix polly patch
* upgrade POC selector patches to 2.0.0

## 2026-02-15
* update patches (offset fixes only)
* add '[hibernate](https://lore.kernel.org/linux-mm/20260215-hibernate-perf-v2-0-cf28c75b04b7@tencent.com/)'-patch

## 2026-02-14
* upgrade POC selector patches to 2.0.0-rc3

## 2026-02-13
* TIP: new NVIDIA patch

## 2026-02-12
* upgrade POC selector patches to 2.0.0-rc2

## 2026-02-11
* upgrade POC selector patches to 1.9.4
* split NVIDIA patches for TIP & NEXT trees

## 2026-02-10
* add NVIDIA patch (in a very early stage...)
* add kernel patches, upgrade POC selector patches to 1.9.3

## 2026-02-09
* 6.19 NEXT/TIP: upgrade POC selector patches from 1.6 to 1.8.1
* 6.19 TIP: remove bbr3 patch

## 2026-02-05
* 6.19 TIP: small (offset) fixes

## 2026-02-04
* 6.19 NEXT: remove scripts/sign-file patch (fixed in linux-next-next-20260203)  
* 6.19 NEXT: upgrade POC selector patches from 1.5 to 1.6
* 6.19 TIP: upgrade POC selector patches from 1.5 to 1.6

## 2026-02-03
* 6.19: upgrade POC selector patches from 1.3 to 1.5  
* CMS_NO_SIGNING_TIME fixed in linux-next-next-20260203

## 2026-02-03
* 6.19 NEXT: add scripts/sign-file patch: build failure on OpenSSL < CMS_NO_SIGNING_TIME  
* 6.19: upgrade adios patch to 3.1.9  
* 6.19: add POC selector patches

## 2026-02-02
* 6.19: upgrade bore-scheduler to 6.6.1

## 2026-01-28
* upgrade bore-scheduler to 6.6.0

## 2026-01-27
* added 'next'-patches for NVIDIA and VHBA kernel modules

## 2026-01-26
* separate patches for TIP and NEXT trees

## 2026-01-10
* add my [wgc](https://github.com/colemar/wgc/) rewrite for amneziawg  
  currently reads the extra config entries:  
  jc, jmin, jmax, h1, h2, h3, h4, s0, s1, i1, i2
