# Elevate_labs_Task3_Nessus-scan
# 🔍 Task 3: Vulnerability Scan on Local Machine

## 📌 Objective
Perform a basic vulnerability assessment on a local machine using Nessus Essentials and document the findings.

---

## 🛠️ Tools Used
- **Scanner**: Nessus Essentials (Free)
- **Target IP**: 192.168.146.135 (Metasploitable VM)

---

## 🖥️ Scan Summary

| Severity | Count |
|----------|-------|
| Critical | 4     |
| High     | 4     |
| Medium   | 7     |
| Low      | 1     |
| Info     | 51    |

**Total Vulnerabilities Detected**: 67

---

## 🚨 Top Critical Issues

### 1. **UnrealIRCd Backdoor**
- **CVSS**: 10.0
- Known backdoored version, allows full remote control.

### 2. **Bind Shell Detection**
- **CVSS**: 9.8
- Dangerous shell backdoor giving remote access.

### 3. **Apache Tomcat ≤ 5.5.x**
- **CVSS**: 10.0
- Severely outdated, multiple critical vulnerabilities.

### 4. **Ubuntu 8.04 SEoL**
- OS is no longer supported; lacks security updates.

---

## 🛡️ Fix Recommendations

- Upgrade all outdated services (e.g., Tomcat, Samba, UnrealIRCd).
- Disable insecure protocols (e.g., Telnet, rsh).
- Use encryption and firewalls to protect NFS and SMB services.
- Replace deprecated OS (Ubuntu 8.04) with supported version.

---

## 📎 Files Included

- `Scan_report.pdf` – Full Nessus scan export
- `README.md` – This analysis report
- `screenshots/` – (Add scan UI screenshots here)

---

## 🧠 Key Learnings

- Gained hands-on experience with Nessus vulnerability scanning.
- Identified real-world risks in vulnerable virtual environments.
- Learned how CVSS scores help prioritize threats.

---
