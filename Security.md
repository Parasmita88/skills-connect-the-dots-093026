Here’s a clean `SECURITY.md` template you can drop into your repo:

```markdown
# Security Policy

## Supported Versions

We currently provide security updates for the following versions:

- `main` (active development)
- `v1.x` (bugfix and security patches)

Older versions may receive fixes on a best‑effort basis only.

---

## Reporting a Vulnerability

If you discover a security issue, please **do not** open a public GitHub issue.

Instead, contact us privately:

- Email: security@example.com
- Subject line: `[SECURITY] <short description>`

Please include:

- A clear description of the vulnerability
- Steps to reproduce
- Potential impact
- Any suggested mitigation (if you have one)

We aim to respond within **72 hours** and will keep you updated on:

- Triage status
- Planned fix timeline
- Coordinated disclosure details

---

## Disclosure Policy

- We prefer **coordinated disclosure**.
- We will acknowledge reporters (if you wish) in release notes or a Hall of Fame.
- We may request a short grace period before public disclosure to ship a fix.

---

## Scope

Security reports are in scope if they relate to:

- Code in this repository
- Configuration files and CI/CD workflows
- Documentation that, if followed, leads to insecure setups

Out of scope examples:

- Third‑party services not managed by this project
- Social engineering or physical attacks

---

## Security Best Practices

To reduce risk when using this project:

- Keep dependencies and this project updated to the latest version.
- Rotate credentials regularly and avoid hard‑coding secrets.
- Use least‑privilege access for any services or tokens.
```

You can tweak the email, response time, and supported versions to match your actual setup.
