# **CCSP Module 1: Cybersecurity Basics – Study Guide**

---

## **Outline of Lecture Notes**

1. **CCSP Overview**
2. **CIA Triad**
   - Confidentiality
   - Integrity
   - Availability
3. **Governance Principles**
   - Policies, Standards, Procedures, Guidelines, Baselines
   - Types of Policies: Regulatory, Advisory, Informative
   - Internal vs External Governance
   - GRC (Governance, Risk, Compliance)
4. **Control Frameworks**
   - Security Framework Definition
   - Key Frameworks: NIST, ISO, CIS, ITIL, COBIT, COSO, CMMI
   - Countermeasures & Risk Management
5. **NIST Cybersecurity Framework (CSF)**
   - Framework Core: Functions, Categories, Subcategories, Informative References
   - Implementation Tiers: Partial → Adaptive
   - Framework Profiles: Current & Target State
6. **Regulatory Compliance**
   - International Law & US State Law
   - Intellectual Property (IP), Patents, Trademarks, Trade Secrets
   - Privacy Laws (GDPR, OECD)
   - Incident, Breach, Data Disclosure
   - Due Care vs Due Diligence

---

## **Section Summaries, Key Terms, and Points**

### **1. CCSP Overview**
- **Summary**: The CCSP certification, developed by ISC² and CSA, addresses cloud security fundamentals. The learning path covers all six CCSP domains and includes theory, demos, and practice exams.
- **Key Points**:
  - CCSP is for professionals with some cybersecurity background.
  - Focuses on cloud security skills.
  - Six domains: Cloud Architecture, Data Security, Platform & Infrastructure Security, Application Security, Security Operations, Legal/Risk/Compliance.
- **Definitions**:
  - **CCSP** – Certified Cloud Security Professional.
  - **CSA** – Cloud Security Alliance.

---

### **2. CIA Triad**
- **Summary**: Core information security principles: Confidentiality, Integrity, Availability.
- **Definitions**:
  - **Confidentiality**: Only authorized entities can access information. Uses **least privilege** and **need-to-know**.
  - **Integrity**: Data cannot be altered without authorization; ensures authenticity and non-repudiation.
  - **Availability**: Systems are accessible and usable by authorized users when needed.
- **Key Points**:
  - Opposites of CIA are **DAD**: Disclosure, Alteration, Destruction.
  - Methods to ensure CIA:
    - Confidentiality → Encryption
    - Integrity → Hashes, digital signatures
    - Availability → Backups, RAID, redundancy
- **Key Lists**:
  - CIA → Confidentiality, Integrity, Availability
  - DAD → Disclosure, Alteration, Destruction

---

### **3. Governance Principles**
- **Summary**: Governance ensures security aligns with business goals and legal/regulatory requirements.
- **Definitions**:
  - **Policy**: Management’s expectations for protecting CIA.
  - **Standard**: Acceptable level of adherence to policy.
  - **Procedure**: Step-by-step actions to implement policy.
  - **Guideline**: Recommendations to support procedures.
  - **Baseline**: Minimum security requirements.
- **Key Points**:
  - Policies must be technology-independent.
  - Internal governance: decision-making within the organization.
  - External governance: applied to vendors, contractors, suppliers.
  - GRC = Governance, Risk, Compliance; always customer responsibility in cloud.
- **Policy Types**:
  - Regulatory → Compliance with laws (HIPAA, SOX, PCI DSS)
  - Advisory → Guidance on expected behavior
  - Informative → Inform employees; not enforceable

---

### **4. Control Frameworks**
- **Summary**: Frameworks provide structured guidance for implementing and managing security controls.
- **Definitions**:
  - **Control**: Tool, process, or mechanism to mitigate risk.
  - **Countermeasure**: Action to reduce threat exploitation of vulnerabilities.
  - **Risk**: Likelihood a threat exploits a vulnerability.
  - **Vulnerability**: Weakness exploitable by a threat.
- **Key Frameworks**:
  - **NIST 800-53/171/37**
  - **ISO 27000 series**
  - **CIS Controls**
  - **ITIL**, **COBIT**, **COSO**, **CMMI**
- **Key Points**:
  - Frameworks are consistent, measurable, standardized, comprehensive, modular.
  - CMMI Levels 1–5 define process maturity.
  - Defense-in-depth methodology maximizes security benefit.

---

### **5. NIST Cybersecurity Framework (CSF)**
- **Summary**: CSF guides organizations to assess and improve cybersecurity capabilities.
- **Definitions**:
  - **Framework Core**: Functions (IPDRR), Categories, Subcategories, Informative References.
  - **Functions (IPDRR)**: Identify, Protect, Detect, Respond, Recover.
  - **Implementation Tiers**: Partial → Adaptive (Tier 1 → Tier 4)
  - **Profiles**: Align CSF functions with organizational goals; current vs target state.
- **Key Points**:
  - CSF is voluntary for private sector but mandatory for US federal agencies (EO 13800).
  - Categories → specific activities; Subcategories → technical/management tasks.
  - Informative References → ISO, COBIT, NIST 853/171.

---

### **6. Regulatory Compliance**
- **Summary**: Ensures cloud infrastructure adheres to legal, regulatory, and privacy requirements.
- **Definitions**:
  - **Incident**: Event potentially harming CIA.
  - **Breach**: Disclosure or exposure of data.
  - **Data Disclosure**: Unauthorized acquisition of personal information.
  - **Due Care**: Duty to do the right thing (policies/procedures).
  - **Due Diligence**: Ensuring due care is followed.
- **Key Points**:
  - Laws: International, US state, criminal, civil/tort.
  - IP: Copyright, patents, trademarks, trade secrets.
  - Privacy: GDPR, OECD, EU-US Privacy Shield.
  - Negligence may lead to fines (e.g., GDPR violations).

---

## **Acronyms**

| Acronym | Meaning |
|---------|---------|
| CCSP    | Certified Cloud Security Professional |
| CSA     | Cloud Security Alliance |
| CIA     | Confidentiality, Integrity, Availability |
| DAD     | Disclosure, Alteration, Destruction |
| SOC     | Service Organization Control |
| GRC     | Governance, Risk, Compliance |
| HIPAA   | Health Insurance Portability and Accountability Act |
| SOX     | Sarbanes-Oxley Act |
| PCI DSS | Payment Card Industry Data Security Standard |
| ISO     | International Organization for Standardization |
| ITIL    | Information Technology Infrastructure Library |
| COBIT   | Control Objectives for Information and Related Technology |
| CMMI    | Capability Maturity Model Integration |
| CSF     | Cybersecurity Framework |
| GDPR    | General Data Protection Regulation |
| OECD    | Organization for Economic Cooperation and Development |

---

## **Flashcards**

**Q:** What are the three elements of the CIA triad?  
**A:** Confidentiality, Integrity, Availability ✅

**Q:** What is the opposite of confidentiality?  
**A:** Disclosure ✅

**Q:** What is due diligence?  
**A:** Actions taken to ensure due care is followed ✅

**Q:** Name the five NIST CSF functions.  
**A:** Identify, Protect, Detect, Respond, Recover ✅

**Q:** What is the purpose of an ISO 27001 certification?  
**A:** Establish an information security management system for consistent security controls ✅

**Q:** What is external governance?  
**A:** Governance applied to vendors, contractors, and suppliers ✅

---

## **Cybersecurity Basics Quiz Answers**

1. **Security, Confidentiality, Processing Integrity, Availability and Privacy** ✅  
2. **Availability** ✅  
3. **Identify, Protect, Detect, Respond, Recover** ✅  
4. **A customer may be unable to leave, migrate or transfer to an alternate CSP.** ✅  
5. **Availability, Confidentiality, Integrity** ✅  
6. **Private cloud** ✅  
7. **Data exchange partners, contractors, hosting services, on-site consultants** ✅  
8. **Confidentiality, Integrity, Availability** ✅  
9. **Confidentiality is the property that information is not disclosed to system entities (processes, users, devices) unless they have been authorized to access the information.** ✅  
10. **Availability is the timely and reliable access to and use of information by authorized users.** ✅  

---

## **Building Blocks & Exam Traps**

- **CIA vs DAD:** Always remember the opposites; questions often test them.  
- **Policy vs Standard vs Procedure:** Policies are strategic; standards and procedures are tactical.  
- **CSF Tiers:** Know the characteristics of each tier (Partial → Adaptive).  
- **Due Care vs Due Diligence:** Don’t confuse; one is responsibility, the other is assurance.  
- **Regulatory Requirements:** Memorize examples like GDPR, HIPAA, SOX, PCI DSS.  
- **Framework Mapping:** NIST CSF can reference ISO 27001, COBIT, NIST 853/171—understand these relationships.  
- **SOC Trust Principles:** Know Security, Availability, Processing Integrity, Confidentiality, Privacy (nonrepudiation is tricky).  
