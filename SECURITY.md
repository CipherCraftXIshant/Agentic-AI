# Security Policy

We take the security of our project seriously. If you believe you have found a security vulnerability, please follow the guidelines below to report it to us responsibly.

---

## Supported Versions

Only the following versions of this project currently receive security updates and bug fixes:

| Version | Supported          | Notes                          |
| ------- | ------------------ | ------------------------------ |
| 2.x.x   | :white_check_mark: | Active release track           |
| 1.9.x   | :white_check_mark: | Security patches only          |
| < 1.9   | :x:                | End-of-life; please upgrade    |

---

## Reporting a Vulnerability

**Please do NOT open a public GitHub issue for security vulnerabilities.**

If you discover a security issue or vulnerability:

1. **Email:** Send your findings to `security@yourdomain.com` (or use GitHub's **Private Vulnerability Reporting** tab under Security).
2. **Details:** Include as much of the following information as possible:
   - Description of the vulnerability and its potential impact.
   - Steps to reproduce the issue (including sample code or payload, if applicable).
   - Affected version(s) and environment setup.
   - Any suggested mitigations or patches.

### Encryption (Optional)
If you wish to encrypt your message, you can find our PGP key at `https://yourdomain.com/pgp-key.asc` (Fingerprint: `0000 0000 0000 0000`).

---

## Our Response Process

When we receive a vulnerability report:

- **Acknowledgement:** We will acknowledge receipt of your report within **48 hours**.
- **Assessment:** We will investigate and confirm the issue within **5 business days**.
- **Updates:** We will keep you updated at least once a week as we work on a fix.
- **Fix & Patch:** Once a patch is ready, we will release an updated version and announce the advisory.

---

## Disclosure & Recognition

- **Coordinated Disclosure:** We ask that you give us reasonable time (up to 90 days) to address the issue before making it public.
- **Credit:** We are happy to credit security researchers in our release notes and Security Hall of Fame (unless you prefer to remain anonymous).

---

## Out of Scope

The following types of reports are generally considered out of scope:
- Social engineering, phishing, or physical security testing.
- Denial of Service (DoS/DDoS) attacks against project infrastructure.
- Vulnerabilities generated purely by automated scanners without proof-of-concept.
