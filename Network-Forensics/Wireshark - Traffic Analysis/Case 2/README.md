Case 2 – Summary

Case 2 analyses an internal network packet capture showing a full attack lifecycle against an FTP service at 192.168.0.1. The activity originates from an internal host (192.168.0.20 running a VirtualBox environment) and progresses through reconnaissance, brute-force authentication, successful compromise, and data exfiltration.

The attacker begins with ARP-based host discovery and ICMP connectivity checks, followed by an FTP brute-force attack that generates a large number of failed login attempts before successful authentication using valid credentials (dvwa / Password1!). After gaining access, the attacker performs FTP enumeration using standard commands such as SYST, FEAT, LIST, and EPSV to identify system information and available resources.

Following compromise, multiple files are downloaded via FTP data channels, confirming data exfiltration. Key weaknesses include weak password policies, lack of account lockout or rate limiting, use of unencrypted FTP traffic, and outdated FTP server software (ProFTPD 1.3.2c) with known vulnerabilities. Overall, the capture demonstrates a complete internal compromise leading to unauthorised access and file extraction.
