# CCSP Study Guide: Module 1 - Cybersecurity Basics

This study guide is designed to help you master the key concepts and terminology from the "Mod1 - Master.txt" lecture transcript for the Certified Cloud Security Professional (CCSP) certification exam. It covers cybersecurity fundamentals, the CIA triad, governance principles, control frameworks, the NIST Cybersecurity Framework (CSF), regulatory compliance, and includes a quiz with answers and explanations to reinforce learning.

---

## Learning Objectives
1. **Describe security fundamentals** used throughout the cybersecurity industry.
2. **Define cybersecurity terms and concepts** specific to the CCSP.

---

## 1. CCSP Overview
- **Purpose**: The CCSP certification, developed by (ISC)² and the Cloud Security Alliance (CSA), addresses the demand for qualified cloud security professionals.
- **Target Audience**: Practitioners with some cybersecurity background aiming to advance their skills in cloud security.
- **Domains Covered**:
  1. Cloud Architectural Concepts and Design Requirements
  2. Cloud Data Security
  3. Cloud Platform and Infrastructure Security
  4. Cloud Application Security
  5. Cloud Security Operations and Management
  6. Cloud Legal, Risk, and Compliance Requirements
- **Study Resources**: Over 20 hours of video lessons, theory, examples, demonstrations, practice tests, and a full-length practice certification exam.

**Key Takeaway**: The CCSP learning path provides comprehensive preparation for the exam, covering both foundational and advanced cloud security concepts.

---

## 2. CIA Triad
The CIA Triad (Confidentiality, Integrity, Availability) is a foundational model for information security.

### Definitions
- **Confidentiality**: Ensures information is not disclosed to unauthorized entities (users, processes, devices).
  - **Enforcement**: Uses principles of least privilege and need-to-know.
  - **Protection**: Encryption, access controls.
  - **Opposite**: Disclosure (DAD - Disclosure, Alteration, Destruction).
- **Integrity**: Prevents unauthorized modification or destruction of information, ensuring non-repudiation and authenticity.
  - **Protection**: Checksums, hashes, digital signatures, separation of duties.
  - **Opposite**: Alteration.
- **Availability**: Ensures timely and reliable access to information and systems by authorized users.
  - **Protection**: Backups, remote sites, clustering, RAID levels.
  - **Opposite**: Destruction.

### Key Concepts
- **Security Governance**: Aligns security with organizational requirements for CIA through policies, procedures, standards, baselines, and guidelines.
- **Cybersecurity vs. Information Security**:
  - **Information Security**: Protects information in any format (paper, digital, verbal).
  - **Cybersecurity**: Focuses on protecting digital assets (networks, hardware, software).
- **Risk Management**: Cybersecurity risks impact the organization’s bottom line, similar to financial or reputational risks.
- **Threats and Vulnerabilities**: Evaluated based on their potential to compromise CIA principles.

**Key Takeaway**: The CIA Triad is the cornerstone of security programs, guiding the protection of assets through governance and compliance.

---

## 3. Governance Principles
Governance ensures organizational alignment with security and compliance objectives.

### Key Components
- **Security Policies**: Communicate management’s expectations for protecting CIA.
  - Must be technology- and solution-independent.
  - Categories:
    - **Regulatory**: Ensures compliance with industry regulations (e.g., HIPAA, GLBA, SOX, PCI DSS).
    - **Advisory**: Guides employee behavior (e.g., handling PII or PHI).
    - **Informative**: Educates employees on company goals, reporting structures, etc.
- **Supporting Elements**:
  - **Procedures**: Step-by-step instructions to achieve policy goals.
  - **Standards**: Define acceptable levels of compliance.
  - **Baselines and Guidelines**: Provide tactical support for policy implementation.
- **Compliance**: Adherence to legal, regulatory, and organizational requirements, monitored through audits and assessments.
- **Governance, Risk, and Compliance (GRC)**:
  - **Internal Governance**: Aligns with organizational vision and mission, defining decision-making authority and accountability.
  - **External Governance**: Applies to vendors, contractors, and suppliers through contracts, SLAs, MOUs, or MOAs.
  - **Customer Responsibility**: GRC and data security remain the customer’s responsibility, even in cloud environments.

**Key Takeaway**: Governance establishes strategic security policies, supported by tactical procedures and standards, to ensure compliance and risk management.

---

## 4. Control Frameworks
Control frameworks provide structured processes for implementing and managing security controls.

### Characteristics
- **Consistent**: Uniform approach to security and privacy.
- **Measurable**: Tracks progress and sets goals.
- **Standardized**: Enables comparison across organizations.
- **Comprehensive**: Covers legal and regulatory requirements.
- **Modular**: Allows tailored modifications.

### Major Frameworks
- **NIST SP 800-53**: 385 controls in 19 families, tailorable to organizational needs.
- **NIST SP 800-171**: For contractors handling controlled unclassified information.
- **ISO 27001**: International standard with 114 controls in 14 groups for information security management.
- **CIS Critical Security Controls**: 20 actionable controls to address pervasive attacks.
- **COBIT**: Focuses on IT management and governance.
- **COSO**: Supports Sarbanes-Oxley compliance for financial reporting.
- **ITIL**: Focuses on IT service management.
- **CMMI**: Process improvement methodology with five maturity levels (Initial, Repeatable, Defined, Managed, Optimizing).

### Risk Management
- **Risk**: Likelihood of a threat exploiting a vulnerability, impacting assets.
- **Vulnerability**: Weakness in an asset or safeguard (e.g., a hole in a fence).
- **Threat**: Any entity or event that could harm an asset (e.g., a wolf attacking sheep).
- **Countermeasures**: Controls to reduce threat impact or likelihood, selected via cost-benefit analysis.

**Key Takeaway**: Frameworks provide structured, measurable approaches to mitigate risks through tailored security controls.

---

## 5. NIST Cybersecurity Framework (CSF)
The NIST CSF is a voluntary framework for managing cybersecurity risks, mandated for federal agencies by Executive Order 13800.

### Components
1. **Framework Core**:
   - **Functions (IPDRR)**: Identify, Protect, Detect, Respond, Recover.
   - **Categories**: Cybersecurity outcomes tied to programmatic needs (e.g., asset management).
   - **Subcategories**: Specific activities (e.g., ID.AM-1 for asset management).
   - **Informative References**: Standards like NIST 800-53, ISO 27001, COBIT.
2. **Implementation Tiers**:
   - **Tier 1 (Partial)**: Ad hoc, reactive risk management.
   - **Tier 2 (Risk Informed)**: Management-approved practices, not organization-wide.
   - **Tier 3 (Repeatable)**: Formal policies, regularly updated.
   - **Tier 4 (Adaptive)**: Continuous improvement, proactive response to threats.
3. **Framework Profiles**:
   - **Current Profile**: Current cybersecurity outcomes.
   - **Target Profile**: Desired outcomes for risk management.
   - **Gap Analysis**: Identifies areas for improvement.

### Key Updates (CSF 1.1, April 2018)
- Added one new category and 10 new subcategories.
- Reworded 26 subcategories for clarity.
- Compatible with CSF 1.0.

**Key Takeaway**: The NIST CSF provides a flexible, outcome-driven approach to managing cybersecurity risks across functions, tiers, and profiles.

---

## 6. Regulatory Compliance
Compliance ensures adherence to legal and regulatory requirements, especially in cloud environments.

### Legal Concepts
- **International Law**: Governs relationships between countries (e.g., conventions, customs).
- **U.S. State Law**: Varies by state, with separate constitutions and courts.
- **Intellectual Property**:
  - **Copyright**: Protects original works (e.g., software, literature).
  - **Trademarks**: Protects brand identities (e.g., logos, slogans).
  - **Patents**: Protects novel, useful inventions.
  - **Trade Secrets**: Protected under the Economic Espionage Act (1996) with NDAs.
- **Privacy Laws**: Define rights to control personal information (e.g., GDPR, OECD).
- **Criminal Law**: Prohibits harmful conduct, prosecuted by the government.
- **Civil/Tort Law**: Compensates victims for harm caused by others.

### Compliance Requirements
- **Regulations**: HIPAA, GLBA, SOX, PCI DSS, GDPR.
- **GDPR Key Features**:
  - Consent for data collection.
  - 24-hour breach notification.
  - Right to access, correct, or be forgotten.
  - Data portability and privacy by design.
- **Incidents, Breaches, and Disclosures**:
  - **Incident**: Potential harm to CIA (e.g., observing credentials).
  - **Breach**: Unauthorized access or exposure (e.g., using stolen credentials).
  - **Disclosure**: Unauthorized release of data (e.g., posting online).
- **Audits**: Verify compliance (e.g., PCI DSS requires annual vulnerability scans).

### Due Care and Due Diligence
- **Due Care**: Doing the right thing (e.g., deploying antivirus, encryption).
- **Due Diligence**: Ensuring compliance through audits and monitoring.
- **Negligence**: Failure to practice due care/diligence, leading to liability.
- **Senior Management Responsibility**: Accountable for policy implementation and compliance.

**Key Takeaway**: Compliance involves understanding and adhering to legal, regulatory, and organizational requirements, with audits ensuring due care and diligence.

---

## Cybersecurity Basics Quiz with Answers
Below are the quiz questions from the transcript, with correct answers and explanations.

1. **What are the five Service Organization Control (SOC) Trust Services principles?**
   - **Correct Answer**: Security, Confidentiality, Processing Integrity, Availability, and Privacy
   - **Explanation**: SOC Trust Services principles are used to evaluate service organizations. Nonrepudiation and auditability are not part of the five principles.

2. **What portion of the CIA triad is affected if a cloud customer cannot get access to the cloud service provider?**
   - **Correct Answer**: Availability
   - **Explanation**: Inability to access services impacts availability, as it prevents authorized users from using systems when needed.

3. **The Cybersecurity Framework (CSF) Core consists of which of the following Functions?**
   - **Correct Answer**: Identify, Protect, Detect, Respond, Recover
   - **Explanation**: The CSF Core functions (IPDRR) guide organizations in managing cybersecurity risks comprehensively.

4. **Vendor lock-in describes what situation?**
   - **Correct Answer**: A customer may be unable to leave, migrate, or transfer to an alternate CSP.
   - **Explanation**: Vendor lock-in occurs when a customer is tied to a specific CSP due to data, technology, or contract constraints.

5. **Which of the following are principles of cloud security?**
   - **Correct Answer**: Availability, Confidentiality, Integrity
   - **Explanation**: These align with the CIA triad, foundational to cloud security. Scalability is a cloud feature, not a security principle.

6. **Which cloud deployment model is most suitable for a large organization with high security and privacy concerns?**
   - **Correct Answer**: Private cloud
   - **Explanation**: Private clouds offer dedicated resources and greater control, ideal for organizations with stringent security needs.

7. **External governance applies to which groups?**
   - **Correct Answer**: Data exchange partners, contractors, hosting services, on-site consultants
   - **Explanation**: External governance involves entities outside the organization, managed through contracts and SLAs.

8. **The triad security model consists of what?**
   - **Correct Answer**: Confidentiality, Integrity, and Availability
   - **Explanation**: The CIA triad is the core model for information security, not including authentication or implementation.

9. **In the CIA triad, what is confidentiality?**
   - **Correct Answer**: Confidentiality is the property that information is not disclosed to system entities (processes, users, devices) unless they have been authorized to access the information.
   - **Explanation**: Confidentiality prevents unauthorized disclosure, enforced through access controls and encryption.

10. **In the CIA triad, availability is what?**
    - **Correct Answer**: Availability is the timely and reliable access to and use of information by authorized users.
    - **Explanation**: Availability ensures systems are accessible when needed, not about preventing unauthorized access.

---

## Study Tips
1. **Focus on Key Terms**: Memorize definitions for CIA triad, governance types, and framework components.
2. **Understand Frameworks**: Compare NIST 800-53, ISO 27001, and CIS controls for their scope and application.
3. **Practice Scenarios**: Apply CIA triad principles to cloud security scenarios (e.g., vendor lock-in, data breaches).
4. **Review Compliance**: Study GDPR and other regulations for their impact on cloud security.
5. **Take Practice Tests**: Use the provided practice exams to assess readiness and identify weak areas.

**Key Takeaway**: This study guide organizes the core concepts from Module 1 into a structured format, with clear definitions, frameworks, and quiz practice to ensure exam readiness.
