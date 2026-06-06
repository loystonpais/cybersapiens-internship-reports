# Cybersapiens Internship - Security Research & Penetration Testing Reports

This is the collection of reports compiled during my Cybersapiens 6 months internship.

This repository documents hands-on security training covering the core pillars of modern cybersecurity assessments: **Web Application Security**, **API Penetration Testing**, and **Mobile Application Security** (collectively referred to as **WAM**), along with **Bug Bounty Roadmaps & Reconnaissance**.

---

## 🛡️ Internship Overview & Core Curriculum (WAM)

The curriculum is structured around deep theoretical understanding and practical security testing methodologies across the following tracks:

### 1. Web Application Security
Web security research focuses on client-side and server-side vulnerabilities, understanding the mechanics of attacks, and mitigation strategies. Key areas analyzed include:
*   **Vulnerable Session Management**: Session Fixation, Session Hijacking, and secure cookie attributes.
*   **Injection Attacks**: SQL Injection (SQLi), XML External Entity (XXE) Injection, Cross-Site Scripting (XSS), and HTML Injection.
*   **Server-Side Flaws**: Server-Side Request Forgery (SSRF), File Path Traversal, Local/Remote File Inclusion (LFI/RFI), and Remote Code Execution (RCE) via Command Injection.
*   **Modern Auth & Browser Controls**: JSON Web Token (JWT) hacking, Cross-Origin Resource Sharing (CORS) misconfigurations, and HTTP Strict Transport Security (HSTS).

### 2. API Penetration Testing
API penetration testing directly analyzes endpoints and request/response structures rather than user interfaces. This track covers the **OWASP API Security Top 10** vulnerabilities:
*   **Authorization Flaws**: Broken Object Level Authorization (BOLA), Broken Object Property Level Authorization (BOPLA), and Broken Function Level Authorization (BFLA).
*   **Rate Limiting & Resources**: Unrestricted Resource Consumption and Unrestricted Access to Sensitive Business Flows.
*   **Configuration & Lifecycle**: Security Misconfigurations, Improper Inventory Management (outdated/shadow APIs), and Unsafe Consumption of APIs (trusting third-party integration data blindly).

### 3. Mobile Application Security
Mobile application security focuses on assessing application binaries and runtime behaviors for iOS and Android environments:
*   **Analysis Methods**: Static analysis (decompiling IPA/APK packages, reviewing manifest/plist configurations, automated tools like MobSF) and Dynamic analysis (monitoring runtime network traffic, memory inspection, and filesystem changes).
*   **Security Protections & Bypasses**: Bypassing SSL Pinning using injection frameworks (Frida, Objection), setting up testing environments (jailbreaking iOS devices, Xcode configurations), and reversing application binaries.
*   **Mobile Risks (OWASP Mobile Top 10)**: Insecure Data Storage, Insufficient Cryptography, Insecure Communication, Code Tampering, and Reverse Engineering.
