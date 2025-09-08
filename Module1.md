# 📖 CCSP Module 1 Study Sheet: Cybersecurity Basics  

---

## 1. CCSP Overview
- ISC² + Cloud Security Alliance developed CCSP.  
- **6 Domains**:  
  1. Cloud architecture & design  
  2. Cloud data security  
  3. Cloud platform & infrastructure security  
  4. Cloud application security  
  5. Cloud operations & management  
  6. Cloud legal, risk & compliance  

**Exam Tip**: Even if the cloud provider handles infrastructure, **GRC is always customer’s responsibility**.  

---

## 2. CIA Triad
- **Confidentiality**: Only authorized access (encryption, least privilege).  
- **Integrity**: Prevent unauthorized modification (hashes, digital signatures).  
- **Availability**: Ensure access when needed (backups, RAID, clustering).  

**Opposites = DAD**: Disclosure, Alteration, Destruction.  

---

## 3. Governance Principles
- **Policy**: Management intent (strategic).  
- **Standards**: Rules & consistency.  
- **Procedures**: Step-by-step actions.  
- **Guidelines/Baselines**: Supporting docs.  

**Policy Types**:  
- Regulatory (HIPAA, SOX, PCI DSS).  
- Advisory (acceptable use, PII/PHI handling).  
- Informative (awareness, company goals).  

---

## 4. Control Frameworks
Frameworks = structured methods to apply controls. Must be **consistent, measurable, standardized, comprehensive, modular**.  

**Examples**:  
- NIST 800-53 → 385+ controls, 19 families.  
- ISO 27001/27002 → International, 114 controls in 14 groups.  
- CIS Controls → 20 prioritized controls.  
- COBIT → IT governance.  
- PCI DSS → Payment card.  
- COSO → Financial reporting/internal control.  
- CMMI → Process improvement (Levels 1–5).  

**Analogy**: Wolf = threat, Hole in fence = vulnerability, Sheep = asset.  

---

## 5. NIST Cybersecurity Framework (CSF)
- Origin: **Obama EO 13636 (2013)** → voluntary.  
- **Trump EO 13800 (2017)** → mandatory for federal agencies.  

**Components**:  
1. **Core**: Functions (IPDRR → Identify, Protect, Detect, Respond, Recover) → Categories → Subcategories → References.  
2. **Tiers**: 1 = Partial, 2 = Risk-informed, 3 = Repeatable, 4 = Adaptive.  
3. **Profiles**: Current vs. Target → roadmap, gap analysis.  

**Mnemonic**: “I Play Defense, Ready & Resilient.”  

---

## 6. Regulatory Compliance
- **International Law**: Conventions, customs, principles.  
- **U.S. Law Types**: Criminal (gov prosecution), Civil/Tort (private lawsuits).  
- **Intellectual Property**: Copyright, Patents, Trademarks, Trade Secrets.  
- **Privacy Laws**: GDPR, HIPAA, SOX, GLBA, OECD, FISMA, PCI DSS.  

**Key Concepts**:  
- **Due Care** = Doing the right thing (e.g., deploy antivirus).  
- **Due Diligence** = Checking it’s maintained (e.g., update patches).  
- **Negligence** = Failure of either → liability.  
- **Senior Management = Always responsible.**  

---

## 7. Quiz Review (Sample Exam Points)
- **SOC Trust Principles**: Security, Availability, Processing Integrity, Confidentiality, Privacy.  
- **CIA Triad Pillars**: Confidentiality, Integrity, Availability.  
- **NIST CSF Functions**: Identify, Protect, Detect, Respond, Recover.  
- **Vendor lock-in**: Customer can’t migrate/leave CSP.  
- **Private Cloud**: Best for high security/privacy orgs.  
- **External Governance**: Vendors, contractors, suppliers, customers.  

---

## Flashcards (Q → A)

**Q:** What are the 3 pillars of the CIA Triad?  
**A:** Confidentiality, Integrity, Availability.  

**Q:** Opposite of CIA (DAD)?  
**A:** Disclosure, Alteration, Destruction.  

**Q:** Which framework is international with 114 controls?  
**A:** ISO 27001/27002.  

**Q:** What are the 5 NIST CSF functions?  
**A:** Identify, Protect, Detect, Respond, Recover.  

**Q:** Due care vs. due diligence?  
**A:** Due care = doing the right thing; Due diligence = ensuring/maintaining it.  

**Q:** Who is responsible for negligence in security failures?  
**A:** Senior management.  

**Q:** What are the SOC Trust Principles?  
**A:** Security, Availability, Processing Integrity, Confidentiality, Privacy.  

**Q:** Example of ensuring availability?  
**A:** Backups, clustering, RAID.  

---

## Mnemonics
- **CIA → Confidentiality, Integrity, Availability**  
- **DAD → Disclosure, Alteration, Destruction**  
- **IPDRR → Identify, Protect, Detect, Respond, Recover**  
- **SAPP → SOC Trust Principles (Security, Availability, Processing Integrity, Privacy)**  
- **“Prudent Man Principle” → Due Care**  
- **Wolf & Sheep Analogy → Threat, Vulnerability, Asset**  

---

## Quick-Check Exam Drill (Practice Q&A)

**Q1.** Which principle of the CIA triad is violated if an attacker modifies financial records?  
**A:** Integrity.  

**Q2.** What is the opposite of Availability in the DAD model?  
**A:** Destruction.  

**Q3.** In cloud security, who holds ultimate responsibility for GRC?  
**A:** The customer (enterprise).  

**Q4.** Which framework is mandated for federal agencies under Executive Order 13800?  
**A:** NIST Cybersecurity Framework (CSF).  

**Q5.** What does ISO 27001 primarily focus on?  
**A:** Information Security Management Systems (ISMS).  

**Q6.** What are the five NIST CSF functions?  
**A:** Identify, Protect, Detect, Respond, Recover.  

**Q7.** Which privacy law applies globally to EU citizens’ data, even outside the EU?  
**A:** GDPR.  

**Q8.** Define Due Care vs. Due Diligence with an example.  
**A:** Due Care = Deploy antivirus; Due Diligence = Keep it updated.  

**Q9.** Which type of policy is used to comply with HIPAA or PCI DSS?  
**A:** Regulatory Policy.  

**Q10.** Which CMMI level represents “managed” processes with metrics?  
**A:** Level 4.  

**Q11.** What does Vendor Lock-in describe?  
**A:** Difficulty moving to another cloud provider due to proprietary dependencies.  

**Q12.** What is the SOC Trust Principle missing if the answer option includes “Nonrepudiation”?  
**A:** Privacy (correct set = Security, Availability, Processing Integrity, Confidentiality, Privacy).  

**Q13.** What is the main safeguard for ensuring Integrity of data?  
**A:** Hashing, checksums, digital signatures.  

**Q14.** What are the two types of Governance (internal vs. external) examples?  
**A:** Internal = policies, roles, accountability; External = contracts, SLAs, MOUs.  

**Q15.** Senior management is sued after a breach because they ignored risk reports. Which concept applies?  
**A:** Negligence (failure of due care/diligence).  
