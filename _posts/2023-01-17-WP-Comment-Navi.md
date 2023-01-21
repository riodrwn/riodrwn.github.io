---
layout: post
title: CVE-2023-22715 - WP-CommentNavi Plugin <= 1.12.1 - Cross Site Scripting (XSS)
---

Description
============
WP-CommentNavi Plugin <= 1.12.1 This could allow a malicious actor to inject malicious scripts, such as redirects, advertisements, and other HTML payloads into your website which will be executed when guests visit your site.

Proof Of Concept
============
Payload

~~~
" onfocus=alert(/XSS/) autofocus="
~~~

Mitigation
============ 
Update the WordPress WP-CommentNavi plugin to the latest available version (at least 1.12.2).

Timeline
============ 
  * 10 January 2023: Vulnerability reported thru patchstack.com.
  * 10 January 2023: Vulnerability valid
  * 16 January 2023: Patch version rolled out
  * 17 January 2023: Vulnerability disclosed
 
References
============ 
  * [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-22715](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-22715)
  * [Patchstack](https://patchstack.com/database/vulnerability/wp-commentnavi/wordpress-wp-commentnavi-plugin-1-12-1-cross-site-scripting-xss)



[Rio Darmawan](https://patchstack.com/database/researcher/0f0ce3de-fbab-4348-9729-a5ef92c74b3e)
