# Security Policy

At Chetan, we prioritize system security. Despite our efforts, vulnerabilities may exist.

If you discover a vulnerability, please inform us so we can address it promptly. Your assistance helps us protect our clients and systems.

### Out of Scope Vulnerabilities:
- Clickjacking on pages with no sensitive actions
- Unauthenticated/logout/login CSRF
- Attacks requiring MITM or physical access
- Social engineering attacks
- Activities leading to service disruption (DoS)
- Content spoofing and text injection without an attack vector
- Email spoofing
- Missing DNSSEC, CAA, CSP headers
- Lack of Secure or HTTP only flag on non-sensitive cookies
- Deadlinks
- User enumeration

### Testing Guidelines:
- Do not run automated scanners on other customer projects. Obtain permission and notify us at security@mrchetan.com before running scanners on Chetan projects.
- Avoid actions that may harm Chetan or its customers.
- Do not access, modify, or delete data that does not belong to you.
- Do not exploit vulnerabilities by downloading more data than necessary or modifying/deleting others' data.

### Reporting Guidelines:
- Provide sufficient information to reproduce the problem for a quick resolution.
- Include your name and contact information for follow-up.
- Attach screenshots, videos, or logs if possible.

### Disclosure Guidelines:
- Do not disclose the problem until we have addressed it and informed affected customers.
- Share a draft of any public research about Chetan with us at least 30 days before publication. Exclude:
  - Data about Chetan customer projects
  - Chetan customers' data
  - Information about Chetan employees, contractors, or partners

### Our Commitment:
- We will respond within 5 business days with an evaluation and resolution date.
- If you follow the above instructions, we will not take legal action against you.
- We will handle your report confidentially and not share your personal details without permission.
- We will keep you informed of progress.
- We will credit you as the discoverer of the problem (unless you prefer otherwise).

We aim to resolve issues quickly and involve you in the publication of the problem after resolution.

## Reporting a Vulnerability

- Email [security@mrchetan.com](mailto:security@mrchetan.com) with details of the vulnerability. We will respond promptly. Do not publicly disclose vulnerabilities until resolved. If you do not receive a response within 48 hours, send a follow-up email.
- Report via GitHub by selecting "Report a security vulnerability" when creating an issue.

For significant vulnerabilities, contact us immediately.

## Security Updates

We will notify users of security updates through our release notes.

Thank you for helping keep our project secure!
