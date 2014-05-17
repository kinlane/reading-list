---
layout: post
title: OpenSSL Heartbleed Security Update
url: http://blog.cloudpassage.com/2014/04/09/openssl-heartbleed-security-update/
source: http://blog.cloudpassage.com/2014/04/09/openssl-heartbleed-security-update/
domain: blog.cloudpassage.com
image: 
---

<p>On Monday, the OpenSSL Project released an update to address the CVE-2014-0160 vulnerability, also known as “Heartbleed”.This serious vulnerability affects a substantial number of applications and services running on the Internet, including the CloudPassage Halo™ service. As of Tuesday, April 8th at 2:30pm PDT, all CloudPassage production systems have been updated and are no longer vulnerable. All communication between the Halo agents and the Halo analytics engine use message-level encryption, encrypting each payload, in order to mitigate SSL vulnerabilities at the transport layer.Vulnerability Details This vulnerability can be remotely exploited to leak encryption secrets from OpenSSL-encrypted sessions, allowing an attacker to retrieve private key material.</p>
<center><p><a href="http://blog.cloudpassage.com/2014/04/09/openssl-heartbleed-security-update/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>
