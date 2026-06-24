# Security Policy

## Supported Versions

We actively monitor and patch the core discovery engine. Security updates and cryptographic rule corrections are backported according to the following matrix:

| Version | Supported |
| :--- | :--- |
| v1.0.x | Active Support |
| < v1.0.0 | Unsupported (Alpha/Beta Releases) |

---

## Reporting a Vulnerability

**Please do not open public GitHub issues for suspected security vulnerabilities.** If you discover a security defect, a bypass in our air-gapped isolation boundaries, or a critical flaw in how our rules parse PQC parameters, please report it through our responsible disclosure channel:

* **Email:** saisravan@gmail.com (or your organization's security monitoring alias)
* **Response Window:** You will receive an initial automated acknowledgment within 24 hours, followed by a formal validation assessment from our maintainers within 72 hours.

### Please Include:
1. A detailed description of the vulnerability or parsing exploit.
2. Steps to reproduce the issue (including any mock code fixtures or configuration templates used).
3. Potential impact on generated CBOM accuracy or localized runtime integrity.

---

## Disclosure Process

When a valid vulnerability is reported:
1. We will coordinate a private fix inside an isolated development branch.
2. A patched release tag will be prepared.
3. We will work with the reporter to issue a public advisory alongside the release, ensuring proper attribution for your discovery.
