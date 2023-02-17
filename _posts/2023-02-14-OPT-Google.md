---
layout: post
title: CVE-2023-25712 - Opt-Out for Google Analytics Plugin <= 2.3.4 - Cross Site Scripting (XSS)
---

Description
============
Opt-Out for Google Analytics Plugin <= 2.3.4 This could allow a malicious actor to inject malicious scripts, such as redirects, advertisements, and other HTML payloads into your website which will be executed when guests visit your site.

Proof Of Concept
============
Payload

~~~
" onfocus=alert(/XSS/) autofocus="
~~~

Mitigation
============ 
Update the WordPress Opt-Out for Google Analytics plugin to the latest available version (at least 2.3.5).

Timeline
============ 
  * 10 February 2023: Vulnerability reported thru patchstack.com.
  * 10 January 2023: Vulnerability valid
  * 14 February 2023: Patch version rolled out
  * 14 January 2023: Vulnerability disclosed

References
============ 
  * [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-25712](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-25712)
  * [Patchstack](https://patchstack.com/database/vulnerability/google-analytics-opt-out/wordpress-opt-out-for-google-analytics-plugin-2-3-4-cross-site-scripting-xss-vulnerability)



[Rio Darmawan](https://patchstack.com/database/researcher/0f0ce3de-fbab-4348-9729-a5ef92c74b3e)
