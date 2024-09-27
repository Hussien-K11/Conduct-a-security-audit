# **Botium Toys Security Audit**
This project presents an internal security audit of **Botium Toys**, a fictional U.S. company specializing in toy development and sales. The audit was conducted to assess the company’s information security infrastructure based on the **NIST Cybersecurity Framework (CSF)** and to ensure compliance with standards like **PCI DSS**, **GDPR**, and **SOC**.

## **Overview**
This audit focused on evaluating Botium Toys' security controls and compliance posture to identify and mitigate potential risks, threats, and vulnerabilities. The IT manager requested the audit due to growing concerns around compliance, data protection, and overall security posture as the business expands its online presence.

The audit was conducted as part of a cybersecurity course project, and the findings are intended to showcase security audit skills for inclusion in a professional cybersecurity portfolio.

## **Audit Scope and Goals**
### **Scope:**
The scope of this audit covered Botium Toys' entire security program, which includes:
- **Employee Equipment:** Desktops, laptops, smartphones, workstations, headsets, etc.
- **Internal Network and Internet Access**
- **Systems:** Accounting, security, database management, and telecommunication systems.
- **Data Storage and Retention**
- **Storefront Products:** Both in-office and online.
- **Legacy System Maintenance**

### **Goals:**
The primary goals of this audit were:
1. Assess current assets and security controls.
2. Complete the **controls and compliance checklist** to identify any gaps in compliance and controls.
3. Provide recommendations to improve Botium Toys’ overall security posture and reduce risks to critical assets.

For more details on the IT department's initial scope and goals, please refer to the following document:
- [Botium Toys: Scope, Goals, and Risk Assessment Report](https://docs.google.com/document/d/1s2u_RuhRAI40JSh-eZHvaFsV1ZMxcNSWXifHDTOsgFc/template/preview#heading=h.evidx83t54sc)

## **Controls and Compliance Checklist**
The security audit involved completing a **Controls and Compliance Checklist**. The checklist evaluates whether Botium Toys has implemented certain security controls and is compliant with industry best practices. You can view the completed checklist here:
- [Completed Controls and Compliance Checklist](https://docs.google.com/document/d/1gY4FcDP1fjlqRsbBjoc0gi0J2H0plqbhRNzh_2gGyn8/edit#heading=h.87tykp1u0l36)

## **Controls Assessment Checklist**
The following controls were evaluated for Botium Toys:

| Control                                       | Yes/No  |
| --------------------------------------------- | ------- |
| Least Privilege                               | No      |
| Disaster Recovery Plans                       | No      |
| Password Policies                             | No      |
| Separation of Duties                          | No      |
| Firewall                                      | Yes     |
| Intrusion Detection System (IDS)              | No      |
| Backups                                       | No      |
| Antivirus Software                            | Yes     |
| Manual Monitoring for Legacy Systems          | No      |
| Encryption                                    | No      |
| Password Management System                    | No      |
| Locks (offices, storefront, warehouse)        | Yes     |
| Closed-Circuit Television (CCTV) Surveillance | Yes     |
| Fire Detection/Prevention Systems             | Yes     |

## **Compliance Checklist**
The following best practices were checked against relevant compliance standards:

### **Payment Card Industry Data Security Standard (PCI DSS):**

| Best Practice                                                             | Yes/No  |
| ------------------------------------------------------------------------- | ------- |
| Only authorized users have access to credit card data                      | No      |
| Credit card data is securely stored, processed, and transmitted            | No      |
| Data encryption for credit card transaction touchpoints                    | No      |
| Secure password management policies                                        | No      |

### **General Data Protection Regulation (GDPR):**

| Best Practice                                                             | Yes/No  |
| ------------------------------------------------------------------------- | ------- |
| E.U. customers' data is private/secured                                    | No     |
| Plan in place to notify E.U. customers within 72 hours of a data breach    | Yes     |
| Data is properly classified and inventoried                                | No      |
| Privacy policies and processes are enforced                                | Yes     |

### **System and Organizations Controls (SOC type 1, SOC type 2):**

| Best Practice                                                             | Yes/No  |
| ------------------------------------------------------------------------- | ------- |
| User access policies are established                                       | No      |
| Sensitive data (PII/SPII) is kept confidential                             | No      |
| Data integrity is ensured (consistent, complete, accurate)                 | Yes     |
| Data is available to authorized individuals                                | No      |

## **Findings**
The security audit revealed several areas where Botium Toys needs to implement critical controls to meet compliance and reduce risk. Key findings include:
- **No disaster recovery plan or data backups**, which poses a major risk to business continuity.
- **Lack of encryption** for sensitive customer and payment data, increasing the risk of data breaches.
- **Outdated password policies** and no centralized password management, which could lead to weak access controls.
- **No intrusion detection system (IDS)**, making the company vulnerable to unnoticed attacks or breaches.

## **Recommendations**
To mitigate risks and improve security posture, the following actions are recommended:
1. **Implement Encryption:** All sensitive data, especially customer credit card information, must be encrypted both in transit and at rest.
2. **Create a Disaster Recovery Plan:** A plan for data backups and disaster recovery must be developed and tested regularly to ensure business continuity.
3. **Update Password Policies:** Enforce stronger password requirements and implement a password management system to manage credentials securely.
4. **Install an IDS:** Implement an intrusion detection system to monitor network traffic and detect potential security breaches.
5. **Regular Legacy System Maintenance:** Schedule regular maintenance for legacy systems to ensure they are secure and up to date.

## **Conclusion**
This project demonstrates the process of conducting an internal security audit using industry-standard frameworks and compliance requirements. By following the recommendations, Botium Toys can significantly improve its security posture, protect sensitive data, and comply with regulatory standards.

Feel free to download and review the full audit report, checklist, and recommendations.

## **Resources**
- [Botium Toys: Scope, Goals, and Risk Assessment Report](https://docs.google.com/document/d/1s2u_RuhRAI40JSh-eZHvaFsV1ZMxcNSWXifHDTOsgFc/template/preview#heading=h.evidx83t54sc)
- [Completed Controls and Compliance Checklist](https://docs.google.com/document/d/1gY4FcDP1fjlqRsbBjoc0gi0J2H0plqbhRNzh_2gGyn8/edit#heading=h.87tykp1u0l36)

## **Next Steps**
1. Clone the repository or download the files to review the audit process in detail.
2. Use this project as a template for conducting internal security audits in real-world scenarios.

## **How to Use This Project**
- **For Employers:** This project demonstrates my ability to assess risks, evaluate security controls, and ensure compliance with industry regulations. Feel free to contact me for more details or to discuss how my skills can contribute to your security initiatives.
- **For Peers:** You can use this project as a reference or learning tool to improve your understanding of security audits and compliance frameworks.
