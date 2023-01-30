---
layout: post
title: CVE-2023-24381 - Advanced Social Pixel Plugin <= 2.1.1 - Cross Site Scripting (XSS)
---

Description
============
Advanced Social Pixel Plugin <= 2.1.1 This could allow a malicious actor to inject malicious scripts, such as redirects, advertisements, and other HTML payloads into your website which will be executed when guests visit your site.

Proof Of Concept
============
Payload

~~~
" onfocus=alert(/XSS/) autofocus="
~~~

Timeline
============ 
  * 06 January 2023: Vulnerability reported thru patchstack.com.
  * 07 January 2023: Vulnerability valid
  * 18 January 2023: Plugin deactivated and close not available for download
  * 27 January 2023: Vulnerability disclosed

References
============ 
  * [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-24381](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-24381)
  * [Patchstack](https://patchstack.com/database/vulnerability/ns-facebook-pixel-for-wp/wordpress-advanced-social-pixel-plugin-2-1-1-cross-site-scripting-xss)



[Rio Darmawan](https://patchstack.com/database/researcher/0f0ce3de-fbab-4348-9729-a5ef92c74b3e)
