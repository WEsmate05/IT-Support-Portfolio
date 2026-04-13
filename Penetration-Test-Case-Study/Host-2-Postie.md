# Host 2 – Linux/Email Server Compromise

## Summary
Access gained through exposed services and credential reuse, leading to root access.

## Key Attack Chain
- Anonymous FTP access
- Credential extraction from archive file
- Admin portal compromise
- Email-based password reset abuse
- SSH login via exposed credentials
- Privilege escalation via sudo misconfiguration (vim)

## Impact
- Full root access obtained
- Access to user mailboxes
- System-wide compromise

## Key Weaknesses
- Anonymous FTP enabled
- Weak password recovery process
- Email credential exposure
- Poor sudo configuration

## Outcome
Root-level compromise achieved.
