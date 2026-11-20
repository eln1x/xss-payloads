# Payloads

A collection of XSS (Cross-Site Scripting) payloads and exploit examples for security testing and educational purposes.

## Overview

This repository contains various HTML and PHP files demonstrating different XSS attack vectors and bypass techniques. These payloads are useful for:

- Security researchers and penetration testers
- Web application developers learning about XSS vulnerabilities
- Understanding various XSS evasion and obfuscation techniques
- Testing XSS filter implementations and WAF (Web Application Firewall) capabilities

## Contents

### HTML Payloads

| File | Purpose |
|------|---------|
| **onclick.html** | Simple onclick event handler XSS |
| **onload.html** | Onload event handler XSS |
| **onmouseover.html** | Onmouseover event handler XSS |
| **onkeydown.html** | Onkeydown event handler with absolute positioning overlay |
| **closingtag.html** | XSS using img tag with onerror and malformed closing tags |
| **protocol.html** | JavaScript protocol handler in href attribute |
| **broken_protocl.html** | Obfuscated javascript protocol with hex encoding |
| **broken_protocl2.html** | Path traversal and encoding bypass technique |
| **data.html** | Data URI scheme payloads with object tags |
| **data2.html** | Data URI with iframe and character encoding obfuscation |
| **redirect.html** | Redirection-based XSS payloads |
| **url.html** | URL-based XSS vectors |
| **stylexss.html** | XSS through CSS style attributes |
| **vbs.html** | VBScript-based XSS (legacy/IE specific) |
| **xss-dos.html** | XSS-based Denial of Service |

### PHP Files

| File | Purpose |
|------|---------|
| **eventfuzz.php** | Fuzzing tool for event-based XSS vectors |
| **after_tag.php** | XSS payloads using content after HTML tags |
| **after_tag_double.php** | Advanced after-tag XSS techniques |

## Disclaimer

⚠️ **IMPORTANT**: These payloads are provided for **educational and authorized security testing purposes only**. 

- **Do NOT** use these payloads against systems or applications you do not own or have explicit permission to test
- **Do NOT** use these for malicious purposes, unauthorized attacks, or illegal activities
- Users are responsible for ensuring they have proper authorization before testing any system
- Always follow applicable laws, regulations, and ethical guidelines

## Usage

These files can be used to:

1. Test web application security filters and input validation
2. Evaluate WAF effectiveness
3. Train and educate security professionals
4. Understand common XSS attack vectors

To use these payloads safely:

1. Set up a local testing environment or sandboxed server
2. Use an isolated browser or virtual machine
3. Ensure you have authorization to perform security testing
4. Document your findings responsibly

## Key XSS Vectors Covered

- **Event Handlers**: onclick, onload, onmouseover, onkeydown, onerror
- **Protocol Handlers**: javascript:, data: URIs
- **Encoding Techniques**: HTML entities, hex encoding, URL encoding, character padding
- **Tag Manipulation**: Broken closing tags, attribute injection
- **Data Schemes**: Base64 encoded payloads, text/html data URIs
- **DOM Manipulation**: Iframe injection, object tags
- **Obfuscation**: Null bytes, case variation, comment insertion

## References

- [OWASP XSS Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html)
- [CWE-79: Improper Neutralization of Input During Web Page Generation](https://cwe.mitre.org/data/definitions/79.html)
- [PortSwigger Web Security Academy - XSS](https://portswigger.net/web-security/cross-site-scripting)

## License

This repository is provided as-is for security research and educational purposes.

---

**Last Updated**: 2026-11-20
