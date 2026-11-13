
# Vantrel: AI Chat Assistant – PCI DSS & HIPAA Gap Analysis

![GRC](https://img.shields.io/badge/Domain-GRC-blue)
![PCI DSS](https://img.shields.io/badge/Framework-PCI%20DSS-orange)
![HIPAA](https://img.shields.io/badge/Framework-HIPAA-green)
![Project](https://img.shields.io/badge/Project-Compliance%20Assessment-purple)
![Status](https://img.shields.io/badge/Status-Completed-success)

##  Project Overview

This project presents a cybersecurity compliance gap analysis for **Vantrel**, an organization introducing an AI-powered chat assistant into its existing environment.

The assessment examines the security and compliance implications of introducing an AI chat assistant that may collect, process, and store sensitive patient health information and payment card details.

Using the **Payment Card Industry Data Security Standard (PCI DSS)** and the **Health Insurance Portability and Accountability Act (HIPAA)** as assessment frameworks, the project identifies security gaps, evaluates their potential impact, and recommends controls to strengthen data protection and compliance.

The primary focus is ensuring that all systems handling sensitive patient and payment information are included within the organization's compliance scope and adequately protected.

##  Problem Statement

The introduction of Vantrel's AI chat assistant creates additional cybersecurity and compliance risks.

Patients may disclose sensitive medical information and payment card details through chat interactions. Furthermore, the assistant uses a separate database that is not directly managed by the organization's security team.

This creates several security concerns, including:

Exposure of sensitive information through unencrypted chat transcripts.
Unauthorized access to the separate chat database.
Storage of payment card information in chat conversations.
Insufficient activity monitoring and audit logging.
Security risks associated with third-party AI providers.
Inadequate data retention and deletion policies.
Potential vulnerabilities within the AI application and its APIs.

Without appropriate security controls and an expanded compliance scope, these weaknesses could expose Vantrel to data breaches, payment fraud, and regulatory compliance risks.

##  Project Objectives

The objectives of this assessment are to:

Identify security and compliance gaps associated with the AI chat assistant.
Map identified gaps to relevant PCI DSS and HIPAA requirements.
Evaluate the risks associated with storing sensitive information in a separate database.
Review the impact of third-party AI services on information security.
Recommend appropriate security controls and remediation measures.
Expand the compliance scope to cover all systems processing sensitive information.

##  Project Scope

The revised compliance scope includes the following components:

| Component | Assessment Focus |
|---|---|
| AI Chat Assistant | Security of the application and handling of sensitive information |
| Chat Transcript Database | Encryption, access restrictions, monitoring, and retention |
| Payment Processing Systems | Protection of payment card information |
| APIs and Cloud Infrastructure | Application and infrastructure security |
| Third-Party AI Providers | External service provider security risks |
| Access Controls and Audit Logs | User permissions, authentication, and activity monitoring |

### Revised Scope Statement

Vantrel's compliance scope will cover all systems that collect, process, store, or transmit patient health information and payment card data, including the AI chat assistant, transcript database, payment systems, APIs, and third-party providers.

The assessment will ensure these systems meet applicable PCI DSS and HIPAA security requirements.

##  Identified Compliance Gaps

The assessment identified seven major security gaps.

| Identified Gap | Framework | PCI DSS Requirement | HIPAA Requirement |
|---|---|---|---|
| Unencrypted chat transcripts | Both | Requirements 3 and 4 | §164.312(a), (e) |
| Payment card details stored in chat | PCI DSS | Requirement 3 | Not directly applicable |
| Unauthorized database access | Both | Requirements 7 and 8 | §164.312(a) |
| Lack of activity monitoring | Both | Requirement 10 | §164.312(b) |
| Third-party AI security risks | Both | Requirement 12 | §164.308(b) |
| Poor data retention policies | Both | Requirement 3.2 | §164.308(a)(1) |
| Insecure AI application/API | Both | Requirement 6 | §164.312(c) |

### Key Findings

**1. Unencrypted Chat Transcripts**

Sensitive patient and payment information could be exposed if chat transcripts are not adequately protected through encryption.

**2. Payment Card Information Stored in Chat**

Storing payment card details in chat conversations increases the risk of unauthorized disclosure and payment fraud.

**3. Unauthorized Database Access**

The separate chat database introduces access control concerns, particularly because it is not directly managed by the organization's security team.

**4. Lack of Activity Monitoring**

Insufficient monitoring makes it difficult to identify suspicious activities and investigate potential security incidents.

**5. Third-Party AI Security Risks**

External AI providers may introduce additional risks when processing sensitive organizational or patient information.

**6. Poor Data Retention Policies**

Without clearly defined retention and deletion policies, sensitive information may remain stored longer than necessary.

**7. Insecure AI Application and APIs**

Vulnerabilities in the AI application or its APIs could provide attackers with opportunities to access or manipulate sensitive information.

##  Recommended Security Controls

Based on the identified gaps, the following remediation measures were recommended:

| No. | Recommended Action | Security Objective |
|---|---|---|
| 1 | Encrypt all sensitive information | Protect data at rest and in transit |
| 2 | Prevent card numbers from being stored in chat transcripts | Reduce exposure of payment card information |
| 3 | Implement Role-Based Access Control (RBAC) and Multi-Factor Authentication (MFA) | Restrict unauthorized access |
| 4 | Bring the separate database under security-team monitoring | Improve visibility and threat detection |
| 5 | Conduct regular vulnerability assessments | Identify and address application weaknesses |
| 6 | Review third-party AI provider security | Reduce external service provider risks |
| 7 | Establish data retention and deletion policies | Prevent unnecessary storage of sensitive information |

##  Frameworks and Standards

### PCI DSS

The Payment Card Industry Data Security Standard provides security requirements for protecting payment account information.

In this assessment, PCI DSS was used to evaluate risks associated with payment card information stored or processed through the AI chat assistant.

Key areas considered include:

Data protection and encryption.
Secure system development.
Access control and authentication.
Security monitoring and logging.
Information security policies.

### HIPAA

The Health Insurance Portability and Accountability Act establishes requirements for protecting electronic protected health information (ePHI) handled by covered entities and business associates.

In this assessment, HIPAA was used to evaluate the protection of sensitive patient information handled through the AI chat assistant.

Key areas considered include:

Access controls.
Audit controls.
Data transmission security.
Information security management.
Business associate security considerations.

**Note:** HIPAA applicability depends on the organization's status as a covered entity or business associate and whether the information involved qualifies as ePHI.

##  Key Project Outcomes

The assessment established the need for a broader compliance scope and stronger security controls across Vantrel's environment.

Key outcomes include:

Identification of seven major security and compliance gaps.
Mapping of identified gaps to relevant PCI DSS and HIPAA requirements.
Identification of risks associated with a separately managed chat database.
Expansion of the proposed compliance scope to include the AI application, databases, APIs, payment systems, and third-party providers.
Development of seven recommended remediation actions.

### Major Takeaway

**Every system that collects, processes, stores, or transmits sensitive patient or payment information must be included in the organization's compliance assessment.**

The separate chat database represents a particularly important risk because it stores sensitive information outside the direct management of the security team.

##  Project Documentation

The original assessment document is:

Assignment on PCI DSS & HIPAA Frameworks.pdf

It contains:

Identified compliance gaps.
PCI DSS and HIPAA requirement mapping.
Revised compliance scope statement.
Recommended security controls.
Assessmemt

  


##  Author

**[Oluwasola Fadare]**

Cybersecurity | Governance, Risk & Compliance (GRC) | Information Security

GitHub: (https://github.com/<your-username>)
LinkedIn:(<www.linkedin.com/in/oluwasola-fadare-37a8181b4)
Email:(fancyfadash29@gmail.com>)

---

 If you find this project useful, consider giving the repository a star!
