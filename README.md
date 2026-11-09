# Task-3
Perform-a-Basic-Vulnerability-Scan-on-Your-PC-


## 1. Objective

The objective of this task is to perform a basic vulnerability assessment on a personal computer using **Tenable Nessus Essentials**. The scan helps identify security weaknesses, outdated software, missing security patches, and potential configuration issues.

## 2. Tools Used

- **Tenable Nessus Essentials** – Vulnerability scanning tool.
- **Windows 10/11** – Target operating system.
- **Web Browser** – To access the Nessus interface.
- **Command Prompt** – To identify system and network information.

## 3. Scope

- Target: Personal Windows PC.
- Assessment type: Basic vulnerability scan.
- Scanning tool: Nessus Essentials.
- Scan policy: Basic Network Scan.

Only systems owned by me or systems for which explicit authorization has been obtained are included in the assessment.

## 4. Procedure

### Step 1: Install Nessus Essentials

1. Visit the official Tenable website.
2. Download Nessus Essentials.
3. Install the application on the Windows PC.
4. Complete activation and allow the plugins to update.

Official website: https://www.tenable.com/products/nessus/nessus-essentials

### Step 2: Identify System Information

Open Command Prompt and execute:

```cmd
ipconfig
```

To identify the computer name:

```cmd
hostname
```

Record the local IP address and system details for the assessment.

### Step 3: Configure Vulnerability Scan

1. Open the Nessus web interface.
2. Log in to the Nessus dashboard.
3. Select **New Scan**.
4. Choose **Basic Network Scan**.
5. Enter the authorized target IP address.
6. Save the scan configuration.

### Step 4: Perform the Scan

1. Open the configured scan.
2. Click **Launch**.
3. Wait for Nessus to complete the vulnerability assessment.
4. Monitor the scan progress.
5. Open the completed scan results.

### Step 5: Analyze Vulnerabilities

Review the scan results and identify:

- Critical vulnerabilities
- High-severity vulnerabilities
- Medium-severity vulnerabilities
- Low-severity vulnerabilities
- Informational findings

For each vulnerability, review its plugin name, severity, CVE (if applicable), affected port, description, and recommended solution.

## 5. Vulnerability Severity Classification

| Severity | Description |
|---|---|
| Critical | Vulnerabilities with potentially severe security impact |
| High | Significant security weaknesses requiring priority attention |
| Medium | Security issues that should be addressed based on risk |
| Low | Lower-risk security weaknesses |
| Informational | Security observations that may help assess system configuration |

## 6. Common Security Issues and Mitigation

The following are examples of issues that may be identified during vulnerability assessments. They are not confirmed findings from this scan unless they appear in the actual Nessus results.

| Potential Issue | Recommended Mitigation |
|---|---|
| Missing security updates | Install the latest Windows security patches |
| Outdated software | Update applications to supported versions |
| Open or unnecessary ports | Disable unnecessary services and restrict firewall access |
| Weak security configurations | Apply secure configuration policies |
| Outdated TLS protocols | Configure supported and secure TLS versions |
| SMB security weaknesses | Review and enforce appropriate SMB security settings |

## 7. Security Recommendations

- Keep Windows and installed applications updated.
- Enable Windows Defender Firewall.
- Use strong passwords and Multi-Factor Authentication.
- Disable unnecessary services and ports.
- Install software only from trusted sources.
- Perform vulnerability assessments periodically.
- Follow the principle of least privilege.

## 8. Results and Observations

The Nessus vulnerability scanner provides an overview of potential security weaknesses present on the target computer.

The actual number of vulnerabilities identified in each severity category should be recorded from the completed Nessus scan:

| Severity | Findings |
|---|---|
| Critical | [Enter actual count] |
| High | [Enter actual count] |
| Medium | [Enter actual count] |
| Low | [Enter actual count] |
| Informational | [Enter actual count] |

The identified vulnerabilities should be prioritized according to their severity and potential impact. Remediation should be followed by another scan to verify whether the issues have been resolved.

## 9. Conclusion

This task provided practical knowledge of vulnerability assessment using Tenable Nessus Essentials. It helped me understand how to configure a vulnerability scan, identify security weaknesses, interpret vulnerability severity levels, and recommend appropriate mitigation measures.

Regular vulnerability scanning, timely patch management, and secure system configurations are important practices for maintaining endpoint security.

## 10. References

- [Tenable Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials)
- [Nessus Documentation](https://docs.tenable.com/nessus/)
- [Microsoft Security Update Guide](https://msrc.microsoft.com/update-guide)
- [OWASP](https://owasp.org/)

