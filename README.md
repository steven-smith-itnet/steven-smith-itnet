# Steven Smith<br><sub>Information Security · Data Protection · GRC · IT Audit </sub>

Information security professional with 20+ years designing, deploying, and managing network, security, and cloud infrastructure in regulated environments — now applying that engineering depth to data protection, governance, risk, and assurance.

## Background

My IT career spans building carrier-grade backbones, cloud hosting engineering and support, next-generation spine-leaf data center and software-defined network and security architectures, and all the hardware and virtualization in between: routing, switching, firewalls, load balancers, data brokers, network monitoring and telemetry, security and endpoint monitoring tools, SIEM, IPS/IDS, cloud security, docker, K8s, Linux, and open-source tooling. Many of those solutions operated under real regulatory pressure — HIPAA, PCI DSS, NERC CIP, SOX/ITGC, CMMC, NIST 800-171, and FIPS 140-2/140-3.

I have most recently worked as a **data protection engineer** focused on encryption and masking: enterprise key management and HSMs, PKI and certificate lifecycle, tokenization, database and file-level encryption, and the CI/CD, IaC, and PaC best practices that keep all of it running at scale.

Throughout, the interesting work might surprise some — it has been at the seam: partnering with internal IT auditors and GRC teams on regulatory assessments, acting as the technical liaison for audit and compliance reviews, and supporting control-readiness efforts. I have been on the build side of that seam for two decades. I am deliberately moving to the side that also **evaluates** what gets built. But I am taking more than two decades of critical thinking and engineering expertise along for the ride.


## Where I'm Aiming

Four adjacent lanes, one underlying skill set.

| Focus | What I bring |
|---|---|
| **Data protection / cryptography engineering** | KMS, HSM, PKI, encryption, tokenization, masking, key lifecycle governance — my deepest, most verifiable SME area |
| **Security engineering** | Cloud and infrastructure security, identity and access, secure architecture, automation |
| **GRC engineering** | Policy-as-code, infrastructure-as-code guardrails, continuous control monitoring, automated evidence pipelines, KPI/KRI metrics, dashboards, and executive-visible scorecards |
| **IT audit & assurance** (entry to mid-level) | CISA-backed control design and testing, framework crosswalks, risk assessment, remediation tracking — the deliberate pivot, where I'm building reps rather than claiming years |

What ties them together: I can translate complex architecture into clear control narratives, decode
an audit request into engineering tasks, and turn existing systems into continuous compliance
evidence sources instead of point-in-time screenshot exercises.

## What's Here

A portfolio built to demonstrate the work rather than describe it.

**Key management & data protection**

- [aws-kms-cloudhsm-key-management-guide](https://github.com/steven-smith-itnet/aws-kms-cloudhsm-key-management-guide) — planning, deploying, automating, and governing keys on AWS: KMS, CloudHSM, custom and external key stores
- [azure-key-vault-managed-hsm-key-management-guide](https://github.com/steven-smith-itnet/azure-key-vault-managed-hsm-key-management-guide) — the same treatment for Azure Key Vault and Managed HSM
- [gcp-cloud-kms-hsm-key-management-guide](https://github.com/steven-smith-itnet/gcp-cloud-kms-hsm-key-management-guide) — Google Cloud KMS, Cloud HSM, Cloud EKM, and Autokey
- [thales-ciphertrust-manager-install-guide](https://github.com/steven-smith-itnet/thales-ciphertrust-manager-install-guide) — CipherTrust Manager on VMware and AWS, with KMIP, CTE/CTE-U, and Splunk integration
- [certificate-expiration-monitoring-demo](https://github.com/steven-smith-itnet/certificate-expiration-monitoring-demo) — TLS/PKI discovery, inventory, alerting, and alert-fatigue reduction across PowerShell, Python, SQL, and multi-cloud IaC

**GRC engineering & control automation**

- [ita-grc-toolkit](https://github.com/steven-smith-itnet/ita-grc-toolkit) — IT controls assurance toolkit: seven modules of reusable scripts and templates in Python, Bash, PowerShell, and Ansible, with GitHub Actions running OPA/Conftest and multi-cloud guardrails
- [aws-least-privilege-compliance-checker](https://github.com/steven-smith-itnet/aws-least-privilege-compliance-checker) — automated IAM least-privilege analysis and policy-as-code guardrails mapped to SOC 2, NIST 800-53, and CIS
- [soc2-cloud-control-mapping-demo](https://github.com/steven-smith-itnet/soc2-cloud-control-mapping-demo) — SOC 2 Trust Services Criteria mapped to AWS controls, with automated evidence collection in Bash, boto3, PowerShell, and Athena SQL
- [grc-compliance-dashboard-demo](https://github.com/steven-smith-itnet/grc-compliance-dashboard-demo) — executive dashboard aggregating six program modules into KPIs/KRIs, risk trend, and remediation tracking, built dashboard-as-code

**Audit, risk & program work samples**

- [iso27001-compliance-program-demo](https://github.com/steven-smith-itnet/iso27001-compliance-program-demo) — ISMS scope, Annex A control matrix, gap analysis, and remediation plan
- [internal-isms-audit-demo](https://github.com/steven-smith-itnet/internal-isms-audit-demo) — internal ISO 27001 / SOC 2 audit: report, control checklist, and corrective action plan
- [enterprise-risk-register-demo](https://github.com/steven-smith-itnet/enterprise-risk-register-demo) — ISO 31000 / NIST SP 800-30 risk register with 5x5 scoring, heat maps, and quantitative FAIR/Monte Carlo analysis
- [vendor-security-assessment-demo](https://github.com/steven-smith-itnet/vendor-security-assessment-demo) — third-party assessment questionnaire, scoring, and TPRM automation
- [incident-response-plan-demo](https://github.com/steven-smith-itnet/incident-response-plan-demo) — NIST 800-61 / ISO 27035 / SOC 2 CC7.x runbooks, a phishing/BEC tabletop, and evidence-as-code

**Recent ISO framework course notes**

- [iso-27001-lead-auditor-notes](https://github.com/steven-smith-itnet/iso-27001-lead-auditor-notes) — ISMS
- [iso-27701-lead-auditor-notes](https://github.com/steven-smith-itnet/iso-27701-lead-auditor-notes) — privacy information management
- [iso-42001-lead-auditor-notes](https://github.com/steven-smith-itnet/iso-42001-lead-auditor-notes) — AI management systems, all 38 Annex A controls, and AI system impact assessment


## Toolbox

- **Data protection:** Thales CipherTrust Manager and CCKM, Luna HSM, Oracle Key Vault, AWS KMS/CloudHSM, Azure Key Vault/Managed HSM, GCP Cloud KMS, enterprise PKI/CA, Venafi, mTLS, TDE, tokenization, masking, FIPS 140-2/140-3
- **Automation & code:** Python, Bash, PowerShell, Ansible, Terraform, OPA/Rego, REST APIs, JSON/YAML, Git, CI/CD
- **Analytics & monitoring:** Splunk, Power BI, Tableau, SQL, pandas, KPI/KRI dashboarding
- **Identity & access:** RBAC, SAML, OAuth, AD, Okta, CyberArk, TACACS+/RADIUS, 802.1X
- **GRC platforms:** RSA Archer, AuditBoard, ServiceNow IRM
- **Frameworks:** SOC 2, ISO/IEC 27001 · 27701 · 42001, NIST CSF · 800-53 · 800-171 · 800-37 · AI RMF, PCI DSS, HIPAA, HITRUST, NERC CIP, CMMC, FedRAMP, SOX/ITGC, GDPR

## Certifications

**Held:** CISSP · CISA · Certified GRC Engineer – Auditor (CGE-AUD) · Security+ · ITIL 4 Foundation ·
CCNP Security · CCNP Enterprise · CCNA

**In progress:** CGE-P · CRISC · AIGP · CSA TAISE · AI governance coursework

## Why

Controls that exist only in a document drift the day after they're written. The engineers who built
the system usually know exactly where the evidence lives — and the people asking for that evidence
often can't reach it without them. I've spent 20 years on the building side of that gap, and I'd
rather close it than keep describing it: build controls that produce their own evidence, and be able
to sit on either side of the table when someone tests them.

## Elsewhere

- **Portfolio:** [brightridgellc.com/steven-smith-itnet](https://www.brightridgellc.com/steven-smith-itnet)
- **LinkedIn:** [in/steven-smith-itnet](https://www.linkedin.com/in/steven-smith-itnet/)
- **Credly:** [credly.com/users/steven-smith-itnet](https://www.credly.com/users/steven-smith-itnet)
- **Email:** itnetsws@gmail.com
