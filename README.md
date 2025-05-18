#   Controls and Compliance Checklist - Botium Toys

## Scope and Goals: 

**Scope:** For fictitious Botium Toys, this project focuses on implementing missing critical security controls and addressing non-compliant areas identified in their [Scope, Goals, and Risk Assessment Report](https://docs.google.com/document/d/161ZO0O4TM9Kef5BMtyahWzCd67Qxe7mPEWk2Yj0GT-g/edit?usp=sharing). 

Compliance efforts will target:

* **PCI DSS:** Secure credit card data handling practices.
* **GDPR:** EU customer data privacy and security measures.
* **SOC:** User access policies and sensitive data protection.

**Goals:**

1.  Implement foundational missing security controls.
2.  Address immediate non-compliance with PCI DSS and GDPR.
3.  Reduce critical security vulnerabilities.


![image](https://github.com/user-attachments/assets/128c7173-d6c3-4cdf-855b-6d052b201b2f)


---

##   Controls Assessment Checklist

*Does Botium Toys currently have these controls in place?*

|   Yes   |   No   |   Control   |
| :---: | :---: | :------------------------------------------------------------------ |
|   ☐   |   ❌   |   Least Privilege   |
|   ☐   |   ❌  |   Disaster recovery plans   |
|   ☐   |   ❌  |   Password policies   |
|   ☐   |   ❌  |   Separation of duties   |
|   ✔️  |   ☐   |   Firewall   |
|   ☐   |   ❌  |   Intrusion detection system (IDS)   |
|  ✔️   |   ☐   |   Backups   |
|   ☐   |   ❌  |   Antivirus software   |
|   ☐   |   ❌  |   Manual monitoring, maintenance, and intervention for legacy systems |
|   ✔️  |   ☐   |   Encryption   |
|   ☐   |   ❌  |   Password management system   |
|  ✔️   |   ☐   |   Locks (offices, storefront, warehouse)   |
|  ✔️   |   ☐   |   Closed-circuit television (CCTV) surveillance   |
|  ✔️   |   ☐   |   Fire detection/prevention (fire alarm, sprinkler system, etc.)   |

---

##   Compliance Checklist 📜

*Does Botium Toys currently adhere to these compliance best practices?*

**Payment Card Industry Data Security Standard (PCI DSS)** </br> International standard for secure credit card data handling

|   Yes   |   No   |   Best practice   |
| :---: | :---: | :--------------------------------------------------------------------- |
|   ☐   |   ❌  |   Only authorized users have access to customers' credit card information. |
|   ☐   |   ❌  |   Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |
|   ☐   |   ❌  |   Implement data encryption procedures to better secure credit card transaction touchpoints and data. |
|   ☐   |   ❌  |   Adopt secure password management policies.   |

**Compliance Explanation**  </br> Due to handling of credit card transactions both online and in person, adherence to PCI DSS is required for secure processing and storage.

---

**General Data Protection Regulation (GDPR)** </br> A regulation protecting EU citizens' data privacy within and outside EU territory, requiring breach notification within 72 hours

|   Yes   |   No   |   Best practice   |
| :---: | :---: | :------------------------------------------------------------------- |
|   ☐   |   ❌  |   E.U. customers' data is kept private/secured.   |
|   ✔️  |   ☐   |   There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |
|   ☐   |   ❌  |   Ensure data is properly classified and inventoried.   |
|   ✔️  |   ☐   |   Enforce privacy policies, procedures, and processes to properly document and maintain data. |


**Compliance Explanation** </br> The organization must comply with GDPR as it collects and processes personal information of EU citizens. Any breaches must be reported within 72 hours.

---
**System and Organizations Controls (SOC type 1, SOC type 2)**

|   Yes   |   No   |   Best practice   |
| :---: | :---: | :------------------------------------------------------------------ |
|   ☐   |   ❌  |   User access policies are established.   |
|   ☐   |   ❌  |   Sensitive data (PII/SPII) is confidential/private.   |
|   ✔️  |   ☐   |   Data integrity ensures the data is consistent, complete, accurate, and has been validated. |
|   ☐   |   ❌  |   Data is available to individuals authorized to access it.   |

**Compliance Explanation** </br> To implement user access policies and ensure the confidentiality/privacy of sensitive data (PII/SPII), and ensuring data availability to authorized individuals.

---

##   Controls Assessment 🔧 

### Administrative Controls

|   Control name   |   Type and Explanation   |   Needs Implementation (X)   |   Priority   |
| :--------------- | :------------------------------: | :-----------------------------: | :----------: |
|   Least Privilege   |   **Preventative:** Reduces risk of insider threats  |   X   |   High   |
|   Disaster recovery plans   |   **Corrective:** Supports business continuity   |   X   |   High   |
|   Password policies   |   **Preventative:** Defends against brute-force  |   X   |   High   |
|   Separation of duties   |   **Preventative:** Reduces misuse of power  |   X   |   High   |

### Technical Controls

|   Control Name   |   Type and Explanation   |   Needs Implementation (X)   |   Priority   |
| :--------------------------: | :-----------------------------------------------------------------: | :-----------------------------: | :----------: |
|   Intrusion Detection System (IDS)   |   **Detective:**  Identifies intrusions   |   X   |   High   |
|   Backups   |   **Corrective:**  Supports recovery |   X   |   High   |
|   Encryption   |   **Deterrent:** Protects sensitive data  |   X   |   High/ Medium   |
|   Password management   |   **Preventative:** Reduces password fatigue   |   X   |   Medium   |

----

## Recommendations 💡

- **Implement core preventative controls** such as password policies, least privilege, and encryption.
- **Enhance technical infrastructure** with IDS, regular backups, and password management systems.
- **Comply with applicable standards** (PCI DSS, GDPR) due to the handling of sensitive customer data.
- **Enforce administrative procedures** like separation of duties and a disaster recovery plan.

----
## 🚀 Project Status

![Status](https://img.shields.io/badge/Status-Complete-brightgreen) ![Focus](https://img.shields.io/badge/Focus-Controls--Assessment-yellow) ![Compliance](https://img.shields.io/badge/Compliance-GDPR-critical) ![Compliance](https://img.shields.io/badge/Compliance-PCI--DSS-critical)


---
> *“Security is not a product, but a process.”* – Bruce Schneier
