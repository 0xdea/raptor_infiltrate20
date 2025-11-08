# raptor_infiltrate20

[![](https://img.shields.io/github/stars/0xdea/raptor_infiltrate20.svg?style=flat&color=yellow)](https://github.com/0xdea/raptor_infiltrate20)
[![](https://img.shields.io/github/forks/0xdea/raptor_infiltrate20.svg?style=flat&color=green)](https://github.com/0xdea/raptor_infiltrate20)
[![](https://img.shields.io/github/watchers/0xdea/raptor_infiltrate20.svg?style=flat&color=red)](https://github.com/0xdea/raptor_infiltrate20)
[![](https://img.shields.io/badge/twitter-%400xdea-blue.svg)](https://twitter.com/0xdea)
[![](https://img.shields.io/badge/mastodon-%40raptor-purple.svg)](https://infosec.exchange/@raptor)

> "Bugs are by far the largest and most successful class of entity."
>
> -- Encyclopedia of Animal Life

This repository contains all materials related to my talk *"The INFILTRATE effect: 6 bugs in 6 months"* presented at #INFILTRATE20 on January 26, 2021.

Related links:  
<https://hnsecurity.it/blog/the-infiltrate-effect-6-bugs-in-6-months/> (blog)  
<https://vimeo.com/474793702> (video)  

## advisories

* [**2019-02-solaris-xscreensaver**](advisories/2019-02-solaris-xscreensaver.txt). Local privilege escalation via xscreensaver (CVE-2019-3010).
* [**2020-01-solaris-xlock**](advisories/2020-01-solaris-xlock.txt). Low impact information disclosure via Solaris xlock (CVE-2020-2656).
* [**2020-02-cde-dtsession**](advisories/2020-02-cde-dtsession.txt). Local privilege escalation via CDE dtsession (CVE-2020-2696).
* [**2020-05-cde-sdtcm_convert**](advisories/2020-05-cde-sdtcm_convert.txt). Local privilege escalation via CDE sdtcm_convert (CVE-2020-2944).
* [**2020-06-cde-libDtSvc**](advisories/2020-06-cde-libDtSvc.txt). Stack-based buffer overflow in CDE libDtSvc (CVE-2020-2851).
* [**2020-07-solaris-whodo-w**](advisories/2020-07-solaris-whodo-w.txt). Heap-based buffer overflow in Solaris whodo, w commands (CVE-2020-2771).

## exploits

* [**raptor_xscreensaver**](exploits/raptor_xscreensaver). Solaris 11.x (CVE-2019-3010). Local privilege escalation via xscreensaver.
* [**raptor_session_ipa.c**](exploits/raptor_dtsession_ipa.c). Solaris 10 (CVE-2020-2696). Local privilege escalation via CDE dtsession (Intel).
* [**raptor_sdtcm_conv.c**](exploits/raptor_sdtcm_conv.c). Solaris 10 (CVE-2020-2944). Local privilege escalation via CDE sdtcm_convert (Intel).
* [**raptor_dtprintname_sparc3.c**](exploits/raptor_dtprintname_sparc3.c). Solaris 10 (CVE-2019-2832). Buffer overflow in CDE dtprintinfo (SPARC).
* [**raptor_dtprintcheckdir_intel.c**](exploits/raptor_dtprintcheckdir_intel.c). Solaris 10 (0day?). Another buffer overflow in CDE dtprintinfo (Intel).
* [**raptor_dtprintcheckdir_intel2.c**](exploits/raptor_dtprintcheckdir_intel2.c). Solaris 10 (0day?). Format string bug in CDE dtprintinfo (Intel).
* [**raptor_dtprintcheckdir_sparc.c**](exploits/raptor_dtprintcheckdir_sparc.c). Solaris 10 (0day?). Format string bug in CDE dtprintinfo (SPARC PoC).
* [**raptor_dtprintcheckdir_sparc2.c**](exploits/raptor_dtprintcheckdir_sparc2.c). Solaris 10 (0day?). Format string bug in CDE dtprintinfo (SPARC).

## slides

* [**6bugs.pdf**](slides/6bugs.pdf). Slide deck presented at #INFILTRATE20 (PDF version).
* [**6bugs.pptx**](slides/6bugs.pptx). Slide deck presented at #INFILTRATE20 (PowerPoint version).
