# 🧠 AWS Cloud Practitioner Certification Prep Notes

## 📘 Exam Overview

The **AWS Certified Cloud Practitioner** exam tests your understanding of:

- Core AWS services and global infrastructure
- Security and compliance within the AWS Cloud
- Billing, pricing models, and account management
- Cloud architectural principles

---

## 🌩️ Cloud Concepts

### ☁️ Cloud Deployment Models

- **Public Cloud:** Services offered over the public internet (e.g., AWS)
- **Private Cloud:** Cloud infrastructure operated solely for one organization
- **Hybrid Cloud:** Combination of public and private cloud

### ☁️ Cloud Computing Models

- **IaaS:** Infrastructure as a Service (e.g., EC2, VPC)
- **PaaS:** Platform as a Service (e.g., Elastic Beanstalk)
- **SaaS:** Software as a Service (e.g., Amazon WorkDocs)

---

## 🛠️ Core AWS Services

### 🚀 Compute

#### Amazon EC2

- Virtual servers in the cloud.
- **Instance Types:**
  - **General Purpose (t3, m5)**
  - **Compute Optimized (c5)**
  - **Memory Optimized (r5)**
  - **Storage Optimized (i3)**
  - **Accelerated Computing (p4, inf1)**

#### AWS Lambda

- Serverless compute.
- Pay per invocation.
- Max execution: 15 minutes
- Memory: 128MB to 10GB

---

### 🗄️ Storage

#### Amazon S3

- Object storage.
- 99.999999999% durability.
- Use cases: backups, hosting, data lake

##### 📂 S3 Storage Classes

| Class                     | Use Case                            | Durability    | Availability | Retrieval |
| ------------------------- | ----------------------------------- | ------------- | ------------ | --------- |
| Standard                  | Frequent access                     | 99.999999999% | 99.99%       | Instant   |
| Standard-IA               | Infrequent access                   | 99.999999999% | 99.9%        | Instant   |
| One Zone-IA               | Infrequent, single AZ               | 99.999999999% | 99.5%        | Instant   |
| Intelligent-Tiering       | Auto-tiers based on access pattern  | 99.999999999% | 99.9–99.99%  | Varies    |
| Glacier Instant Retrieval | Archive, milliseconds access        | 99.999999999% | 99.9%        | Millisec  |
| Glacier Flexible          | Archive, minutes to hours retrieval | 99.999999999% | 99.9%        | Min–Hours |
| Glacier Deep Archive      | Lowest-cost archive                 | 99.999999999% | 99.9%        | Up to 12h |

> 💡 Use lifecycle policies to automate transitions and reduce cost.

#### Amazon EBS

- Block storage for EC2.
- Types: gp3, io2, st1, sc1

#### Amazon EFS

- Managed file storage (NFS).
- Scales automatically.
- Storage tiers: Standard, IA

---

### 🛢️ Database

#### Amazon RDS

- Managed relational DBs.
- Engines: MySQL, PostgreSQL, MariaDB, Oracle, SQL Server, Aurora

#### Amazon DynamoDB

- Managed NoSQL database.
- Single-digit millisecond latency

#### Amazon Redshift

- Managed data warehouse

---

### 🔐 Security

#### IAM

- Manage users and roles
- Supports MFA, least privilege access

#### AWS Organizations

- Manage multiple AWS accounts
- Apply SCPs (Service Control Policies)

#### AWS Shield

- DDoS protection

#### AWS WAF

- Web application firewall

#### AWS KMS

- Manage encryption keys

---

### 🌐 Networking & CDN

#### Amazon VPC

- Isolated network for your resources

#### AWS CloudFront

- Global CDN for low latency content delivery

#### AWS Route 53

- DNS service
- Supports routing policies (failover, geolocation)

---

### 🔄 Management Tools

- **CloudWatch:** Monitoring and logging
- **CloudTrail:** Logs API calls
- **Trusted Advisor:** Best practice recommendations
- **Config:** Tracks configuration changes

---

### 💸 Billing & Pricing

- **Free Tier:** 12-month and always-free options
- **Pay-as-you-go:** Only pay for what you use
- **Cost Explorer:** Visualize costs
- **Budgets:** Set cost and usage thresholds
- **Pricing Calculator:** Estimate monthly costs

#### Consolidated Billing

- Combine usage across accounts

---

### 🧾 Support Plans

| Plan       | 24/7 Support | Trusted Advisor | Use Case           | Cost        |
| ---------- | ------------ | --------------- | ------------------ | ----------- |
| Basic      | No           | Core checks     | Everyone           | Free        |
| Developer  | Email only   | Core checks     | Dev/test           | $29+/month  |
| Business   | Phone/Chat   | All checks      | Production         | $100+/month |
| Enterprise | TAM, 15 min  | Concierge + All | Critical workloads | $15k+/month |

---

### 🌍 AWS Global Infrastructure

- **Regions:** Geographic locations (e.g., us-east-1)
- **Availability Zones:** Data centers in each region
- **Edge Locations:** CDN locations for CloudFront
- **Local Zones:** Extend regions for latency-sensitive workloads

---

## ✅ Services with Types or Tiers

| Service    | Tiers/Classes                  | Purpose                         |
| ---------- | ------------------------------ | ------------------------------- |
| S3         | Standard, IA, Glacier, etc.    | Cost vs access speed            |
| EC2        | Instance families (t, c, r, p) | Tailor for workload             |
| EBS        | gp3, io2, st1, sc1             | Performance vs cost             |
| Lambda     | Memory, timeout                | Fine-tune functions             |
| EFS        | Standard, IA                   | File system cost vs access      |
| RDS        | Engines: Aurora, MySQL, etc.   | Choose based on compatibility   |
| CloudFront | Edge locations, TTL            | Performance and caching control |
| Support    | Plans: Basic → Enterprise      | Support level needs             |

---
