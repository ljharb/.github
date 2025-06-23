# Incident Response Plan

## Reporting a Vulnerability

We take the security of this package very seriously. If you believe you’ve found a security vulnerability, please inform us responsibly through coordinated disclosure.

### How to Report

> **Do not** report security vulnerabilities through public GitHub issues, discussions, or social media.

Instead, please use one of these secure channels:

1. **GitHub Security Advisories**
   Use the **Report a vulnerability** button in the Security tab of the repository.

2. **Email**
   Follow the posted [Security Policy](https://github.com/ljharb/.github/security/policy).

### What to Include

**Required Information:**
- Brief description of the vulnerability type
- Affected version(s) and components
- Steps to reproduce the issue
- Impact assessment (what an attacker could achieve)

**Helpful Additional Details:**
- Full paths of affected source files
- Specific commit or branch where the issue exists
- Required configuration to reproduce
- Proof-of-concept code (if available)
- Suggested mitigation or fix

## Our Response Process

**Timeline Commitments:**
- **Initial acknowledgment**: Within 24 hours
- **Detailed response**: Within 3 business days
- **Status updates**: Every 7 days until resolved
- **Resolution target**: 90 days for most issues

**What We’ll Do:**
1. Acknowledge your report and assign a tracking ID
2. Assess the vulnerability and determine severity
3. Develop and test a fix
4. Coordinate disclosure timeline with you
5. Release a security update and publish an advisory
6. Credit you in our security advisory (if desired)

## Disclosure Policy

- **Coordinated disclosure**: We’ll work with you on timing
- **Typical timeline**: 90 days from report to public disclosure
- **Early disclosure**: If actively exploited
- **Delayed disclosure**: For complex issues

## Scope

**In Scope:**
- This package (all supported versions)
- Official documentation and examples
- Parsing and stringification APIs
- Dependencies with direct security implications

**Out of Scope:**
- Third-party forks or mirrors
- Browser-only polyfills
- Social engineering or physical attacks
- Theoretical vulnerabilities without practical exploitation

## Security Measures

**Our Commitments:**
- Regular vulnerability scanning via `npm audit`
- Automated security checks in CI/CD (GitHub Actions)
- Secure coding practices and mandatory code review
- Prompt patch releases for critical issues

**User Responsibilities:**
- Keep the package updated
- Monitor dependency vulnerabilities
- Follow secure configuration guidelines for query strings

## Legal Safe Harbor

**We will NOT:**
- Initiate legal action
- Contact law enforcement
- Suspend or terminate your access

**You must:**
- Only test against your own installations
- Not access, modify, or delete user data
- Not degrade service availability
- Not publicly disclose before coordinated disclosure
- Act in good faith

## Recognition

- **Advisory Credits**: Credit in GitHub Security Advisories (unless anonymous)

## Security Updates

**Stay Informed:**
- Subscribe to npm updates for this package
- Enable GitHub Security Advisory notifications

**Update Process:**
- Patch releases (e.g., 6.14.0 → 6.14.1)
- Out-of-band releases for critical issues
- Advisories via GitHub Security Advisories

## Contact Information

- **Security reports**: [Security policy](https://github.com/ljharb/.github/security/policy)
- **General inquiries**: GitHub Discussions or Issues

