# Exchange_DIVD-2021-00001

Collection of scripts used while testing for exchange vulnerabilities of 2 March 2021
(Only scripts that are publicly available are stored here)

## Current scripts

### http-vuln-exchange_v4.nse
Improved version of the version scanning script based on Kevin Baumont's script: https://github.com/GossiTheDog/scanning
Current location: https://github.com/DIVD-NL/scanning
Removed Exchange 2010 as the vulnerability is less critical.

### http-vuln-cve2021-26855_patched.nse
Patched version of the script that also returns output if the host isn't vulenrable

## retired scripts

### http-vuln-exchange.nse
Original version of Kevin Baumont https://github.com/GossiTheDog/scanning

### http-vuln-exchange_v2.nse
Improved script of Kevin Baumont https://github.com/GossiTheDog/scanning

### http-vuln-exchange_v3.nse
Improved version of the version scanning script based on Kevin Baumont's script: https://github.com/GossiTheDog/scanning
Current location: https://github.com/DIVD-NL/scanning

### http-vuln-cve2021-26855.nse
Original script from https://github.com/microsoft/CSS-Exchange/blob/main/Security/src/http-vuln-cve2021-26855.nse

