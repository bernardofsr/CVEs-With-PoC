# Form Tools - Version 3.0.20

### CVE-2021-38143 - Stored XSS
An issue was discovered in Form Tools through 3.0.20.
When an administrator creates a customer account, it is possible for the customer to log in and proceed with a change of name and last name. However, these fields are vulnerable to XSS payload insertion, being triggered in the admin panel when the admin tries to see the client list. This type of XSS (Stored) can lead to the extraction of the PHPSESSID cookie belonging to the admin.

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
### CVE-2021-38144
[Reserved CVE][Soon Available]

### CVE-2021-38145
[Reserved CVE][Soon Available]

