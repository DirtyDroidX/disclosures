# disclosures

## CVEs

- ["Get Super Serial" CVE-2015-2231 & CVE-2015-2232](https://github.com/rednaga/disclosures/blob/master/GetSuperSerial.md)
  Chain from an application with internet permissions to a system uid, then from a system uid to root. This is mainly due to an extremely weak firmware upgrade system calls "ADUPS" which has failed to have any type of response. While the two specific CVEs directly correlate to a few Blu phones, it appears to be used by many other lower-end phones. 
