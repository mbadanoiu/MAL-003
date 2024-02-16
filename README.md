# MAL-003: Groovy Security Bypass and Stored XSS in Apache OfBiz

A Groovy RCE and XSS have been identified in Apache OfBiz <= 18.12.05.

### Why no CVE?

[Apache OfBiz](https://ofbiz.apache.org/) does not create CVEs for "post-auth attacks done using demo credentials, notably using the admin user" as mentioned on their [security page](https://ofbiz.apache.org/security.html).

### Requirements:

This vulnerability requires:
<br/>
- Valid user credentials

### Proof Of Concept:

More details and the exploitation process can be found in this [PDF](https://github.com/mbadanoiu/MAL-003/blob/main/Apache%20OfBiz%20-%20MAL-003.pdf).
