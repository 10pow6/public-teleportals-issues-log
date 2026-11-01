# Security Policy

We take the security of TelePortals and our users seriously. Thank you for helping keep the platform safe.

## ⚠️ Do not report security issues publicly

**Please do not open a public GitHub issue, discussion, or pull request for a security vulnerability.** Public reports expose the issue to everyone before we can fix it, putting users and their data at risk.

This includes (but is not limited to):

- Authentication, login, or session problems
- Account takeover or impersonation
- Exposed secrets, API keys, tokens, or credentials
- **Integration API** abuse or authorization bypass
- Ways to create, transfer, or spend TP6 you shouldn't have
- Bypassing payment, quotas, or tier limits
- Accessing, enumerating, or exposing other users' URLs, analytics, or account data
- Open redirects or abuse of the link‑shortening service
- Anything that lets you act as another user or the system

## ✅ How to report privately

Use GitHub's private vulnerability reporting:

### [🔒 Report a vulnerability →](https://github.com/10pow6/public-teleportals-issues-log/security/advisories/new)

You can also open this repository's **Security** tab and click **Report a vulnerability**. Only you and our team can see the report. You need a GitHub account.

**No GitHub account?** Reach us through our community **Discord** (linked from the [TelePortals site](https://tp.land)) and **send a direct message to a staff/admin member**. Let them know you have a security report — please **do not post the details in any public channel**. A staff member will follow up with you privately.

Every report should include:

- A clear description of the issue and its impact
- Step‑by‑step instructions to reproduce it
- Any proof‑of‑concept, screenshots, or logs (redact your own credentials)
- Your account email or handle (so we can credit you, if you'd like)

**Reports without clear steps to reproduce and a real impact on our users will be closed without a response.**

## 🚫 Out of scope

These aren't vulnerabilities for us. Reports about them will be closed without a response:

- Output from automated scanners or tools without a working proof of concept
- Missing "best practice" HTTP headers or cookie flags (CSP, HSTS, X‑Frame‑Options, etc.) without a demonstrated exploit
- Email configuration findings (SPF, DKIM, DMARC)
- Clickjacking on pages with no sensitive actions
- Self‑XSS, or anything that requires the victim to paste code into their own browser
- CSRF on logout or other actions with no security impact
- Software version numbers, banners, or descriptive error messages
- Missing rate limits on actions with no security impact
- Denial of service, load testing, or flooding
- Social engineering or phishing of our staff or users
- Attacks that require physical access to a device or an already‑compromised account
- Bugs in third‑party services we use, unless you show impact on our users

## What to expect

- We'll acknowledge your report as quickly as we can.
- We'll investigate, keep you updated, and let you know when it's resolved.
- **We don't run a paid bug bounty.** Valid reports are credited in the published advisory, if you'd like.
- Please give us a reasonable window to fix the issue before sharing it publicly.

## Responsible disclosure

Please act in good faith:

- **Don't** access, modify, or delete data that isn't yours.
- **Don't** degrade or disrupt the service for other users.
- **Don't** use the vulnerability beyond what's needed to demonstrate it.

We're grateful to researchers and users who report responsibly, and we're happy to credit you for valid reports. 🙏
