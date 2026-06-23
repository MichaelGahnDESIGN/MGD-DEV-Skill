# Security Policy

## Reporting Security Issues

**Please DO NOT open a public GitHub issue for security vulnerabilities.**

Instead, email: **[Anfrage@Michael-Gahn.de](mailto:Anfrage@Michael-Gahn.de)** with:
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if you have one)

We will respond within **48 hours** and work with you on a fix.

## Supported Versions

| Version | Status | Support |
|---------|--------|---------|
| 1.1.x | ✅ Latest | Actively supported |
| 1.0.x | ⚠️ Previous | Security fixes only |
| < 1.0 | ❌ Legacy | No longer supported |

## Security Practices

- **No sensitive data stored** — API keys, tokens, or passwords are never stored in scripts or configuration files
- **Input validation** — All scripts validate input before execution
- **Pre-push hooks** — Prevent accidental commits of secrets (`.env`, credentials)
- **Regular audits** — Dependencies are checked for known vulnerabilities
- **Transparency** — Security issues are disclosed responsibly after fixes are released

## Best Practices for Users

- Never commit `.env` files or credentials to version control
- Use environment variables for sensitive data
- Keep Claude Code and other tools updated
- Report suspicious behavior immediately

---

Thank you for helping us keep this project secure!
