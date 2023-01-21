---
layout: post
title: CVE-2023-23821 - Polish Map Plugin <= 1.2 - Cross Site Scripting (XSS)
---

Description
============
Polish Map Plugin <= 1.2 This could allow a malicious actor to inject malicious scripts, such as redirects, advertisements, and other HTML payloads into your website which will be executed when guests visit your site.

Proof Of Concept
============
Payload

~~~
" onfocus=alert(/XSS/) autofocus="
~~~

Mitigation
============ 
Update the WordPress Interactive Polish Map plugin to the latest available version (at least 1.2.1).

Timeline
============ 
  * 10 January 2023: Vulnerability reported thru patchstack.com.
  * 10 January 2023: Vulnerability valid
  * 18 January 2023: Patch version rolled out
  * 20 January 2023: Vulnerability disclosed

References
============ 
  * [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-23821](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-23821)
  * [Patchstack](https://patchstack.com/database/vulnerability/interactive-polish-map/wordpress-interactive-polish-map-plugin-1-2-cross-site-scripting-xss-vulnerability)



[Rio Darmawan](https://patchstack.com/database/researcher/0f0ce3de-fbab-4348-9729-a5ef92c74b3e)
