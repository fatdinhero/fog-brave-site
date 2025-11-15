# Security Policy

## Supported Versions

We are committed to maintaining the security of FOG.brave. Currently supported version:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |

## Reporting a Vulnerability

We take security seriously. If you discover a security vulnerability in FOG.brave, please report it responsibly.

### How to Report

**Please DO NOT create a public GitHub issue for security vulnerabilities.**

Instead, please report security issues through one of the following channels:

1. **GitHub Security Advisories** (Preferred)
   - Go to the [Security tab](https://github.com/fatdinhero/fog-brave-site/security) of this repository
   - Click "Report a vulnerability"

2. **Email**
   - Contact the maintainers directly through GitHub

3. **Private Message**
   - Discord: https://discord.gg/fogbrave (DM moderators)
   - Telegram: https://t.me/fogbrave (DM admins)

### What to Include

When reporting a vulnerability, please include:

- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact
- Suggested fix (if any)
- Your contact information (optional)

### Response Timeline

- **Initial Response**: Within 48 hours
- **Assessment**: Within 1 week
- **Fix Development**: Depends on severity
- **Public Disclosure**: After fix is deployed

## Security Best Practices

### For Users

When donating through FOG.brave:

1. **Verify Wallet Addresses**: Always double-check wallet addresses before sending funds
2. **Use Secure Connections**: Only access the site via HTTPS
3. **Wallet Security**: Never share your private keys or seed phrases
4. **Browser Extensions**: Use official wallet extensions from trusted sources
5. **Phishing Protection**: Verify you're on the official fog.brave domain

### For Contributors

When contributing to the project:

1. **Dependencies**: Keep all dependencies up to date
2. **Code Review**: All changes must be reviewed before merging
3. **Sensitive Data**: Never commit private keys, passwords, or API keys
4. **XSS Prevention**: Sanitize all user inputs
5. **HTTPS Only**: Always use HTTPS for external resources

## Known Security Considerations

### Client-Side Wallet Integration

FOG.brave uses client-side Web3 wallet integration:

- No private keys are ever stored or transmitted
- Wallet connections are handled by browser extensions
- All transactions require explicit user approval
- No centralized backend stores sensitive data

### Smart Contract Interactions

Currently, FOG.brave displays static wallet addresses. Future smart contract integrations will:

- Undergo thorough security audits
- Follow best practices for Solidity development
- Use established, audited libraries
- Implement multi-signature controls

## Security Updates

Security updates will be:

- Published through GitHub Security Advisories
- Announced in our community channels
- Documented in release notes
- Deployed as quickly as possible

## Responsible Disclosure

We kindly ask security researchers to:

- Allow reasonable time for us to fix issues before public disclosure
- Not exploit the vulnerability beyond what's necessary to demonstrate it
- Not access or modify user data without permission
- Act in good faith to avoid privacy violations

## Recognition

We appreciate security researchers who help keep FOG.brave safe:

- Responsible disclosures will be acknowledged (with permission)
- Significant findings may be recognized in our README
- We're open to discussing bug bounties for critical issues

## Contact

For security concerns that don't require immediate attention:
- GitHub: https://github.com/fatdinhero/fog-brave-site
- Community: https://discord.gg/fogbrave

Thank you for helping keep FOG.brave and its users safe! 🙏

---

**FOG.brave** - *Friends of God* | Secure Web3 Charity Platform
