# my-kernel-patches
## Patches for the linux kernel

- [README 2025](README2025.md) 

## 2024-02-10
### 7.00 TIP (aae3ab427a426b2b24053c8089274f5315cd8e75)
* add NVIDIA patch (in a very early stage...)
* add kernel patches, upgrade POC selector patches to 1.9.3

## 2024-02-09
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
