# Incident Response Playbook

**For Cargojet Airways Limited**  
**Prepared by Jamiu Ayinde**

---

## Table of Contents

1. [Executive Summary](#executive-summary)  
2. [Roles, Responsibilities & Contact Information](#roles-responsibilities--contact-information)  
3. [Incident Type: Malware Attack](#incident-type-malware-attack)  
4. [Incident Response Process](#incident-response-process)  
5. [Escalation Points and Justifications](#escalation-points-and-justifications)  
6. [Stakeholder Communication](#stakeholder-communication)  
7. [References](#references)  

---

## Executive Summary

To safeguard the operational integrity and data confidentiality at Cargojet Airways Limited, this Incident Response Plan (IRP) guides the Incident Response Team (IRT) through detecting, containing, eradicating, and learning from cybersecurity incidents. Partnering with **CYBERDB** for third-party support, the IRP aims to prevent data loss, service interruption, and reputational damage.

---

## Roles, Responsibilities & Contact Information

| **Role**                  | **Responsibility**                                                                 | **Contact Information**      |
|---------------------------|-------------------------------------------------------------------------------------|------------------------------|
| **CSO / CISO**            | Strategic lead. Develops risk ranking criteria. Main contact for executives/board.  | Name: Akeem<br>Email: ak@cargojet.com |
| **Incident Response Lead**| Authorizes and coordinates incident response efforts.                               | Name: Kevin Incuben<br>Email: Kincuben@cargojet.com |
| **Identity & Access Team**| Manages privileged accounts and monitors for compromise.                           | Name: Wale Adeniji<br>Email: Wadenji@cargojet.com |
| **IT Operations**         | Manages access, patches, and upgrades to contain threats.                          | Name: Lanre Ifanyi<br>Email: lanre@cargojet.com |
| **Legal Counsel**         | Ensures compliance with notification and legal standards.                          | Name: Akeem Ayinde<br>Email: ak@cargojet.com |
| **Audit & Compliance**    | Manages regulatory reporting requirements.                                         | Name: Jide Olopoona<br>Email: Jide@cargojet.com |
| **Human Resources**       | Handles employee communications regarding breaches.                                | Name: Ogundipe Lanrewal<br>Email: Olanre@cargojet.com |
| **Marketing & PR**        | Manages external communication with customers, partners, and media.                | Name: Michael Chibuzo<br>Email: Micheal@cargojet.com |
| **Technical Support Lead**| Provides technical guidance for external users during incidents.                   | Name: Jane Smit<br>Email: jane@cyberdb.com |

---

## Incident Type: Malware Attack

- **Systems Affected:** Flight scheduling servers  
- **Threat Actor:** Possible nation-state or organized criminal group  
- **Attack Vector:** Phishing link and malware installation  
- **Detection Timeline:** 2 hours  

---

## Incident Response Process

### Step 1: Preparation
- Regular training and policy review.
- Maintain contact lists and ensure regulatory compliance.

### Step 2: Identification
- Monitor logs and escalate if critical systems are compromised.

### Step 3: Containment
- Isolate affected systems. Engage CYBERDB if containment fails.

### Step 4: Eradication
- Remove malware and audit systems. Escalate if reinfection is detected.

### Step 5: Recovery
- Restore systems and validate patching. Report persistent vulnerabilities.

### Step 6: Lessons Learned
- Review the incident and propose procedural improvements.

### Step 7: Communications
- Notify stakeholders and follow compliance/reporting standards.

---

## Escalation Points and Justifications

- **Systems Affected:** Operational servers require immediate attention due to mission-critical operations.  
- **Attack Confirmation:** Escalate upon detecting phishing attempts with malware.  
- **Containment Failure:** Escalate to Identity and Access Team.  
- **Detected Re-infection:** Engage CYBERDB for forensic investigation.  
- **Post-Incident Gaps:** Share findings with management to secure resources for future prevention.  

---

## Stakeholder Communication

- **Internal Stakeholders:** Executive Team, IT, Employees  
- **External Stakeholders:** Customers, Regulatory Bodies  
- **Sensitive Information to Withhold:** Attack specifics and system vulnerabilities  

---

## References

1. [SANS Institute](https://www.sans.org) - Best Practices for Incident Management  
2. [NIST SP 800-61r2](https://nvlpubs.nist.gov) - Incident Handling Guide  
3. [PCI DSS Guidelines](https://www.pcisecuritystandards.org) - Incident Response  
4. [HIPAA Breach Notification](https://www.hhs.gov/hipaa)  
5. [GDPR](https://eugdpr.org) - General Data Protection Regulation  
6. [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)  
7. [ISO/IEC 27035](https://www.iso.org) - Information Security Incident Management  

---

**Document Owner:** Jamiu Ayinde  
**Approved By:** Pauline Dhillon  
**Version:** 2.0  
**Last Reviewed:** October 2024
