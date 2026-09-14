# Security Policy

## Reporting Security Vulnerabilities

If you discover a security vulnerability in GCDWebServer, please email us at **security@gcdwebserver.local** instead of using the public issue tracker.

### Guidelines for Reporting:
- **Do not** open public issues for security vulnerabilities
- Provide detailed information about the vulnerability
- Include proof-of-concept code if possible
- Allow us 90 days to address the issue before public disclosure

## Security Best Practices

### For Users:
- Keep GCDWebServer updated to the latest version
- Review security advisories regularly
- Use HTTPS/TLS for all connections
- Implement proper authentication and authorization
- Monitor access logs for suspicious activity

### For Contributors:
- Follow secure coding practices
- Run security scans before submitting PRs
- Never commit sensitive information (keys, passwords, tokens)
- Use signed commits when possible
- Report security issues privately

## Security Features

### Enabled Security Measures:
- ✅ Branch protection on `master`
- ✅ Required pull request reviews
- ✅ Status checks required
- ✅ Dependabot for dependency scanning
- ✅ Secret scanning enabled
- ✅ Code scanning (SAST)
- ✅ Signed commits encouraged

## Vulnerability Disclosure

We follow responsible disclosure practices:
1. Initial contact and acknowledgment (24-48 hours)
2. Investigation and fix development (30-45 days)
3. Security advisory publication
4. Public release with patched version

## Version Support

| Version | Status | Security Updates |
|---------|--------|------------------|
| Latest  | Active | Receiving updates |
| n-1     | Active | Critical only |
| Older   | EOL    | Not supported |

## Security Contacts

- **Security Team:** security@gcdwebserver.local
- **GitHub Security Advisory:** Use GitHub's private vulnerability reporting

---

**Last Updated:** 2026-09-14