# Host 1 – Internal Network Compromise (Windows)

## Summary
Full compromise achieved from unauthenticated access to SYSTEM level.

## Key Attack Chain
- Anonymous FTP access
- Credential discovery in exposed file
- POP3 plaintext credential retrieval
- RDP login using reused credentials
- Privilege escalation via Metasploit exploit

## Impact
- Full domain compromise
- Access to sensitive internal files
- SYSTEM-level control of host

## Key Weaknesses
- Weak authentication controls
- Insecure services (FTP, POP3, RDP)
- Credential reuse
- Outdated OS vulnerabilities

## Outcome
Complete administrative takeover of Windows host.
