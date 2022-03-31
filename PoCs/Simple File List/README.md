# Simple File List - Versions <=3.2.7

### CVE-2022-1119 - Arbitraty File Download
The Simple File List WordPress plugin is vulnerable to Arbitrary File Download via the eeFile parameter found in the ~/includes/ee-downloader.php file due to missing controls which makes it possible unauthenticated attackers to supply a path to a file that will subsequently be downloaded, in versions up to and including 3.2.7.

###
**CVSS Data:**
```
CVSS Score: 7.5 (High)
CVSS Vector: CVSS:3.1/A:N/I:N/C:H/S:U/UI:N/PR:N/AC:L/AV:N
```

###
**Vulnerable endpoint example:**
```
example.com/wp-content/plugins/simple-file-list/includes/ee-downloader.php?eeFile=/etc/passwd
```

###
**Publication Date:**
```
2022-03-28
```