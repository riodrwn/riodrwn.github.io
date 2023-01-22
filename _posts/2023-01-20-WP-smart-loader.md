---
layout: post
title: CVE-2023-23675 - WP Smart Preloader Plugin <= 1.15 - Cross Site Scripting (XSS)
---

Description
============
WP Smart Preloader Plugin <= 1.15 This could allow a malicious actor to inject malicious scripts, such as redirects, advertisements, and other HTML payloads into your website which will be executed when guests visit your site.

Proof Of Concept
============
Payload

~~~
" onfocus=alert(/XSS/) autofocus="
~~~

Mitigation
============ 
Update the WordPress WP Smart Preloader plugin to the latest available version (at least 1.15.1)

Timeline
============ 
  * 12 January 2023: Vulnerability reported thru patchstack.com.
  * 12 January 2023: Vulnerability valid
  * 18 January 2023: Patch version rolled out
  * 20 January 2023: Vulnerability disclosed
  
References
============ 
  * [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-22716](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-23675)
  * [Patchstack](https://patchstack.com/database/vulnerability/wp-smart-preloader/wordpress-wp-smart-preloader-plugin-1-15-cross-site-scripting-xss-vulnerability)



[Rio Darmawan](https://patchstack.com/database/researcher/0f0ce3de-fbab-4348-9729-a5ef92c74b3e)
