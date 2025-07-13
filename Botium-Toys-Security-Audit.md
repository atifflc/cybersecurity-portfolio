# Botium Toys Internal Security Audit Report

## 1. Introduction

This report documents the results of an internal security audit for Botium Toys, a small U.S.-based toy company with a growing online presence. The audit evaluates the current security posture, identifies risks, and assesses compliance with industry standards and best practices.

## 2. Scope and Goals

- **Scope:** The audit covers all assets managed by Botium Toys’ IT department, including employee equipment, internal network, systems, data storage, and physical assets.
- **Goals:**
  - Review and classify IT-managed assets.
  - Assess current controls and compliance practices.
  - Identify security gaps and recommend improvements.

## 3. Assets Managed by IT

- On-premises equipment for business operations
- Employee devices (desktops, laptops, smartphones, peripherals)
- Storefront products (retail and warehouse)
- Systems and software (accounting, telecom, database, security, ecommerce, inventory)
- Internet access and internal network
- Data retention and storage solutions
- Legacy systems (end-of-life, require monitoring)

## 4. Risk Assessment Summary

- **Risk Score:** 8/10 (high risk due to insufficient controls and incomplete compliance)
- **Key Risks:**
  - Inadequate asset management and classification
  - Potential exposure of cardholder data and PII/SPII
  - No encryption for sensitive data
  - Lack of access controls (least privilege, separation of duties)
  - No intrusion detection system (IDS)
  - No disaster recovery or data backup plans
  - Weak password policy and no centralized password management
  - Irregular legacy system maintenance
- **Impact:** Medium for asset loss (due to lack of asset visibility), high for regulatory fines and data breaches.

## 5. Controls Assessment Checklist

| Control                                   | In Place? | Notes                                                    |
|--------------------------------------------|-----------|----------------------------------------------------------|
| Asset inventory and classification         | No        | Assets not fully identified or classified.               |
| Access controls (least privilege, SoD)     | No        | Not implemented.                                         |
| Encryption for sensitive data              | No        | Not used for cardholder/customer data.                   |
| Firewall                                   | Yes       | Appropriately configured and maintained.                 |
| Antivirus software                         | Yes       | Installed and regularly monitored.                       |
| Intrusion Detection System (IDS)           | No        | Not installed.                                           |
| Disaster recovery and data backups         | No        | No plans or backups in place.                            |
| Password policy (complexity, enforcement)  | No        | Policy exists but is weak and unenforced.                |
| Centralized password management            | No        | Not implemented.                                         |
| Physical security (locks, CCTV, fire)      | Yes       | Adequate controls in place.                              |
| Privacy policies and breach notification   | Yes       | Policies and E.U. breach notification plan exist.        |

## 6. Compliance Checklist

| Compliance Best Practice           | In Place? | Notes                                                    |
|------------------------------------|-----------|----------------------------------------------------------|
| PCI DSS (Payment Card Industry)    | No        | No encryption or strong access controls for cardholder data. |
| GDPR (General Data Protection)     | Partial   | Breach notification plan and privacy policies exist, but gaps remain. |
| SOC 1 / SOC 2                      | No        | No evidence of controls or audits for these standards.    |

## 7. Recommendations

- **Asset Management:** Implement asset inventory and classification processes.
- **Access Controls:** Enforce least privilege and separation of duties.
- **Encryption:** Deploy encryption for all sensitive customer and payment data.
- **Intrusion Detection:** Install and configure an IDS.
- **Disaster Recovery:** Develop and test disaster recovery and backup plans.
- **Password Security:** Update password policy and implement centralized management.
- **Compliance:** Work towards full PCI DSS and GDPR compliance.
- **Legacy Systems:** Establish a maintenance schedule and clear intervention procedures.

## 8. Self-Assessment Checklist

| Requirement                                              | Completed |
|---------------------------------------------------------|-----------|
| Reviewed scope, goals, and risk assessment report       | Yes       |
| Considered risks to customers, employees, and assets    | Yes       |
| Reviewed the control categories document                | Yes       |
| Selected "yes" or "no" for each control listed          | Yes       |
| Selected "yes" or "no" for each compliance best practice| Yes       |

*This report can be saved and uploaded to your professional portfolio or GitHub repository to demonstrate your ability to conduct a security audit and assess compliance for a growing organization.*
