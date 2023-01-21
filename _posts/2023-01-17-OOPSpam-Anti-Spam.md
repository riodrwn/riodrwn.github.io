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

Mitigation
============ 
Update the WordPress OOPSpam Anti-Spam plugin to the latest available version (at least 1.1.36)

Timeline
============ 
  * 10 January 2023: Vulnerability reported thru patchstack.com.
  * 10 January 2023: Vulnerability valid
  * 17 January 2023: Patch version rolled out
  * 17 January 2023: Vulnerability disclosed
  
References
============ 
  * [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-22716](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-22716)
  * [Patchstack](https://patchstack.com/database/vulnerability/oopspam-anti-spam/wordpress-oopspam-anti-spam-plugin-1-1-35-cross-site-scripting-xss-vulnerability)



[Rio Darmawan](https://patchstack.com/database/researcher/0f0ce3de-fbab-4348-9729-a5ef92c74b3e)
