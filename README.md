# Web Application Security

## Course Description

This is an introductory course on «Web Application Security» is teached to students of the «Computer Security» speciality in [National Research Tomsk State University](http://en.tsu.ru/) on the [Information Security and Cryptography Department](http://isc.tsu.ru).

## Problem Sets
The following [assignments](assignments.md) should be completed.

### Getting Started With Burp Suite
1. Download a free version of [Burp Suite](https://portswigger.net/burp/freedownload).
2. Install Java.
3. Run `Burp Suite` with the following command:

  ```
  java -jar -Xmx1024m /path/to/burp.jar
  ```

4. Configure a proxy server in your browser to use `Burp Suite`.

## Resources

* [OWASP Testing Guide](https://www.owasp.org/index.php/OWASP_Testing_Guide_v4_Table_of_Contents)
* [Getting Started With Burp Suite](https://portswigger.net/burp/help/suite_gettingstarted.html)
* [Special Vulnerable Applications](apps.md)
* [Challenges](challenges.md)
* [Tools](tools.md)
* [SSL Checklist for Pentesters](http://www.exploresecurity.com/wp-content/uploads/custom/SSL_manual_cheatsheet.html)

## Readings

### Common Attacks
* [Hacking with Unicode](https://speakerdeck.com/mathiasbynens/hacking-with-unicode)
* [Exploiting the unexploitable with lesser known browser tricks](https://speakerdeck.com/filedescriptor/exploiting-the-unexploitable-with-lesser-known-browser-tricks)

### Same Origin Policy
* [Cookie Same Origin Policy](https://crypto.stanford.edu/cs142/lectures/10-cookie-security.pdf)
* [Hacking cookies in modern web applications and browsers](http://gsec.hitb.org/materials/sg2015/D1%20-%20Dawid%20Czagan%20-%20Hacking%20Cookies%20in%20Modern%20Web%20Applications%20and%20Browsers.pdf)
* [SOP Bypass Test Suite](https://github.com/rafaybaloch/SOP-Bypass-Mini-Test-Suite)
* [Preventing XSS-attacks using Same-site Cookies](https://blogs.dropbox.com/tech/2017/03/preventing-cross-site-attacks-using-same-site-cookies/)
* [The Security Model of the Web](http://schd.ws/hosted_files/secappdev2017/a2/DeRyck_SecAppDev_WebSecurityModel.pdf)
* [Same-Origin Policy: Evaluation in Modern Browsers](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-schwenk.pdf)

### Injections
* [The Essence of Command Injection Attacks in Web Applications](http://web.cs.ucdavis.edu/~su/publications/popl06.pdf)
* [Evading All Web-application Firewalls XSS Filters](https://www.exploit-db.com/docs/38117.pdf)
* [XML Schema, DTD, and Entity Attacks](https://www.vsecurity.com//download/papers/XMLDTDEntityAttacks.pdf)
* [XSS Polyglots](https://blog.bugcrowd.com/xss-polyglots-the-context-contest)
* [How To: Command Injections](https://www.hackerone.com/blog/how-to-command-injections)
* [Backslash Powered Scanning](https://www.youtube.com/watch?list=PLuUtcRxSUZUpv2An-RNhjuZSJ5fjY7ghe&v=EPmjl7q1-n4)

### RPO
* [RPO attack](http://www.thespanner.co.uk/2014/03/21/rpo/)
* [Обзор атак на клиента с помощью CSS](https://raz0r.name/articles/css-attacks/)
* [Detecting and exploiting path-relative stylesheet import (PRSSI) vulnerabilities](http://blog.portswigger.net/2015/02/prssi.html)
* [RPO Gadgets](http://blog.innerht.ml/rpo-gadgets/)
* [A few RPO exploitation techniques](http://www.mbsd.jp/Whitepaper/rpo.pdf)
