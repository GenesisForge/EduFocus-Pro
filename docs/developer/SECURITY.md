# Security Policy

## Our Security Commitment

At Genesis Forge, we take the security of EduFocus Pro and the privacy of our users seriously. This document outlines our security practices and how to report security vulnerabilities.

---

## 🔒 Security Principles

### Privacy-First Architecture

EduFocus Pro is built with security at its core:

**No Data Transmission**
- All user data stays on the user's device
- No external network requests for user data
- No analytics or tracking endpoints
- No third-party scripts or resources

**Local Storage Only**
- Uses Chrome's secure storage API
- Encrypted at rest by the browser
- No server-side storage
- No cloud synchronization

**Minimal Permissions**
- Only requests necessary Chrome permissions
- No access to browsing history
- No access to other websites
- No access to personal information

---

## 🛡️ Supported Versions

We provide security updates for the following versions:

| Version | Supported          | Status |
| ------- | ------------------ | ------ |
| 3.5.x   | ✅ Yes             | Current stable release |
| 3.4.x   | ✅ Yes             | Security patches only |
| 3.3.x   | ⚠️ Limited         | Critical security patches only |
| < 3.3   | ❌ No              | Please upgrade |

**Recommendation:** Always use the latest version for the best security and features.

---

## 🚨 Reporting a Vulnerability

### How to Report

If you discover a security vulnerability in EduFocus Pro, please report it responsibly:

**Email:** edufocusbusiness@gmail.com  
**Subject:** SECURITY VULNERABILITY - [Brief Description]

**Please DO NOT:**
- Create public GitHub issues for security vulnerabilities
- Disclose the vulnerability publicly before we've addressed it
- Exploit the vulnerability beyond what's necessary to demonstrate it

### What to Include

Please provide as much information as possible:

**Required Information:**
- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact assessment
- Affected version(s)

**Helpful Additional Information:**
- Proof of concept code
- Screenshots or videos demonstrating the issue
- Suggested mitigation or fix (if you have one)
- Your assessment of severity (Low/Medium/High/Critical)

**Your Information:**
- Your name or pseudonym (for credit)
- Contact email
- Whether you want public acknowledgment

### Example Report

Subject: SECURITY VULNERABILITY - XSS in Note Title Field
Description:
Cross-site scripting vulnerability in the note title field allows
execution of arbitrary JavaScript when viewing notes.
Steps to Reproduce:

1. Create a new note
2. In the title field, enter: alert('XSS')
3. Save the note
4. Navigate to Notes tab
5. JavaScript executes when note is displayed

Impact:

* Could allow malicious scripts to access local storage
* Could manipulate or exfiltrate user notes
* Affects all users on version 3.5.3

Affected Version: 1.0.0
Browser: Chrome 120.0.6099.109
OS: Windows 11
Suggested Fix:
Sanitize all user input before rendering. Use textContent
instead of innerHTML for note titles.
Contact: security.researcher@example.com
Credit Name: Jane Doe
Public Acknowledgment: Yes please

---

## 📋 Vulnerability Assessment Criteria

### Severity Levels

**Critical (P0)**
- Remote code execution
- Data exfiltration to external servers
- Authentication bypass (if applicable)
- Mass data corruption or loss

**High (P1)**
- Cross-site scripting (XSS)
- Significant data corruption
- Privilege escalation
- Exposure of sensitive information

**Medium (P2)**
- Denial of service
- Minor data leakage
- Client-side validation bypass
- UI spoofing

**Low (P3)**
- Minor security improvements
- Best practice violations
- Non-exploitable issues

---

## ⏱️ Response Timeline

### Our Commitment

**Initial Response:**
- Critical: Within 24 hours
- High: Within 48 hours
- Medium: Within 5 business days
- Low: Within 10 business days

**Investigation & Fix:**
- Critical: Fix deployed within 7 days
- High: Fix deployed within 14 days
- Medium: Fix deployed within 30 days
- Low: Fix deployed in next regular update

**Disclosure:**
- We will coordinate disclosure with you
- Minimum 90 days before public disclosure
- Credit given to reporter (if desired)
- Public advisory published after fix is deployed

### Process

1. **Report Received** - We acknowledge your report
2. **Validation** - We reproduce and validate the vulnerability
3. **Assessment** - We assess severity and impact
4. **Development** - We develop and test a fix
5. **Deployment** - We deploy the fix to all users
6. **Disclosure** - We publicly disclose (coordinated with reporter)
7. **Recognition** - We credit the reporter (if desired)

---

## 🏆 Security Researcher Recognition

### Hall of Fame

We maintain a security researcher hall of fame to acknowledge those who help keep EduFocus Pro secure.

**Current Contributors:**
*(None yet - be the first!)*

### Credit Policy

**We offer:**
- Public acknowledgment in our security advisories
- Credit in release notes
- Listing in our security hall of fame (README)
- Our sincere gratitude

**We currently do not offer:**
- Monetary bug bounties (may change in the future)
- Merchandise or swag
- Financial compensation

---

## 🔐 Security Best Practices for Users

### Protecting Your Data

**Device Security:**
- Keep Chrome updated to the latest version
- Use strong device passwords/biometrics
- Enable full disk encryption
- Don't share your device with untrusted users

**Extension Security:**
- Only install EduFocus Pro from the official Chrome Web Store
- Verify the publisher is "Genesis Forge"
- Don't install modified versions from third parties
- Report suspicious extension behavior immediately

**Data Backups:**
- Regularly export your data (Settings → Export All Data)
- Store backups in a secure location
- Test backup restoration periodically
- Keep multiple backup versions

**Safe Browsing:**
- Don't enter sensitive information in notes if device is shared
- Log out of shared computers completely
- Clear browser data if using a public computer
- Be cautious of phishing attempts

---

## 🔍 Security Features

### What We Do to Protect You

**Content Security Policy (CSP)**
- Prevents loading of external scripts
- Blocks inline JavaScript execution
- Restricts resource loading to extension only

**Input Sanitization**
- All user input is sanitized before storage
- HTML entities are escaped
- Script injection is prevented

**Secure Storage**
- Uses Chrome's secure storage API
- Data encrypted at rest by browser
- No plaintext credential storage

**Minimal Attack Surface**
- No server-side components
- No network requests for user data
- No third-party dependencies for core functionality
- Open about our architecture

**Regular Updates**
- Security patches deployed quickly
- Users notified of critical updates
- Automatic updates through Chrome Web Store

---

## 🚫 Out of Scope

The following are **not** considered security vulnerabilities:

**By Design:**
- Local storage is accessible if device is compromised (use device security)
- Data loss if browser data is cleared without backup (user responsibility)
- Performance issues or crashes (report as bugs, not security)

**Social Engineering:**
- Phishing attacks impersonating Genesis Forge
- Social engineering to obtain exported data from users
- Tricking users into installing malicious extensions

**Third-Party Issues:**
- Vulnerabilities in Chrome browser itself
- OS-level security issues
- Hardware vulnerabilities

**Already Known:**
- Issues listed in our public issue tracker
- Issues in unsupported versions (< 3.3)

Please report these through normal support channels (edufocusbusiness@gmail.com) rather than as security vulnerabilities.

---

## 📜 Security Advisories

### Past Advisories

*(None published yet)*

### Notification Channels

We publish security advisories through:
- Release notes in Chrome Web Store
- CHANGELOG.md in our repository
- Email to institutional users (upon request)
- README.md security section

To receive security notifications for institutional deployment, email edufocusbusiness@gmail.com with "Security Notifications" in the subject line.

---

## 🔗 Additional Resources

### Security-Related Documentation

- [Privacy Policy](../legal/privacy/privacy_en.md) - Our privacy practices
- [Terms of Service](../user/TERMS_OF_SERVICE.md) - Legal terms and liability
- [License](../legal/LICENSE) - Software license and restrictions

### External Resources

- [Chrome Extension Security Best Practices](https://developer.chrome.com/docs/extensions/mv3/security/)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [CWE/SANS Top 25](https://www.sans.org/top25-software-errors/)

---

## 📞 Security Contact

**For security vulnerabilities only:**  
Email: edufocusbusiness@gmail.com  
Subject: SECURITY VULNERABILITY - [Brief Description]

**For other security questions:**  
Email: edufocusbusiness@gmail.com  
Subject: Security Question

**Response Time:** Within 24 hours for critical issues, within 7 business days for questions.

---

## 🙏 Thank You

Thank you for helping keep EduFocus Pro and its users safe. Responsible disclosure of security vulnerabilities helps us protect our community and maintain trust.

Every security report, regardless of severity, is valuable and appreciated.

---

**Last Updated:** October 2025  
**Version:** 1.0.0  
**Security Contact:** edufocusbusiness@gmail.com

Copyright © 2025 Genesis Forge. All Rights Reserved.  
EduFocus Pro - Privacy-First Education Technology
