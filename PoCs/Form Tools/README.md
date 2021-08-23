# Form Tools - Version 3.0.20

### CVE-2021-38143 - Stored XSS
An issue was discovered in Form Tools through 3.0.20.
When an administrator creates a customer account, it is possible for the customer to log in and proceed with a change of name and last name. However, these fields are vulnerable to XSS payload insertion, being triggered in the admin panel when the admin tries to see the client list. This type of XSS (Stored) can lead to the extraction of the PHPSESSID cookie belonging to the admin.

###

Insertion of the payload in the "First Name" field:

![alt text](https://github.com/bernardofsr/CVEs-With-PoC/blob/main/PoCs/Form%20Tools/images/StoredXSS.png?raw=true "Payload on 'First Name'")

###
The administrator logs in and opens the page with the list of clients:

![alt text](https://github.com/bernardofsr/CVEs-With-PoC/blob/main/PoCs/Form%20Tools/images/StoredXSS2.png?raw=true "Payload triggered")

XSS triggered and exposing the admin cookie.

##

### CVE-2021-38144 - Reflected XSS
[Reserved CVE][Soon Available]

##

### CVE-2021-38145 - SQL Injection
[Reserved CVE][Soon Available]

