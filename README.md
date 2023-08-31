# Qualys-Vuln-Management

## Description
This project involves conducting an unauthenticated and authenticated scan on an insecure Windows 10 virtual machine using a Qualys External Scan Application. Following the scans, security measures will be implemented to remediate vulnerabilities found. 

## What is Qualys?
Qualys is a cybersecurity company that offers a cloud-based platform for various security and compliance solutions. Their platform provides tools for vulnerability management, continuous monitoring, web application security, policy compliance, and more. Qualys helps organizations identify vulnerabilities and potential security risks within their systems, assess the security of web applications, and ensure compliance with various industry regulations. Their services aid in maintaining a strong cybersecurity posture and protecting digital assets from potential threats.

## Software/Hardware Used: 
- VMWare
- Microsoft Windows 10 Pro
- Qualys External Scan Application

## Unauthenticated Scan Before Hardening / Security Controls
![image](https://github.com/nigelamoss/Qualys-Vuln-Management/assets/91230399/0778371a-7186-411d-82b4-4cad14dcac90)

![image](https://github.com/nigelamoss/Qualys-Vuln-Management/assets/91230399/87a049ad-e0df-4563-a653-014128e6dfc1)

## Authenticated Scan Before Hardening / Security Controls
![image](https://github.com/nigelamoss/Qualys-Vuln-Management/assets/91230399/13e97289-dba7-47a3-b4e4-26533b0a9264)

![image](https://github.com/nigelamoss/Qualys-Vuln-Management/assets/91230399/f2347d6e-2250-462b-ab8e-d1e2f9915eb7)

## Metrics Before Hardening / Security Controls

The following table shows the metrics we measured in our insecure environment:

| Vulnerability Severity   | Confirmed
| ------------------------ | -----
| 5                        | 7
| 4                        | 77
| 3                        | 45
| 2                        | 8
| 1                        | 0
| Info                     | 177
| Total                    | 137

## Remediation Measures
The following security controls were implementated:
  - Installed latest version of Windows 10 OS update
  - Installed latest version of Microsoft Edge Browser
  - Uninstalled outdated Mozilla Firefox Browser
  - Installed latest version of VLC software
  - Disabled network discovery
  - Disabled file and printer sharing

## Authenticated Scan After Hardening / Security Controls
![image](https://github.com/nigelamoss/Qualys-Vuln-Management/assets/91230399/c6925f0a-d809-4810-8073-9bd7bde4a5b6)


![image](https://github.com/nigelamoss/Qualys-Vuln-Management/assets/91230399/fc4e91ea-76a9-4a92-8848-e16d5683055d)


## Metrics After Hardening / Security Controls

The following table shows the metrics we measured in our insecure environment after we have applied security controls:

| Vulnerability Severity   | Confirmed
| ------------------------ | -----
| 5                        | 0
| 4                        | 0
| 3                        | 0
| 2                        | 8
| 1                        | 0
| Info                     | 4
| Total                    | 4

## Conclusion
In this project, we performed an unauthenticated and authenticated scan on an insecure Windows 10 machine. We proceeded to review the vulnerabilities found and implement appropriate security measures to remediate the aforementioned vulnerabilities. After remediation, we ran another authenticated scan to confirm the impact of the security measures. It is noteworthy that the number of vulnerabilities was drastically reduced after the security controls were applied, demonstrating their effectiveness. 
