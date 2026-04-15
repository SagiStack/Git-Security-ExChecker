#  Privacy Policy | Security ExChecker

**Last Updated:** April 15, 2026

At **Security ExChecker**, we believe that security tools should be the most transparent applications on your machine. This Privacy Policy outlines our commitment to your data security and privacy while using our GitHub extension.

---

###  1. Data Collection & Zero-Tracking
Security ExChecker is built on a **Privacy-First** architecture:
*   **No Remote Tracking:** We do not collect, monitor, or transmit your browsing history or repository interactions.
*   **No Analytics:** There are no trackers, cookies, or telemetry scripts included in this extension.
*   **Zero Data Sharing:** We do not sell, trade, or share any user metrics or identifiers with third parties.

###  2. GitHub API Key Management
To provide deep behavioral analysis, the extension allows users to input a GitHub Personal Access Token (PAT):
*   **Local Storage Only:** Your token is stored exclusively on your local device using `chrome.storage.local`.
*   **Secured Origin:** Requests are authenticated directly between your browser and the official GitHub API (`api.github.com`).
*   **No Leakage:** Your API key is never transmitted to the developer or any middle-man server.

###  3. Analysis Logic & External APIs
The extension performs analysis using two methods:
1.  **Local Heuristics:** The primary security score is calculated locally within your browser's execution context.
2.  **Vulnerability Scanning:** The extension queries the **Google OSV API** (`api.osv.dev`) to check for known vulnerabilities in your dependencies. This query contains only package names and versions; no identifying user data is included.

###  4. Compliance & Consent
By using Security ExChecker, you consent to the storage of your GitHub API key on your local device for the sole purpose of increasing your API rate limits. 

###  5. Contact & Support
If you have questions regarding this policy or the extension's data handling, please contact the developer:
*   **Email:** [sagishavit1001@gmail.com](mailto:sagishavit1001@gmail.com)
*   **GitHub:** [Project Repository](https://github.com/sagishavit/Github-Security-ExChecker)

---
*Developed with a focus on transparency and open-source integrity.*
