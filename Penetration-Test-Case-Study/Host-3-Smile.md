# Host 3 – Web Application Compromise

## Summary
WordPress system compromised via SQL injection leading to full root access.

## Key Attack Chain
- Directory enumeration
- WordPress plugin enumeration
- SQL injection via vulnerable plugin
- Database credential extraction
- WordPress login compromise
- SSH access via reused credentials
- Privilege escalation via SUID binary misuse

## Impact
- Full server compromise
- Database exposure
- Root access achieved

## Key Weaknesses
- SQL injection vulnerability
- Weak password storage
- Credential reuse
- Misconfigured SUID binaries

## Outcome
Full system compromise achieved.
