# CybersecurityAttorney.com-Cyber-Insurance
Cyber Insurance: What's Covered, What’s Not, and What Gets You Denied


**By Ramyar Daneshgar**  
Security Engineer & Legal Policy Researcher at CybersecurityAttorney.com

> **Disclaimer:** This article is for educational purposes only and does not constitute legal advice. If you require legal guidance specific to your organization, consult with a licensed attorney experienced in cybersecurity and data protection law.

---

## Introduction: The Role of Cyber Insurance in a Digitally Hostile World

Cyber insurance has evolved from a niche offering to a foundational component of corporate risk management. As cyberattacks become more targeted, more financially devastating, and more litigious, organizations across sectors are forced to look at cyber insurance not as a luxury, but as a necessity. Yet, despite increasing adoption, cyber insurance remains poorly understood — especially when it comes to what it covers, what it excludes, and how insurers assess and ultimately decide claims.

This comprehensive guide explains:
- Core components of modern cyber insurance policies
- Common pitfalls and exclusions
- Legal interpretations of liability and denial
- How to evaluate and negotiate policy terms
- What legal and security teams must do before and after a breach

---

## What Cyber Insurance Typically Covers

Modern cyber policies are divided into two broad categories: **First-Party Coverage** (your direct losses) and **Third-Party Coverage** (your liability to others).

### First-Party Coverage
- **Incident Response & Forensics**: Costs for hiring DFIR teams to investigate, contain, and mitigate.
- **System Restoration**: Covers rebuilding systems, restoring backups, and software remediation.
- **Business Interruption**: Replaces lost revenue due to downtime — but only if it meets the insurer’s definition of “covered cause.”
- **Ransomware Payments**: Includes ransom amount, negotiator fees, crypto transaction fees.
- **Notification & Monitoring**: Costs for notifying affected individuals, call center support, and credit monitoring.
- **Crisis Communications**: Public relations management, legal guidance for public disclosures, and brand repair.

### Third-Party Coverage
- **Regulatory Defense & Fines**: Covers legal defense and sometimes civil penalties (where insurable).
- **Data Subject Litigation**: Legal fees and settlements from class-action lawsuits.
- **Contractual Claims**: Breach of confidentiality or SLA claims from vendors or clients.
- **PCI-DSS Penalties**: Card brand fines, re-audit fees, and forensic investigations.

---

## What’s Commonly Excluded (and Often Litigated)

Insurers aggressively narrow scope through exclusions. Common ones include:

- **Acts of War / Nation-State Attacks**: Coverage may be denied if the breach is attributed to a foreign government or military operation. Example: *Merck v. ACE* challenged the application of a war exclusion in the context of NotPetya.
- **Failure to Maintain Security Controls**: If MFA, logging, or patching were claimed but not implemented, coverage may be voided.
- **Prior Knowledge**: Breaches that started before policy inception or were known but undisclosed.
- **Social Engineering Fraud**: Excluded unless specifically added as a rider.
- **Insider Threats**: Actions by employees or vendors may not be covered, especially if negligence or lack of monitoring is proven.
- **Breach of Contract**: Contractual disputes unrelated to a covered cyber event.

---

## What Gets Claims Denied

Denials don’t just stem from exclusions. They often arise from missteps in implementation or documentation.

### Misrepresentation on Application
If you claimed 24/7 monitoring, endpoint detection, or encryption during underwriting but failed to implement them — your policy may be rescinded for fraud or material misrepresentation.

### Delayed Notification
If your policy requires breach reporting within 48 hours, notifying them a week later could nullify the claim.

### Poor Documentation
Insurers need logs, incident timelines, and forensic evidence to verify the claim. Lack of documentation can reduce payouts or justify denial.

### Unauthorized Vendors
Some policies only pay if you use pre-approved vendors. Hiring your preferred DFIR team without written approval may disqualify you from reimbursement.

---

## Legal Interpretations of Liability and Shared Responsibility

Courts are increasingly asked to interpret cyber insurance language, especially around:

- **Attribution of Nation-State Attacks**: Must attribution be proven beyond doubt? Can a criminal group linked to a foreign government trigger a war exclusion?
- **Reasonable Security Standard**: What constitutes “reasonable”? Courts look to industry standards such as NIST 800-53 or ISO 27001.
- **Third-Party Liability**: If a vendor causes your breach, who is liable — you, the vendor, or both? Courts often weigh the indemnification language in contracts and whether your policy recognizes supply chain risk.

---

## Cyber Insurance Policy Review Checklist (Expanded)

The checklist below is designed as a structured legal and technical framework to help risk managers, CISOs, and in-house counsel evaluate cyber insurance policies. It ensures alignment between organizational cybersecurity controls, regulatory obligations, and insurer expectations. Each question addresses known litigation patterns, common claim denials, and coverage misalignments. Organizations should use this checklist to identify policy gaps, confirm compliance with coverage conditions, and prepare defensible documentation in the event of a claim. Legal and security teams should collaboratively review this checklist before binding a policy and on an annual renewal basis to ensure continuous alignment with evolving threats and operations.

Use this checklist when evaluating or renewing a policy:

### 1. Coverage Scope & Financial Adequacy
Cyber policies vary widely in how they allocate limits across coverage categories. Evaluate the general aggregate limit, then analyze specific sublimits for categories such as ransomware, data restoration, legal costs, and business interruption.

- **Ransomware & Extortion**: Check whether ransom payments are covered and whether the policy reimburses for extortion-related costs such as cryptocurrency transaction fees and third-party negotiators. Confirm if payments to entities under OFAC sanctions void the claim.
- **Forensics & Recovery**: Confirm whether digital forensic investigation and remediation costs (e.g., endpoint reimaging, malware reverse-engineering) are fully covered or subject to a cap.
- **Business Interruption**: Determine how downtime is measured — some policies require complete cessation of operations rather than partial loss of availability. Check if losses related to cloud service providers are included.
- **Third-Party Services**: Look for coverage of PR, call centers, and legal notification requirements — often required by state or international law.

### 2. Regulatory & Legal Compliance
Insurers take different positions on covering fines or penalties arising from data protection laws. Scrutinize both the policy wording and local law.

- **Insurable Fines**: Determine if administrative fines under GDPR, CCPA, BIPA, or HIPAA are included. In some jurisdictions, such penalties are legally uninsurable as a matter of public policy.
- **Regulatory Investigations**: Ensure the policy covers costs of responding to subpoenas, regulatory requests, or audits from authorities like the FTC, OCR, or EU DPAs.
- **Legal Defense**: Confirm whether legal counsel is reimbursed for responding to investigations, especially if the insurer restricts defense to panel firms.
- **Consent Orders & Settlements**: Verify coverage for negotiated settlements or consent orders and whether such costs fall under defense or indemnity provisions.

### 3. Policy Triggers & Definitions
Insurers rely heavily on policy definitions to determine coverage eligibility. Ambiguities here can drastically alter coverage.

- **Security Event vs. Privacy Event**: Some policies only cover events that involve confirmed data exfiltration. Broader policies may trigger on unauthorized access or system downtime.
- **Definition of "Breach"**: Must the breach be substantiated by digital forensics or is credible suspicion (e.g., alert from SIEM) sufficient?
- **Cloud & Third-Party Data**: Confirm whether incidents affecting cloud infrastructure (e.g., AWS, Azure, GCP) or SaaS providers are explicitly included. Also check if incidents at managed service providers fall under your policy.
- **Coverage for Internal Systems vs. Public-Facing Infrastructure**: Determine whether the policy covers breaches affecting DevOps environments, staging servers, or internal APIs.

### 4. Exclusions & Ambiguities
Most policies contain exclusions that narrow or entirely eliminate coverage for common threat vectors. These often mirror prior litigation outcomes.

- **Social Engineering**: BEC, phishing, and vendor impersonation schemes are usually excluded unless specifically added. Confirm inclusion of misdirected payments or fraudulent wire transfers.
- **Cyber Terrorism & War**: Review whether exclusions refer to "acts of war," "nation-state actors," or "cyberterrorism." Seek clarity on attribution standards and whether APT groups (e.g., Lazarus, Sandworm) fall under this exclusion.
- **Negligence & Insider Threats**: Some policies exclude claims caused by "gross negligence" or "intentional acts" of employees. Understand whether failure to terminate access or apply patches could trigger a denial.
- **Contractual Obligations**: Exclusions often apply to standard commercial breach of contract claims not directly tied to a security event.

### 5. Security Controls Required
Modern cyber policies often include preconditions tied to technical safeguards. Failure to comply can result in denial even for otherwise covered events.

- **Mandated Controls**: Common requirements include multi-factor authentication (MFA), endpoint detection and response (EDR), encryption at rest and in transit, and regular patching cycles (e.g., CVSS 7+ within 30 days).
- **Proof of Compliance**: Insurers may request logs, audit reports, vulnerability scans, or screenshots to validate these controls at the time of breach.
- **Attestations in Application**: If your application claimed MFA on all remote access, ensure that it was true for all covered assets.
- **Security Framework Alignment**: Align your policies with frameworks cited in policy terms (e.g., NIST CSF, ISO 27001, CIS Controls).

### 6. Claims Process
The claim submission and reimbursement process is often governed by strict procedural rules. Failure to follow protocol can forfeit payment.

- **Notification Windows**: Most policies require notification within 48–72 hours of discovery. Late reporting is a common basis for denial.
- **Authorized Vendors**: Confirm whether legal, forensic, and PR vendors must be pre-approved. If not, negotiate for freedom to use internal or trusted partners.
- **Documentation Requirements**: Insurers expect detailed breach timelines, scope of impact, affected systems, and steps taken. Retain artifacts like SIEM logs, IR plans, and board communications.
- **Consent to Incur Costs**: Some policies require insurer consent before engaging breach response firms. Understand the escalation process.

### 7. Retroactive & Tail Coverage
Coverage for incidents discovered late or after policy expiration is vital — especially for breaches with long dwell time.

- **Retroactive Date**: Review this date carefully. Claims related to breaches initiated prior to this date are not covered.
- **Known Incidents**: Even if the retroactive date is favorable, prior known incidents or weaknesses may be excluded unless disclosed.
- **Extended Reporting Period (ERP)**: Consider purchasing ERP coverage, especially during M&A or policy non-renewals. Ensure it's long enough to accommodate latent discovery (12–36 months).
- **Claims-Made vs. Occurrence Basis**: Most cyber policies are claims-made, meaning discovery and filing must occur within the policy period unless ERP is in place.

### 8. Application Truthfulness & Maintenance
Many cyber claims are denied due to inaccuracies or omissions during the application process. These are interpreted under insurance law as material misrepresentations.

- **Underwriting Integrity**: Answers to application questionnaires must be confirmed by technical personnel — not just brokers or executives.
- **Changes in Security Posture**: Some policies require the insured to notify the carrier about material changes — such as switching cloud providers or replacing security tools.
- **Audit Trail**: Retain dated copies of the final application, email confirmations, and internal review logs. These documents may be critical during claim disputes.
- **Rescission Clauses**: Understand the grounds on which a policy can be rescinded — often broader than mere fraud, and can include inadvertent misstatements.

---

## How to Strengthen Your Organization’s Cyber Insurance Posture

1. **Conduct a Gap Assessment**: Compare your current controls to the policy’s requirements. Address discrepancies proactively.
2. **Simulate a Claim**: Run a tabletop exercise involving a breach and walk through the notification and claims process.
3. **Retain Documentation**: Store application responses, evidence of security controls, and incident logs in an accessible, audit-ready format.
4. **Review Annually**: Policies should evolve with your infrastructure, threat surface, and regulatory risks.
5. **Negotiate Terms**: Ask for broader definitions, higher sub-limits, and your choice of vendors. Everything is negotiable.

---

## Conclusion

Cyber insurance is only as good as your understanding of it. Too many organizations assume that a policy guarantees coverage, only to find themselves in litigation or facing uncovered losses. By taking a strategic, legally informed approach — one that integrates security controls, regulatory understanding, and strong incident response — cyber insurance can be a vital part of a holistic risk management program.


---

## References & Further Reading
- National Association of Insurance Commissioners (NAIC) – Cybersecurity Resource Center
- FTC – Considerations for Cyber Insurance
- Merck & Co., Inc. v. ACE American Insurance Company, Docket No. UNN-L-002682-18
- Ponemon Institute – Cost of a Data Breach Report
- Coveware – Quarterly Ransomware Reports
- SANS Institute – Cyber Insurance Legal Landscape Whitepaper
- IAPP – Cyber Risk & Insurance Resources
- NIST 800-53 Framework
- Krebs on Security – Real-World Claim Denials

> **Disclaimer:** This article is provided for informational purposes only and does not constitute legal advice. For legal counsel, please consult a licensed cybersecurity attorney.
