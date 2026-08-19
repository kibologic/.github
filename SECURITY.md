# Security Policy

This security policy applies to **all repositories** under the [Kibologic organization](https://github.com/kibologic).

---

## Supported Versions

We patch security vulnerabilities in the **latest minor version** of each package. Older versions are not actively maintained.

| Status | Supported |
|---|---|
| Latest release | ✅ Yes |
| Previous major | ⚠️ Critical only |
| Older versions | ❌ No |

---

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

If you believe you've found a security vulnerability in any Kibologic project, please disclose it responsibly using **GitHub's private vulnerability reporting**:

### How to Report

1. Go to the affected repository's **Security** tab.
2. Select **Report a vulnerability**.
3. Include:
   - Affected repository and version
   - A clear description of the vulnerability
   - Steps to reproduce
   - Any relevant code snippets or PoC

This opens a private advisory visible only to the reporter and the repository maintainers — nothing is exposed publicly until a fix is ready.

---

## Our Commitment

- We will keep you informed as we investigate and fix the issue.
- We will credit responsible disclosures in release notes (unless you prefer anonymity).
- We will not take legal action against researchers acting in good faith.

---

## Scope

All packages and applications published under:
- `@swissjs/*` (e.g., `@swissjs/core`, `@swissjs/compiler`)
- `@sws/*` (e.g., `@sws/identity`, `@sws/web-storage`)
- Kibologic application repositories (e.g., `swiss-erp`, `swite`)

---

## Out of Scope

- Social engineering attacks
- Denial of service attacks
- Issues in third-party dependencies (report directly to those maintainers)

---

## Contact

For security matters, use GitHub's private vulnerability reporting (see above) on the relevant repository.

For general questions, open a GitHub Discussion or Issue in the relevant repo.
