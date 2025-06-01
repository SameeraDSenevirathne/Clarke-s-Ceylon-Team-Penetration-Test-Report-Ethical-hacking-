# Ethical Hacking Assignment - Group 24

This repository contains the documentation, evidence, and analysis of a comprehensive penetration test conducted on a simulated network environment for the **PUSL 3132: Ethical Hacking** coursework at **Plymouth University**.

## 📚 Objectives

- Assess the security posture of the Clarke’s Ceylon Team digital infrastructure.

- Identify vulnerabilities that could be exploited by an attacker.

- Demonstrate successful exploitation and post-exploitation activities.

- Provide actionable mitigation recommendations to improve security.

## 📝 Methodology

- **Planning**: Defined scope, constraints, and methodologies.

- **Reconnaissance**: Collected information using **Nmap** and **Nessus**.

- **Threat Modeling**: Identified critical assets and potential threats.

- **Vulnerability Assessment**: Employed automated tools and manual analysis.

- **Exploitation**: Conducted targeted attacks using **Metasploit**.

- **Post-Exploitation**: Collected sensitive data and performed lateral movement.

- **Reporting**: Documented findings, screenshots, and mitigation strategies.

## 🛠️ Key Tools Used

- **Nmap**: Network scanning and service discovery.

- **Nessus**: Vulnerability assessment.

- **Metasploit**: Exploitation and post-exploitation framework.

- **John the Ripper**: Password hash cracking.

## 🚨 Findings

- SMBv1/SMB Signing Disabled: Enabled exploits like EternalBlue (MS17-010).

- Weak/Default Credentials: Allowed unauthorized access.

- Outdated Operating Systems and Software: Created exposure to known exploits.

- Insecure Protocols: Use of Telnet and self-signed SSL certificates.

- Misconfigured Services: FTP with anonymous access, misconfigured SSH.

## 🔥 Key Exploitation Highlights

- Successful exploitation of **MS17-010 (EternalBlue)** on host `172.168.0.38`, resulting in a **Meterpreter session** and password hash extraction.

- Cracking of password hashes using **John the Ripper**.

## 🛡️ Mitigation Recommendations

- Update and patch outdated software and operating systems.

- Enforce SMB signing and disable SMBv1.

- Replace Telnet with SSH and enforce strong encryption protocols (TLS 1.2+).

- Use multi-factor authentication and strong password policies.

- Regularly review firewall configurations and disable unused services.

## 📂 Usage

- Ethical Hacking Assignment Report (`Ethical Hacking Assignment _GROUP-24.pdf`).

- Screenshots demonstrating reconnaissance, exploitation, and post-exploitation.

- Nessus and Nmap reports highlighting vulnerabilities.

- ⚠️ **Disclaimer**: All activities were conducted in a controlled, educational environment with explicit permission. Unauthorized access to systems without consent is illegal.

## 📚 References

- [Metasploit Framework Documentation](https://docs.metasploit.com/)

- [Nmap Official Site](https://nmap.org/)

- [OWASP Penetration Testing Methodology](https://owasp.org/)

- [Microsoft CVE Details](https://www.cvedetails.com/)

- [National Institute of Standards and Technology](https://www.nist.gov/cyberframework)
