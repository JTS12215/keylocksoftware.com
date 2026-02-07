Security Policy
Our Commitment to Security
At KeyLock Password Manager, user security is our highest priority. We follow a "Zero-Knowledge" and "Local-First" architecture to ensure that only the user has access to their sensitive data. We appreciate the work of security researchers and are committed to working with the community to resolve vulnerabilities.

Reporting a Vulnerability
Please do NOT open a public GitHub Issue for a security vulnerability. Public disclosure of a vulnerability before a patch is available puts all users at risk.

If you believe you have found a security vulnerability in KeyLock, please follow these steps:

Email Us: Send a detailed report to keylock.app@gmail.com

Encrypt the Report: (Optional but recommended) If you have a PGP key, please use it to encrypt your message.

Include Details:

A description of the vulnerability and its potential impact.

Step-by-step instructions to reproduce the issue.

Any Proof-of-Concept (PoC) code or screenshots.

The version of KeyLock (e.g., v26.02.4) and the OS you are using.

Our Response Timeline
Acknowledgement: You will receive an automated or manual acknowledgement.

Status Update: We will provide a status update or may request more information.

Resolution: We aim to patch critical vulnerabilities as quickly as possible and will update you accordingly.

Guidelines for Researchers (Safe Harbor)
To encourage responsible disclosure, we promise not to pursue legal action against researchers who:

Protect User Data: Do not attempt to access, modify, or delete any data that does not belong to you.

Avoid Disruptive Testing: Do not perform Denial of Service (DoS) attacks or high-intensity automated scans that could degrade the application's performance.

Maintain Confidentiality: Give us a reasonable amount of time (Coordinated Vulnerability Disclosure) to fix the bug before sharing details publicly. We recommend a 90-day window.

Stay in Scope: Focus your research on the KeyLock application code and encryption logic.

Scope
In-Scope
Bypassing the Master Password or database encryption.

Memory leaks that expose plain-text passwords.

Vulnerabilities in the import/export or backup logic.

Flaws in the PBKDF2 key derivation implementation.

Out-of-Scope
Vulnerabilities in third-party services (e.g., Dropbox, OneDrive sync).

Physical attacks (e.g., someone stealing the computer while it is unlocked).

Attacks requiring administrative access to the machine (e.g., keyloggers already installed by malware).

Acknowledgments
We value your time and expertise. If you report a valid, previously unknown vulnerability, we will (with your permission) credit you in our Release Notes and the About section of the application.
