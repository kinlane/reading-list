---
layout: post
title: OpenSSL Heartbleed Update
url: http://blog.softlayer.com/2014/openssl-heartbleed-update
source: http://blog.softlayer.com/2014/openssl-heartbleed-update
domain: blog.softlayer.com
image: 
---

<p>On April 7th, the OpenSSL Project released an update to address a serious security flaw (CVE-2014-0160), which allows remote attackers to obtain sensitive information from process memory via crafted packets that trigger a buffer over-read, as demonstrated by reading private keys, related to d1_both.c and t1_lib.c, aka the Heartbleed bug.After notification of this vulnerability we began a close examination of our services to determine any that may have been affected.Both the SoftLayer customer portal and API are serviced behind hardware load balancers and neither the hardware load balancers nor the software running on the servers behind them were found to be running vulnerable versions of OpenSSL.</p>
<center><p><a href="http://blog.softlayer.com/2014/openssl-heartbleed-update" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>
