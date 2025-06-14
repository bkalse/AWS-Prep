# 📘 AWS Certified AI Practitioner (AIF-C01) Study Guide  
## Domain 5: Security, Compliance, and Governance for AI Solutions (14%)

---

### 🔒 Task Statement 5.1: Explain Methods to Secure AI Systems

#### 🌐 AWS Services and Features for Security
| Service | Purpose |
|--------|---------|
| **IAM Roles & Policies** | Define access control for AWS resources. |
| **Encryption** | Protect data at rest and in transit (e.g., KMS, TLS). |
| **Amazon Macie** | Discover and protect sensitive data (e.g., PII). |
| **AWS PrivateLink** | Securely access services without exposing traffic to the public internet. |
| **AWS Shared Responsibility Model** | Clarifies security responsibilities between AWS and the customer. |

#### 📃 Source Citation & Data Origin
- **Data Lineage**: Track the flow of data through the pipeline.
- **Data Cataloging**: Organize metadata (e.g., AWS Glue Data Catalog).
- **SageMaker Model Cards**: Document model origin, purpose, and performance.

#### 📊 Secure Data Engineering Best Practices
- **Data Quality Assessment**: Ensure reliability and validity.
- **Privacy-Enhancing Technologies**: Use anonymization, differential privacy.
- **Access Control**: Implement least privilege access.
- **Data Integrity**: Protect from tampering (e.g., checksums, hashing).

#### 🔐 Security & Privacy Considerations
- **Application Security**: Protect AI apps from common exploits.
- **Threat Detection**: Use services like Amazon GuardDuty.
- **Vulnerability Management**: Regular scanning and patching.
- **Infrastructure Protection**: Network segmentation, firewalls.
- **Prompt Injection**: Guardrails for LLM inputs.
- **Encryption**: Enforce at rest (S3, EBS) and in transit (TLS).

---

### ✅ Task Statement 5.2: Recognize Governance and Compliance Regulations for AI Systems

#### 📊 Regulatory Compliance Standards
| Standard | Description |
|---------|-------------|
| **ISO** | International standards for information security and risk management. |
| **SOC** | System and Organization Controls (e.g., SOC 2 for data security and privacy). |
| **Algorithm Accountability Laws** | Regulations for fairness, transparency, and bias mitigation. |

#### ⚖️ AWS Governance & Compliance Services
| Service | Role in Governance |
|---------|------------------|
| **AWS Config** | Track configuration changes and compliance. |
| **Amazon Inspector** | Automated vulnerability scanning. |
| **AWS Audit Manager** | Automate evidence collection for audits. |
| **AWS Artifact** | Access compliance reports and documentation. |
| **AWS CloudTrail** | Monitor and log all API calls. |
| **AWS Trusted Advisor** | Provides real-time guidance on best practices. |

#### 📆 Data Governance Strategies
- **Data Lifecycle Management**: Automate data archiving and deletion.
- **Logging & Monitoring**: Use CloudWatch, CloudTrail.
- **Data Residency**: Ensure compliance with local laws.
- **Observation & Retention**: Retain logs for auditing and compliance.

#### ✍️ Governance Protocols & Frameworks
- **Policies & Cadence**: Define and review regularly.
- **Review Strategies**: Internal and third-party assessments.
- **Generative AI Security Scoping Matrix**: Scope AI projects for compliance.
- **Transparency Standards**: Disclose AI use and behavior.
- **Team Training**: Ensure awareness of compliance obligations.

---

💪 **Tip**: Prioritize encryption, access control, and governance reviews early in AI solution design to avoid costly refactors and regulatory risks later.

