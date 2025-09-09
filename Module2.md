# 📖 CCSP Study Guide – Module 2: Domain 1 (Cloud Concepts, Architecture & Design)

---

## 1. Cloud Computing Concepts
- **NIST 5 Characteristics**: On-demand self-service, Broad network access, Resource pooling, Rapid elasticity, Measured service.  
- **Cloud Service Models**:  
  - **IaaS** → Infrastructure as a Service (VMs, networking, storage).  
  - **PaaS** → Platform as a Service (runtime, databases, dev tools).  
  - **SaaS** → Software as a Service (apps for end-users).  
- **Key Benefits**: Agility, scalability, cost savings, pay-per-use.  

**Mnemonic:** “**OBRRM**” = On-demand, Broad, Resource pooling, Rapid elasticity, Measured.  

---

## 2. Cloud Reference Architecture
- Defined in **NIST SP 500-292**.  
- **Actors:**  
  - Cloud Service Consumer (CSC)  
  - Cloud Service Provider (CSP)  
  - Cloud Broker  
  - Cloud Carrier  
  - Cloud Auditor  
- Establishes standardized terminology and roles for secure cloud ecosystems.  

**Exam Tip:** Know the 5 actors — often tested in scenario questions.  

---

## 3. Cloud Service Deployment Models
- **Public Cloud** → Shared infrastructure, multi-tenant, cost-effective.  
- **Private Cloud** → Dedicated infrastructure, higher control/security.  
- **Hybrid Cloud** → Mix of private + public, flexible but complex.  
- **Community Cloud** → Shared among organizations with common goals (e.g., healthcare, government).  

**Design Tradeoffs:** Cost vs. security vs. compliance.  

---

## 4. Security Aspects of Virtualization
- **Hypervisor types:**  
  - Type 1 = Bare-metal (e.g., VMware ESXi, Hyper-V).  
  - Type 2 = Hosted (e.g., VirtualBox).  
- **Risks:** VM escape, VM sprawl, snapshot exposure, hypervisor compromise.  
- **Mitigations:** Hardening hypervisor, patching, limiting admin access, strong network segmentation.  

---

## 5. Principles of Secure Cloud Computing
- **Defense in Depth** → multiple layers of security.  
- **Least Privilege** → minimum required rights.  
- **Separation of Duties** → split critical tasks.  
- **Data-Centric Security** → protect data at rest, in motion, and in use.  
- **Redundancy & Availability** → failover, clustering, geo-redundancy.  
- **Secure APIs** → reduce attack surface, enforce authentication.  

---

## 6. Design Requirements
- **Business Requirements → Security Requirements → Cloud Design.**  
- **Data classification** drives encryption and access control (public, internal, confidential, restricted).  
- **Regulatory requirements** must be mapped to cloud controls (HIPAA, PCI DSS, GDPR).  
- **Service Level Agreements (SLAs)** should define uptime, RTO/RPO, penalties.  

**Exam Tip:** Always tie requirements back to **business objectives + compliance needs**.  

---

## 7. Cloud Model Boundaries
- **Shared Responsibility Model:**  
  - CSP → Security *of* the cloud.  
  - CSC → Security *in* the cloud.  
- **Isolation boundaries:** logical separation (VMs, containers, tenant networks).  
- **Data location & jurisdiction** → compliance concerns (GDPR, data sovereignty).  

---

## 8. Protecting Sensitive Information
- **Encryption:** At rest, in transit, in use.  
- **Key Management:** CSP vs. customer-owned keys (KMS, HSM).  
- **Tokenization/Masking:** Replace sensitive data with surrogates.  
- **DLP (Data Loss Prevention):** Prevent exfiltration of sensitive data.  
- **Identity & Access Management:** MFA, RBAC, JIT access.  

---

## 9. Threat Modeling
- **STRIDE model:** Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege.  
- **DREAD scoring:** Damage, Reproducibility, Exploitability, Affected Users, Discoverability.  
- **Cloud-specific threats:**  
  - Insecure APIs  
  - Insider threats  
  - Multi-tenancy risks  
  - Data breaches  
  - Misconfigured storage (e.g., S3 buckets)  

**Mitigation:** Perform continuous threat modeling, pen testing, red/blue teaming.  

---

## Flashcards (Q → A)

**Q:** What are the 5 essential characteristics of cloud computing (NIST)?  
**A:** On-demand self-service, Broad network access, Resource pooling, Rapid elasticity, Measured service.  

**Q:** Name the 5 cloud actors in NIST SP 500-292.  
**A:** Cloud Service Consumer, Cloud Service Provider, Cloud Broker, Cloud Carrier, Cloud Auditor.  

**Q:** Difference between Public and Private Cloud?  
**A:** Public = shared infrastructure for many customers; Private = dedicated for one.  

**Q:** Which hypervisor type runs directly on hardware?  
**A:** Type 1 (bare-metal).  

**Q:** Which design principle enforces minimum access rights?  
**A:** Least Privilege.  

**Q:** What is the “shared responsibility model”?  
**A:** CSP secures infrastructure *of* the cloud; CSC secures workloads *in* the cloud.  

**Q:** What is data tokenization?  
**A:** Replacing sensitive data with non-sensitive surrogates.  

**Q:** List STRIDE categories.  
**A:** Spoofing, Tampering, Repudiation, Information Disclosure, DoS, Elevation of Privilege.  

---

## Acronyms
- **IaaS** → Infrastructure as a Service.  
- **PaaS** → Platform as a Service.  
- **SaaS** → Software as a Service.  
- **CSP** → Cloud Service Provider.  
- **CSC** → Cloud Service Consumer.  
- **SLA** → Service Level Agreement.  
- **STRIDE** → Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege.  
- **DREAD** → Damage, Reproducibility, Exploitability, Affected Users, Discoverability.  

---

## Quick-Check Exam Drill (Module 2)

**[M2-Q1]** List NIST’s 5 essential cloud characteristics.  
**A:** On-demand self-service, Broad network access, Resource pooling, Rapid elasticity, Measured service.  

**[M2-Q2]** What are the 5 roles in NIST’s Cloud Reference Architecture?  
**A:** Consumer, Provider, Broker, Carrier, Auditor.  

**[M2-Q3]** Which deployment model is best for highly regulated industries requiring dedicated infrastructure?  
**A:** Private Cloud.  

**[M2-Q4]** What is VM escape?  
**A:** Attack where a VM breaks isolation and gains access to host or other VMs.  

**[M2-Q5]** Example of a secure cloud design principle?  
**A:** Separation of duties, least privilege, defense in depth.  

**[M2-Q6]** What do SLAs define?  
**A:** Service guarantees (uptime, RTO/RPO, penalties).  

**[M2-Q7]** Who is responsible for securing data stored in IaaS?  
**A:** Customer (CSC).  

**[M2-Q8]** What technique replaces sensitive data with surrogates?  
**A:** Tokenization.  

**[M2-Q9]** List STRIDE categories.  
**A:** Spoofing, Tampering, Repudiation, Information Disclosure, DoS, Elevation of Privilege.  

**[M2-Q10]** Which cloud threat arises from poor IAM configuration or excessive privileges?  
**A:** Insider threat / privilege escalation.  
