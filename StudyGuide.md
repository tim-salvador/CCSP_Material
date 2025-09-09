# CCSP Study Guide

The Certified Cloud Security Professional (CCSP) certification, offered by ISC2, validates expertise in cloud security architecture, design, operations, and compliance. This study guide is based on the official CCSP exam outline effective since August 1, 2022 (with minor updates in November 2023). As of September 9, 2025, the exam is currently in a 3-hour linear format with 125 multiple-choice questions, requiring a passing score of 700/1000. Starting October 1, 2025, it will transition to a variable-length Computerized Adaptive Testing (CAT) format with 100-150 questions.

The exam covers six domains. This guide breaks down each domain with its weight, subtopics, and key study notes, including explanations, concepts, and tips. For preparation, use official ISC2 resources, the CCSP CBK, practice exams, and related certifications like CCSK. Study tips: Focus on understanding concepts, not memorization; practice with real-world cloud scenarios (e.g., AWS, Azure, GCP); join study groups; allocate time based on domain weights.

## Domain 1: Cloud Concepts, Architecture and Design (17%)

This domain covers foundational cloud knowledge and security design principles. Study focus: Understand cloud models, roles, and how to integrate security from the start.

- **1.1 - Understand cloud computing concepts**
  - Cloud computing definitions: On-demand delivery of IT resources via the internet with pay-as-you-go pricing, as defined by NIST SP 800-145.
  - Cloud computing roles and responsibilities (e.g., cloud service customer, cloud service provider, cloud service partner, cloud service broker, regulator): CSP provides services; CSC consumes them; brokers facilitate.
  - Key cloud computing characteristics (e.g., on-demand self-service, broad network access, multi-tenancy, rapid elasticity and scalability, resource pooling, measured service): Multi-tenancy shares resources among users; elasticity allows quick scaling.
  - Building block technologies (e.g., virtualization, storage, networking, databases, orchestration): Virtualization enables multi-tenancy via hypervisors; orchestration tools like Kubernetes manage containers.

- **1.2 - Describe cloud reference architecture**
  - Cloud computing activities: Include provisioning, monitoring, and management.
  - Cloud service capabilities (e.g., application capability types, platform capability types, infrastructure capability types): IaaS provides infrastructure, PaaS platforms, SaaS applications.
  - Cloud service categories (e.g., Software as a Service (SaaS), Infrastructure as a Service (IaaS), Platform as a Service (PaaS)): SaaS like Office 365; IaaS like EC2; PaaS like Heroku.
  - Cloud deployment models (e.g., public, private, hybrid, community, multi-cloud): Public is open; private is dedicated; hybrid combines both.
  - Cloud shared considerations (e.g., interoperability, portability, reversibility, availability, security, privacy, resiliency, performance, governance, maintenance and versioning, service levels and service-level agreements (SLA), auditability, regulatory, outsourcing): Ensure portability to avoid vendor lock-in; SLAs define uptime guarantees.
  - Impact of related technologies (e.g., data science, machine learning, artificial intelligence (AI), blockchain, Internet of Things (IoT), containers, quantum computing, edge computing, confidential computing, DevSecOps): AI in cloud requires secure data handling; IoT increases attack surfaces.

- **1.3 - Understand security concepts relevant to cloud computing**
  - Cryptography and key management: Use encryption for data at rest/transit; manage keys with HSMs.
  - Identity and access control (e.g., user access, privilege access, service access): Implement IAM with least privilege.
  - Data and media sanitization (e.g., overwriting, cryptographic erase): Ensure data deletion meets standards like NIST 800-88.
  - Network security (e.g., network security groups, traffic inspection, geofencing, zero trust network): Zero trust assumes no trust by default.
  - Virtualization security (e.g., hypervisor security, container security, ephemeral computing, serverless technology): Secure hypervisors against escapes; containers with tools like Docker Security.
  - Common threats: DDoS, data breaches, misconfigurations.
  - Security hygiene (e.g., patching, baselining): Regular patching and baseline configurations prevent vulnerabilities.

- **1.4 - Understand design principles of secure cloud computing**
  - Cloud secure data lifecycle: Create, store, use, share, archive, destroy with security controls.
  - Cloud-based business continuity (BC) and disaster recovery (DR) plan: Use cloud replication for high availability.
  - Business impact analysis (BIA) (e.g., cost-benefit analysis, return on investment (ROI)): Identify critical assets and recovery priorities.
  - Functional security requirements (e.g., portability, interoperability, vendor lock-in): Design for easy migration.
  - Security considerations and responsibilities for different cloud categories (e.g., Software as a Service (SaaS), Infrastructure as a Service (IaaS), Platform as a Service (PaaS)): Shared responsibility model—CSP secures infrastructure, CSC secures data.
  - Cloud design patterns (e.g., SANS security principles, Well-Architected Framework, Cloud Security Alliance (CSA) Enterprise Architecture): AWS Well-Architected includes security pillar.
  - DevOps security: Integrate security in CI/CD pipelines (DevSecOps).

- **1.5 - Evaluate cloud service providers**
  - Verification against criteria (e.g., International Organization for Standardization/International Electrotechnical Commission (ISO/IEC) 27017, Payment Card Industry Data Security Standard (PCI DSS)): Check certifications for compliance.
  - System/subsystem product certifications (e.g., Common Criteria (CC), Federal Information Processing Standard (FIPS) 140-2): Ensure crypto modules are FIPS-validated.

## Domain 2: Cloud Data Security (20%)

Focus on protecting data in cloud environments. Study tips: Learn encryption methods and data lifecycle management.

- **2.1 - Describe cloud data concepts**
  - Cloud data life cycle phases: Create, store, use, share, archive, destroy.
  - Data dispersion: Data spread across regions for redundancy.
  - Data flows: Map how data moves between services.

- **2.2 - Design and implement cloud data storage architectures**
  - Storage types (e.g., long-term, ephemeral, raw storage): Ephemeral for temporary data; long-term like S3 Glacier.
  - Threats to storage types: Unauthorized access, data corruption.

- **2.3 - Design and apply data security technologies and strategies**
  - Encryption and key management: Client-side vs. server-side encryption.
  - Hashing: For integrity checks.
  - Data obfuscation (e.g., masking, anonymization): Mask PII for testing.
  - Tokenization: Replace sensitive data with tokens.
  - Data loss prevention (DLP): Scan and block sensitive data exfiltration.
  - Keys, secrets and certificates management: Use vaults like AWS Secrets Manager.

- **2.4 - Implement data discovery**
  - Structured data: Databases like SQL.
  - Unstructured data: Files, emails.
  - Semi-structured data: JSON, XML.
  - Data location: Identify where data resides.

- **2.5 - Plan and implement data classification**
  - Data classification policies: Public, confidential, etc.
  - Data mapping: Inventory data assets.
  - Data labeling: Tag data for handling rules.

- **2.6 - Design and implement Information Rights Management (IRM)**
  - Objectives (e.g., data rights, provisioning, access models): Control access post-distribution.
  - Appropriate tools (e.g., issuing and revocation of certificates): Use digital signatures.

- **2.7 - Plan and implement data retention, deletion, and archiving policies**
  - Data retention policies: Comply with laws like GDPR.
  - Data deletion procedures and mechanisms: Secure erase.
  - Data archiving procedures and mechanisms: Move to cold storage.
  - Legal hold: Preserve data for litigation.

- **2.8 - Design and implement auditability, traceability, and accountability of data events**
  - Definition of event sources and requirement of event attributes (e.g., identity, Internet Protocol (IP) address, geolocation): Log who, what, when.
  - Logging, storage and analysis of data events: Use SIEM tools.
  - Chain of custody and non-repudiation: Ensure evidence integrity.

## Domain 3: Cloud Platform & Infrastructure Security (17%)

Covers securing cloud infrastructure. Study: Risk analysis and controls.

- **3.1 - Comprehend cloud infrastructure and platform components**
  - Physical environment: Data centers.
  - Network and communications: VPCs, APIs.
  - Compute: VMs, containers.
  - Virtualization: Hypervisors.
  - Storage: Block, object.
  - Management plane: Consoles, APIs.

- **3.2 - Design a secure data center**
  - Logical design (e.g., tenant partitioning, access control): Multi-tenant isolation.
  - Physical design (e.g., location, buy or build): Redundant sites.
  - Environmental design (e.g., Heating, Ventilation, and Air Conditioning (HVAC), multi-vendor pathway connectivity): Power backups.
  - Design resilient: Fault-tolerant architectures.

- **3.3 - Analyze risks associated with cloud infrastructure and platforms**
  - Risk assessment (e.g., identification, analysis): Use frameworks like NIST.
  - Cloud vulnerabilities, threats and attacks: Side-channel attacks.
  - Risk mitigation strategies: Controls like encryption.

- **3.4 - Plan and implementation of security controls**
  - Physical and environmental protection (e.g., on-premises): Access controls.
  - System, storage and communication protection: Firewalls, encryption.
  - Identification, authentication and authorization in cloud environments: MFA, RBAC.
  - Audit mechanisms (e.g., log collection, correlation, packet capture): CloudTrail.

- **3.5 - Plan business continuity (BC) and disaster recovery (DR)**
  - Business continuity (BC) / disaster recovery (DR) strategy: RTO/RPO definitions.
  - Business requirements (e.g., Recovery Time Objective (RTO), Recovery Point Objective (RPO), recovery service level): Calculate based on BIA.
  - Creation, implementation and testing of plan: Regular drills.

## Domain 4: Cloud Application Security (17%)

Focus on secure app development in cloud. Study: SDLC, threat modeling.

- **4.1 - Advocate training and awareness for application security**
  - Cloud development basics: Serverless, microservices.
  - Common pitfalls: Insecure APIs.
  - Common cloud vulnerabilities (e.g., Open Web Application Security Project (OWASP) Top-10, SANS Top-25): Injection, broken auth.

- **4.2 - Describe the Secure Software Development Life Cycle (SDLC) process**
  - Business requirements: Align security with goals.
  - Phases and methodologies (e.g., design, code, test, maintain, waterfall vs. agile): Agile integrates security iteratively.

- **4.3 - Apply the Secure Software Development Life Cycle (SDLC)**
  - Cloud-specific risks: API exposures.
  - Threat modeling (e.g., STRIDE, DREAD, ATASM, PASTA): Identify threats like spoofing.
  - Avoid common vulnerabilities during development: Secure coding practices.
  - Secure coding (e.g., OWASP ASVS, SAFECode): Verification standards.
  - Software configuration management and versioning: Git with security scans.

- **4.4 - Apply cloud software assurance and validation**
  - Functional and non-functional testing: Performance, security.
  - Security testing methodologies (e.g., blackbox, whitebox, static, dynamic, SCA, IAST): SAST for code analysis.
  - Quality assurance (QA): Automated tests.
  - Abuse case testing: Simulate attacks.

- **4.5 - Use verified secure software**
  - Securing application programming interfaces (API): OAuth, rate limiting.
  - Supply-chain management (e.g., vendor assessment): Check for vulnerabilities.
  - Third-party software management (e.g., licensing): SBOMs.
  - Validated open-source software: Scan for risks.

- **4.6 - Comprehend the specifics of cloud application architecture**
  - Supplemental security components (e.g., WAF, DAM, XML firewalls, API gateway): WAF blocks web attacks.
  - Cryptography: Encrypt comms.
  - Sandboxing: Isolate apps.
  - Application virtualization and orchestration (e.g., microservices, containers): Kubernetes security.

- **4.7 - Design appropriate Identity and Access Management (IAM) solutions**
  - Federated identity: SAML, OpenID.
  - Identity providers (IdP): Okta, Azure AD.
  - Single sign-on (SSO): Reduce passwords.
  - Multi-factor authentication (MFA): Add layers.
  - Cloud access security broker (CASB): Monitor cloud usage.
  - Secrets management: Rotate credentials.

## Domain 5: Cloud Security Operations (16%)

Operational aspects of cloud security. Study: Monitoring, incident response.

- **5.1 - Build and implement physical and logical infrastructure for cloud environment**
  - Hardware specific security configuration requirements (e.g., HSM and TPM): Secure boot.
  - Installation and configuration of management tools: Orchestrators.
  - Virtual hardware specific security configuration requirements (e.g., network, storage, memory, CPU, Hypervisor type 1 and 2): Isolate VMs.
  - Installation of guest operating system (OS) virtualization toolsets: Secure guest OS.

- **5.2 - Operate and maintain physical and logical infrastructure for cloud environment**
  - Access controls for local and remote access (e.g., RDP, SSH, console-based access mechanisms, jumpboxes, virtual client): Bastion hosts.
  - Secure network configuration (e.g., VLAN, TLS, DHCP, DNSSEC, VPN): Encrypt traffic.
  - Network security controls (e.g., firewalls, IDS, IPS, honeypots, vulnerability assessments, network security groups, bastion host): Layered defense.
  - OS hardening through baselines, monitoring and remediation (e.g., Windows, Linux, VMware): CIS benchmarks.
  - Patch management: Automated updates.
  - Infrastructure as Code (IaC) strategy: Terraform with security checks.
  - Availability of clustered hosts (e.g., distributed resource scheduling, dynamic optimization, storage clusters, maintenance mode, HA): Failover.
  - Availability of guest OS: Backups.
  - Performance and capacity monitoring (e.g., network, compute, storage, response time): Tools like CloudWatch.
  - Hardware monitoring (e.g., disk, CPU, fan speed, temperature): Alerts.
  - Configuration of host and guest OS backup and restore functions: Snapshots.
  - Management plane (e.g., scheduling, orchestration, maintenance): Secure APIs.

- **5.3 - Implement operational controls and standards (e.g., ITIL, ISO/IEC 20000-1)**
  - Change management: Approve changes.
  - Continuity management: BC plans.
  - Information security management: ISMS.
  - Continual service improvement management: Metrics.
  - Incident management: Response processes.
  - Problem management: Root cause.
  - Release management: Deploy securely.
  - Deployment management: Automation.
  - Configuration management: CMDB.
  - Service level management: SLAs.
  - Availability management: Uptime.
  - Capacity management: Scaling.

- **5.4 - Support digital forensics**
  - Forensic data collection methodologies: Chain of custody.
  - Evidence management: Preservation.
  - Collect, acquire, and preserve digital evidence: Tools like EnCase.

- **5.5 - Manage communication with relevant parties**
  - Vendors: Contracts.
  - Customers: Reporting.
  - Partners: Collaboration.
  - Regulators: Compliance.
  - Other stakeholders: Transparency.

- **5.6 - Manage security operations**
  - Security operations center (SOC): 24/7 monitoring.
  - Intelligent monitoring of security controls (e.g., firewalls, IDS, IPS, honeypots, network security groups, AI): AI for anomaly detection.
  - Log capture and analysis (e.g., SIEM, log management): Splunk.
  - Incident management: IR plans.
  - Vulnerability assessments: Scanning tools.

## Domain 6: Legal, Risk and Compliance (13%)

Legal and compliance in cloud. Study: Regulations, contracts.

- **6.1 - Articulate legal requirements and unique risks within the cloud environment**
  - Conflicting international legislation: Data sovereignty.
  - Evaluation of legal risks specific to cloud computing: Jurisdiction.
  - Legal framework and guidelines: Laws like CCPA.
  - eDiscovery (e.g., ISO/IEC 27050, CSA Guidance): Preserve evidence.
  - Forensics requirements: Cloud-specific challenges.

- **6.2 - Understand privacy issues**
  - Difference between contractual and regulated private data (e.g., PHI, PII): PHI under HIPAA.
  - Country-specific legislation related to private data (e.g., PHI, PII): EU GDPR.
  - Jurisdictional differences in data privacy: Transfers via SCCs.
  - Standard privacy requirements (e.g., ISO/IEC 27018, GAPP, GDPR): Privacy by design.
  - Privacy Impact Assessments (PIA): Evaluate risks.

- **6.3 - Understand audit process, methodologies, and required adaptations for a cloud environment**
  - Internal and external audit controls: SOC 2 reports.
  - Impact of audit requirements: Resource allocation.
  - Identify assurance challenges of virtualization and cloud: Visibility.
  - Types of audit reports (e.g., SSAE, SOC, ISAE): SOC 1/2/3.
  - Restrictions of audit scope statements (e.g., SSAE, ISAE): Defined controls.
  - Gap analysis (e.g., control analysis, baselines): Identify deficiencies.
  - Audit planning: Scope, objectives.
  - Internal information security management system: ISO 27001.
  - Internal information security controls system: Controls framework.
  - Policies (e.g., organizational, functional, cloud computing): Alignment.
  - Identification and involvement of relevant stakeholders: Collaboration.
  - Specialized compliance requirements for highly-regulated industries (e.g., NERC/CIP, HIPAA, HITECH, PCI): Sector-specific.
  - Impact of distributed IT model (e.g., diverse geographical locations and crossing over legal jurisdictions): Multi-jurisdiction compliance.

- **6.4 - Understand implications of cloud to enterprise risk management**
  - Assess providers risk management programs (e.g., controls, methodologies, policies, risk profile, risk appetite): Due diligence.
  - Difference between data owner/controller vs. data custodian/processor: Controller decides, processor handles.
  - Regulatory transparency requirements (e.g., breach notification, SOX, GDPR): 72-hour notification.
  - Risk treatment (i.e., avoid, mitigate, transfer, share, acceptance): Strategies.
  - Different risk frameworks: NIST, ISO 31000.
  - Metrics for risk management: KPIs.
  - Assessment of risk environment (e.g., service, vendor, infrastructure, business): Ongoing.

- **6.5 - Understand outsourcing and cloud contract design**
  - Business requirements (e.g., SLA, MSA, SOW): Define terms.
  - Vendor management (e.g., vendor assessments, vendor lock-in risks, vendor viability, escrow): Audits.
  - Contract management (e.g., right to audit, metrics, definitions, termination, litigation, assurance, compliance, access to cloud/data, cyber risk insurance): Exit clauses.
  - Supply-chain management (e.g., ISO/IEC 27036): Third-party risks.

## Additional Resources and Tips
- Official ISC2 CCSP CBK and self-study guide.
- Practice with ISC2 official practice tests.
- Free resources: CSA CCM, NIST cloud publications.
- Study time: 3-6 months, 2-3 hours daily.
- Join ISC2 community forums for discussions.
