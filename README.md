# CVE-2020-5844

## Authenticated RCE in PandoraFMS 7.0-NG 742
Admin privileged attackers can upload malicious PHP documents. By decoding the base64 file location users can gain a shell as apache user. 

Discovered by TheCyberGeek

## PoC python script
```
Usage: python3 CVE-2020-5844.py URL USER PASS PHP_REVERSE_SHELL
Ex: python3 CVE-2020-5844.py http://10.0.0.2/pandora_console admin pandora reverse.php
```
