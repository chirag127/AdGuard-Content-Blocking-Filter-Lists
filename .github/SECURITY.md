# Security Policy

## Supported Versions

| Version | Supported Status |
| ------- | ---------------- |
| Latest  | ✅ Supported     |

---


## Reporting a Vulnerability

We take the security of our project very seriously. If you discover any security vulnerabilities in **AdGuard-Content-Blocking-Filter-Lists**, please report them responsibly.

**Responsible Disclosure Policy:**

1.  **Do not publicly disclose any vulnerability.**
2.  **Private Disclosure:** Please report any discovered vulnerability by sending an email to the security team at `chirag.dev@example.com` (or a dedicated security email if one exists for the project). Please include as much detail as possible, including steps to reproduce the vulnerability.
3.  **Acknowledgement:** We will acknowledge receipt of your vulnerability report within **48 hours**.
4.  **Resolution:** We will work diligently to assess and resolve the vulnerability as quickly as possible. We will provide an estimated timeline for a fix.
5.  **Public Disclosure:** Once a fix is available and deployed, we may, in coordination with the reporter, disclose the vulnerability details.

We appreciate your efforts in helping to keep **AdGuard-Content-Blocking-Filter-Lists** secure.

---


## Security Best Practices for Filter Lists

As this project primarily deals with filter lists for content blocking, security considerations extend to the integrity and safety of the lists themselves:

*   **Source Verification:** Always verify the source of any contributed or included filter lists. Ensure they are reputable and do not introduce malicious patterns or malware.
*   **Pattern Sanitization:** Implement and maintain robust sanitization routines to prevent the accidental inclusion of patterns that could be exploited (e.g., overly broad selectors that might lead to bypasses or unexpected behavior).
*   **Regular Audits:** Conduct regular audits of existing filter lists to ensure they remain effective, do not conflict with each other, and do not pose any security risks.
*   **Community Contributions:** For community contributions, enforce a strict review process, possibly involving manual checks and automated pattern analysis, before merging.

---


## Tools & Technologies

This repository and its associated infrastructure are developed with security best practices in mind. While this project does not execute arbitrary code or handle sensitive user data directly, the principles of secure development apply:

*   **Static Analysis:** Tools like **Ruff** are used for rapid linting and security analysis of the Python code (if applicable to the generation/management scripts).
*   **Dependency Scanning:** Dependencies will be regularly scanned for known vulnerabilities.
*   **Review Process:** All changes undergo rigorous review before merging.

---


## How to Contribute

Refer to the `.github/CONTRIBUTING.md` file for guidelines on how to contribute to this project. Security-related contributions are particularly welcome.

---


## License

This project is licensed under the **CC BY-NC 4.0 License**. See the `LICENSE` file for more details. This means you are free to share and adapt the material for non-commercial purposes, provided you give appropriate credit, provide a link to the license, and indicate if changes were made.