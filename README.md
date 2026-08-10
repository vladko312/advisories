# Advisories for vulnerabilities
![Advisories](https://img.shields.io/badge/Advisories-4-blue)
![Last modified](https://img.shields.io/badge/Last_modified-10.08.2026-blue)

---

[![pybars3](https://img.shields.io/badge/CVE--2025--25985-9.8-red)](./pybars3.md) -
**Pybars3** at least up to the current version **0.9.7** and **Pybars4** at least up to the current version **0.9.13** are vulnerable to Code Injection.
An attacker controlling the template string can achieve arbitrary code execution without any additional requirements.

[![CVE-2025-25985](https://img.shields.io/badge/CVE--2025--25985-3.2-green)](./CVE-2025-25985.md) -
Macro-video Technologies Co.,Ltd V380E6_C1 IP camera (hardware id: Hw_HsAKPIQp_WF_XHR) was discovered to store plaintext Wi-Fi and user credentials in the filesystem on the flash memory.
This vulnerability allows attackers with physical access to the device or root shell access to access those credentials.

[![CVE-2025-25984](https://img.shields.io/badge/CVE--2025--25984-6.8-yellow)](./CVE-2025-25984.md) -
Macro-video Technologies Co.,Ltd V380E6_C1 IP camera (hardware id: Hw_HsAKPIQp_WF_XHR) was discovered to contain hardcoded root credentials stored in read-only filesystem on the flash memory.
This vulnerability allows attackers with physical access to the device to gain root shell access via UART.

[![CVE-2025-25983](https://img.shields.io/badge/CVE--2025--25983-3.4-green)](./CVE-2025-25983.md) -
QR code based device sharing component present in Macro-video Technologies Co.,Ltd V380 Pro android application versions 2.1.44 and 2.1.64 allows an attacker to obtain plaintext credentials from the created QR code.