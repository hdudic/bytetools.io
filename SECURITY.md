# Security Policy

## Our Commitment to Security

ByteTools is built with privacy and security as core principles. All tools run 100% client-side in your browser with zero data collection, zero server-side processing, and zero data transmission.

We take security seriously and appreciate the security research community's efforts to help keep ByteTools and its users safe.

---

## Supported Versions

We currently support the latest deployed version of ByteTools.io with security updates.

| Version | Supported          |
| ------- | ------------------ |
| Latest (main branch) | :white_check_mark: |
| Older commits | :x: |

---

## Reporting a Vulnerability

If you discover a security vulnerability in ByteTools, please report it responsibly. We appreciate your efforts to disclose the issue in a coordinated manner.

### How to Report

**Preferred Method:** Create a [Security Advisory](https://github.com/hdudic/bytetools.io/security/advisories/new)

**Alternative Methods:**
- Email: Contact us via [bytetools.io](https://bytetools.io) contact form
- Security.txt: See our [security.txt](https://bytetools.io/.well-known/security.txt) for contact information

### What to Include

Please include the following in your report:
- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact and severity assessment
- Any proof-of-concept code (if applicable)
- Your contact information for follow-up

### What to Expect

- **Acknowledgment:** We will acknowledge receipt of your report within 48 hours
- **Initial Assessment:** We will provide an initial assessment within 7 days
- **Updates:** We will keep you informed of our progress
- **Resolution:** We aim to resolve critical issues within 30 days
- **Credit:** With your permission, we will credit you in our security acknowledgments

---

## Security Considerations

### Client-Side Architecture

ByteTools processes all data entirely in your browser:
- **No Server Processing:** Your data never touches our servers
- **No Data Collection:** We don't log, store, or transmit your data
- **No Network Requests:** Tools work offline after initial page load
- **No Third-Party APIs:** All processing happens locally

### What We Can Control

- **Code Security:** We actively maintain secure code practices
- **Dependency Updates:** We regularly update dependencies to patch vulnerabilities
- **HTTPS Enforcement:** All traffic uses HTTPS with HSTS preload
- **Content Security Policy:** Strict CSP headers prevent XSS attacks

### What We Cannot Control

- **Browser Security:** Security depends on your browser's sandboxing and isolation
- **Browser Extensions:** Malicious extensions could intercept data
- **Local Environment:** Compromised devices may expose data
- **Third-Party Libraries:** We rely on open-source libraries (audited regularly)

---

## Scope

### In Scope

Security issues related to:
- Cross-Site Scripting (XSS) vulnerabilities
- Code injection vulnerabilities
- Authentication or session management issues (if applicable)
- Dependency vulnerabilities with available exploits
- Security misconfigurations
- Information disclosure vulnerabilities
- Client-side security bypass techniques

### Out of Scope

The following are generally **not** considered security vulnerabilities:
- Vulnerabilities in outdated browsers (we support modern browsers only)
- Social engineering attacks
- Physical access to user devices
- Denial of Service (DoS) attacks against our static site
- Issues requiring browser extensions or modifications
- Theoretical vulnerabilities without proof of exploitability
- Vulnerabilities in third-party services we link to

---

## Security Features

### Current Protections

- ✅ **HTTPS Only:** Enforced via HSTS with preload
- ✅ **Content Security Policy:** Strict CSP headers
- ✅ **Client-Side Processing:** Zero server-side data handling
- ✅ **No Cookies:** No session cookies or tracking cookies
- ✅ **No Analytics PII:** Analytics are anonymous only
- ✅ **Regular Updates:** Dependencies reviewed and updated regularly
- ✅ **Static Site:** No backend attack surface

### Privacy Protections

- 🔒 No user accounts or authentication required
- 🔒 No data collection or logging
- 🔒 No third-party API calls from tools
- 🔒 Works completely offline after first load
- 🔒 Open source for transparency and auditing

---

## Responsible Disclosure

We follow responsible disclosure principles:

1. **Private Disclosure:** Report vulnerabilities privately first
2. **Coordination:** We will work with you to understand and fix the issue
3. **Public Disclosure:** We will coordinate public disclosure timing with you
4. **Credit:** We will credit researchers (with permission) in our security advisories

**Please do not:**
- Publicly disclose the vulnerability before we've had a chance to fix it
- Exploit the vulnerability beyond what's necessary to demonstrate it
- Access, modify, or delete other users' data (though our architecture makes this nearly impossible)
- Perform attacks that could harm our service availability

---

## Security Acknowledgments

We appreciate the security research community. Researchers who responsibly disclose vulnerabilities will be credited here (with permission):

_No vulnerabilities reported yet._

---

## Contact

- **Security Advisories:** [Create Advisory](https://github.com/hdudic/bytetools.io/security/advisories/new)
- **Security.txt:** [View security.txt](https://bytetools.io/.well-known/security.txt)
- **General Contact:** [ByteTools.io](https://bytetools.io)

---

## Additional Resources

- **Privacy Policy:** All tools are client-side with zero data collection
- **Open Source:** [GitHub Repository](https://github.com/hdudic/bytetools.io)
- **MIT License:** [View License](https://github.com/hdudic/bytetools.io/blob/main/LICENSE)

---

_Last Updated: November 27, 2025_
