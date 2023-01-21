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

Mitigation
============ 
Update the WordPress Responsive Vertical Icon Menu plugin to the latest available version (at least 1.5.9).

Timeline
============ 
  * 08 January 2023: Vulnerability reported thru patchstack.com.
  * 10 January 2023: Vulnerability valid
  * 18 January 2023: Patch version rolled out
  * 20 January 2023: Vulnerability disclosed

References
============ 
  * [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-23870](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-23870)
  * [Patchstack](https://patchstack.com/database/vulnerability/wpdevart-vertical-menu/wordpress-responsive-vertical-icon-menu-plugin-1-5-8-cross-site-scripting-xss)



[Rio Darmawan](https://patchstack.com/database/researcher/0f0ce3de-fbab-4348-9729-a5ef92c74b3e)
