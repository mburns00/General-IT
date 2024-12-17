# Network Security Assessment and Mitigation Strategies

This project involves conducting a comprehensive network vulnerability assessment and proposing strategic solutions to enhance the security posture of an enterprise network. The focus is on identifying critical threats, assessing vulnerabilities, and implementing effective countermeasures to safeguard network infrastructure.

---

## Project Overview

The project addresses key network security challenges, including:

- **Outdated server software vulnerabilities**
- **Insufficient network segmentation**
- **Obsolete encryption protocols**
- **Potential for man-in-the-middle attacks**
- **Lack of employee cybersecurity awareness**
- **Inadequate access control measures**

The vulnerability assessment and analysis were conducted using **Greenbone SIEM** in a Virtual Machine (VM) environment to ensure a systematic and reliable evaluation.

---

## Objectives

- **Conduct a thorough vulnerability assessment** using Greenbone SIEM and manual penetration testing tools.
- **Identify and prioritize network vulnerabilities** based on severity and impact.
- **Develop strategic recommendations** to mitigate identified risks.
- **Implement network security solutions** such as updated software, segmentation, and encryption enhancements.

---

## Key Findings

### 1. Critical Software Vulnerabilities
![{4AE11D24-B7F4-423D-B8ED-AA59C9225D4B}](https://github.com/user-attachments/assets/e2bb7047-59b8-4c45-94d8-617bd3c26e25)

- **Outdated Server Software**: Servers running obsolete versions of ProFTPD, OpenSSH, and Apache HTTPD with known security flaws.
- **Compromised Services**: Vulnerabilities on ports `8787/TCP`, `143/TCP`, and `993/TCP` exposing the network to remote code execution and other attacks.

### 2. Network Configuration Issues
![{32C4A9CB-4F5B-45CE-B3C0-8947416E3E32}](https://github.com/user-attachments/assets/cddd0596-1235-4017-8ae8-b5dbe40c7732)

- **Insufficient Network Segmentation**: Lack of proper VLANs and DMZs allowing lateral movement within the network.
- **Obsolete Encryption Protocols**: Use of SSLv2 and SSLv3 protocols susceptible to interception and decryption.

### 3. Potential Attack Vectors
![{DAE17153-47E8-44B9-BF9D-7E9B63F75DC6}](https://github.com/user-attachments/assets/18b36ef8-42ec-4b74-affb-ebe2d0cfd772)

- **Man-In-The-Middle Attacks**: Network susceptible to eavesdropping and data manipulation due to insecure configurations.

---

## Proposed Solutions

### 1. Software Updates and Patch Management

- **Update Server Software**: Upgrade to the latest versions of ProFTPD, OpenSSH, and Apache to patch known vulnerabilities.
- **Implement Regular Patch Cycles**: Establish a routine for timely updates of all network devices and software.

### 2. Network Segmentation and Firewalls

- **Implement VLANs and DMZs**: Segment the network to isolate sensitive departments and services.
- **Deploy Next-Generation Firewalls**: Place firewalls strategically to control traffic between network segments.

### 3. Encryption Enhancements

- **Upgrade Encryption Protocols**: Adopt TLS 1.3 for all services to ensure data confidentiality and integrity.
- **Disable Obsolete Protocols**: Remove support for SSLv2 and SSLv3 across the network.

### 4. Access Control and Authentication

- **Enforce Multi-Factor Authentication (MFA)**: Add MFA for accessing sensitive systems.
- **Implement Role-Based Access Control (RBAC)**: Ensure users have appropriate permissions based on their roles.

### 5. Cybersecurity Awareness Training

- **Employee Training Programs**: Educate staff on phishing, social engineering, and best security practices.
- **Simulated Phishing Exercises**: Conduct regular tests to reinforce awareness.

---

## Tools & Technologies

- **SIEM Analysis**: Greenbone Vulnerability Management in a Virtual Machine (VM)
- **Vulnerability Scanning**: OpenVAS
- **Penetration Testing**: Nmap, Metasploit
- **Network Design**: Implementation of VLANs, DMZs, and firewalls
- **Encryption Protocols**: TLS 1.3
- **Access Control**: MFA solutions, RBAC systems

---

## Results

By implementing the proposed solutions, the network's security posture will be significantly enhanced, reducing the risk of data breaches and cyber attacks. The strategic placement of security measures will:

- **Prevent Unauthorized Access**: Through updated software and strict access controls.
- **Contain Potential Breaches**: Via network segmentation and firewalls.
- **Protect Data Integrity and Confidentiality**: With modern encryption standards.
- **Strengthen Organizational Security Culture**: Through ongoing employee training.

---

## Conclusion

This project underscores the importance of proactive network security measures. By identifying critical vulnerabilities using **Greenbone SIEM** in a Virtual Machine and implementing strategic solutions, organizations can safeguard their digital assets, maintain operational integrity, and protect against evolving cyber threats.

---

## How to Use

1. Set up **Greenbone SIEM** in a Virtual Machine for vulnerability scanning.
2. Replicate the network topology and configurations (VLANs, DMZs, firewalls).
3. Conduct further vulnerability assessments and penetration tests.
4. Implement the proposed solutions for improved network security.

---

