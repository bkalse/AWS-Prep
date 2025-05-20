
# 🧠 AWS Services Cheat Sheet (Cloud Practitioner)

## ☁️ Compute
| Service | Description |
|---------|-------------|
| EC2 | Virtual servers in the cloud |
| Lambda | Run code without managing servers |
| Elastic Beanstalk | Deploy and manage apps automatically |
| ECS | Docker container orchestration |
| EKS | Managed Kubernetes service |
| Lightsail | Simple cloud servers for smaller apps |
| Batch | Run batch computing jobs |
| Outposts | AWS services in your data center (on-prem) |
| Wavelength | Run apps at the edge of 5G networks |
| Local Zones | Run latency-sensitive apps closer to users |
| App Runner | Simple way to run containerized apps |
| AWS Fargate | Serverless compute engine for containers |

## 🗄️ Storage
| Service | Description |
|---------|-------------|
| S3 | Object storage with various storage classes |
| S3 Glacier | Archive storage with retrieval options |
| EBS | Block storage for EC2 |
| EFS | Scalable file storage for use with EC2 |
| FSx | Managed Windows and Lustre file systems |
| Storage Gateway | Hybrid storage integration (on-prem to cloud) |
| AWS Backup | Centralized backup across AWS services |

| Storage Class               | Description                                               | Use Case                                |
| --------------------------- | --------------------------------------------------------- | --------------------------------------- |
| **S3 Standard**             | High durability, availability, and performance            | Frequently accessed data                |
| **S3 Intelligent-Tiering**  | Automatically moves data between tiers based on usage     | Unknown or changing access patterns     |
| **S3 Standard-IA**          | Infrequent Access – lower cost, but charged for retrieval | Backup, disaster recovery               |
| **S3 One Zone-IA**          | Like Standard-IA, but stored in a single AZ               | Re-creatable infrequently accessed data |
| **S3 Glacier Instant**      | Low-cost, immediate retrieval for archive data            | Long-term archive with fast access      |
| **S3 Glacier Flexible**     | Archive with minutes to hours retrieval time              | Archives with less frequent access      |
| **S3 Glacier Deep Archive** | Lowest-cost storage, retrieval in 12 hours                | Archival of rarely accessed data        |
| **S3 Reduced Redundancy**   | ❌ Deprecated, not recommended anymore                     | (Legacy)                                |


## 🛠️ Developer Tools
| Service | Description |
|---------|-------------|
| CodeCommit | Git repositories |
| CodeBuild | Build and test code |
| CodeDeploy | Automate application deployments |
| CodePipeline | CI/CD automation pipeline |
| Cloud9 | Cloud-based IDE |
| X-Ray | Debug and trace applications |
| AWS CodeStar | Unified UI for software development |
| AWS CloudShell | Browser-based shell for managing AWS resources |

## 🧬 Database
| Service | Description |
|---------|-------------|
| RDS | Managed relational database (MySQL, PostgreSQL, etc.) |
| Aurora | High performance MySQL/PostgreSQL-compatible DB |
| DynamoDB | Fast NoSQL key-value and document DB |
| ElastiCache | In-memory cache (Redis/Memcached) |
| Redshift | Managed data warehouse |
| Neptune | Graph database |
| DocumentDB | MongoDB-compatible document DB |
| QLDB | Immutable ledger database |
| Timestream | Time series database |
| Database Migration Service (DMS) | Migrate databases to AWS |

## 🌐 Networking & Content Delivery
| Service | Description |
|---------|-------------|
| VPC | Isolated virtual network |
| Route 53 | Scalable DNS and domain registration |
| CloudFront | Content delivery network (CDN) |
| API Gateway | Create and manage APIs |
| Direct Connect | Dedicated network link to AWS |
| Global Accelerator | Improve global app availability/performance |
| App Mesh | Microservice communication layer |
| PrivateLink | Securely access services over AWS network |

## 🔒 Security, Identity & Compliance
| Service | Description |
|---------|-------------|
| IAM | Manage users, groups, roles, and permissions |
| Cognito | User sign-up/sign-in and authentication |
| Organizations | Manage multiple AWS accounts |
| Artifact | On-demand access to AWS compliance reports |
| KMS | Key Management Service (encryption) |
| Shield | DDoS protection |
| WAF | Web Application Firewall |
| Secrets Manager | Manage and rotate credentials securely |
| Macie | Detect PII in S3 using ML |
| Inspector | Analyze security vulnerabilities |
| Security Hub | Central security dashboard |
| Control Tower | Set up and govern a secure AWS environment |
| AWS Directory Service | Managed Microsoft AD |
| Amazon GuardDuty | Threat detection and continuous security monitoring |
| AWS Detective | Investigate security issues |

## 📊 Management & Governance
| Service | Description |
|---------|-------------|
| CloudWatch | Monitoring and observability |
| CloudTrail | Log and audit API activity |
| Config | Record and evaluate AWS resource configurations |
| Systems Manager | Manage EC2 and on-prem resources |
| Trusted Advisor | Recommendations for best practices |
| Service Catalog | Catalog of approved IT services |
| License Manager | Track and manage software licenses |
| Control Tower | Automate AWS account setup |
| CloudFormation | Infrastructure as code |
| Launch Wizard | Guide to deploy enterprise apps |

## 💰 Billing & Cost Management
| Service | Description |
|---------|-------------|
| AWS Budgets | Set and track budgets |
| Cost Explorer | Analyze cost and usage |
| Pricing Calculator | Estimate costs of AWS services |
| Consolidated Billing | Combine billing across accounts |
| Billing Dashboard | Central place to view AWS bills |

## 📢 Application Integration
| Service | Description |
|---------|-------------|
| SQS | Message queuing |
| SNS | Publish-subscribe messaging |
| EventBridge | Event bus to connect services |
| Step Functions | Coordinate multiple services with workflows |
| AppFlow | SaaS data integration |

## 📈 Analytics
| Service | Description |
|---------|-------------|
| Athena | Query S3 data with SQL |
| Glue | Serverless ETL (Extract, Transform, Load) |
| Lake Formation | Build a secure data lake |
| QuickSight | Business intelligence and data visualizations |
| Redshift | Petabyte-scale data warehouse |
| Data Pipeline | Move and transform data |
| EMR | Managed big data framework (Spark/Hadoop) |
| Kinesis | Processing and analyzing real-time streaming data at scale |
| MKS| Managed Apache Kafka Cluster |
| QuickSight | BI Tool for creating visualizations and dashboards |
| Amazon OpenSearch Service (Elasticsearch) | Managed search and analytics |

## 🤖 Machine Learning
| Service | Description |
|---------|-------------|
| SageMaker | Build, train, and deploy ML models |
| Comprehend | Natural language processing (NLP) |
| Rekognition | Image and video analysis |
| Translate | Language translation |
| Lex | Build conversational interfaces (chatbots) |
| Polly | Text-to-speech |
| Forecast | Time-series forecasting |
| Personalize | Build recommendation engines |
| Amazon Textract | Extract text and data from documents |
| Amazon Augmented AI (A2I) | Human review for ML predictions |
| Amazon Kendra | Intelligent search service |

## 🚚 Migration & Transfer
| Service | Description |
|---------|-------------|
| Snowball | Physical device to transfer large data |
| Snowmobile | Exabyte-scale data transfer truck |
| Migration Hub | Track migrations |
| Application Migration Service | Lift-and-shift app migration |
| Transfer Family | SFTP, FTPS, and FTP transfers to S3 |

## 👨‍💼 End User Computing
| Service | Description |
|---------|-------------|
| WorkSpaces | Virtual desktops in the cloud |
| AppStream 2.0 | Stream desktop apps from AWS |

## 🛠️ AWS Support Plans Comparison
| Feature / Plan                         | **Basic** (Free) | **Developer** | **Business** | **Enterprise** |
|----------------------------------------|------------------|--------------------------|--------------------------|-------------------------------|
| **24/7 Support for Critical Issues**   | ❌               | ❌                       | ✅                       | ✅                            |
| **Response Time - General Guidance**   | —                | < 24 hrs                 | < 24 hrs                 | < 24 hrs                      |
| **Response Time - System Impaired**    | —                | < 12 hrs                 | < 12 hrs                 | < 4 hrs                       |
| **Response Time - Production Down**    | —                | —                        | < 1 hr                   | < 1 hr                        |
| **Response Time - Business Critical**  | —                | —                        | —                        | < 15 mins                     |
| **AWS Trusted Advisor**                | Limited          | Core Checks              | Full Checks              | Full Checks                   |
| **AWS Health Dashboard**               | ✅               | ✅                       | ✅                       | ✅                            |
| **Architecture Support**               | ❌               | ❌                       | General Guidance         | Tailored Guidance             |
| **Account Management (TAM)**           | ❌               | ❌                       | ❌                       | ✅                            |
| **Support Channels**                   | Docs, Forums     | Email                    | Chat, Phone, Email       | Chat, Phone, Email            |

## 🌍 AWS Services by Availability Level
| **Service**                   | **Availability Scope**                          | **Notes**                                                         |
| ----------------------------- | ----------------------------------------------- | ----------------------------------------------------------------- |
| **EC2 (Instances)**           | **AZ-level**                                    | Launched in a specific AZ; failures isolated to that AZ           |
| **EBS (Volumes)**             | **AZ-level**                                    | Tied to a single AZ; cannot attach across AZs                     |
| **EFS (File Storage)**        | **Region-level**                                | Accessible across multiple AZs within a region                    |
| **S3 (Object Storage)**       | **Region-level**                                | Automatically replicated across multiple AZs                      |
| **RDS (Single-AZ/Multi-AZ)**  | AZ-level (Single), Region-level (Multi-AZ)      | Choose based on high availability needs                           |
| **Aurora**                    | **Region-level**                                | Supports multi-AZ and cross-region replication                    |
| **DynamoDB**                  | **Region-level**                                | Fully managed and region-scoped with optional global tables       |
| **Lambda**                    | **Region-level**                                | Runs in multiple AZs within a region                              |
| **ECS (Fargate/EC2)**         | **AZ-level (EC2)** / **Region-level (Fargate)** | EC2 tasks tied to AZ, Fargate managed across AZs                  |
| **EKS (Kubernetes)**          | **Region-level**                                | Nodes are in AZs; control plane is region-scoped                  |
| **S3 Glacier / Deep Archive** | **Region-level**                                | Built on top of S3, same durability model                         |
| **VPC**                       | **Region-level**                                | Subnets are created per AZ                                        |
| **CloudFront (CDN)**          | **Global**                                      | Edge locations globally                                           |
| **Route 53 (DNS)**            | **Global**                                      | Highly available global DNS                                       |
| **CloudWatch**                | **Region-level**                                | Metrics and logs are region-scoped                                |
| **IAM**                       | **Global**                                      | Accounts and permissions span all regions                         |
| **AWS Organizations**         | **Global**                                      | Used for managing multi-account setups                            |
| **SageMaker**                 | **Region-level**                                | Training and hosting occur in specific regions                    |
| **Elastic Load Balancer**     | **Region-level**                                | Distributes traffic across AZs within a region                    |
| **Global Accelerator**        | **Global**                                      | Provides a global IP that routes to endpoints in multiple regions |

> **AZ-level**: Service operates within a single Availability Zone (e.g., EC2, EBS)  
> **Region-level**: Service spans multiple AZs within a region for high availability (e.g., S3, Lambda)  
> **Global**: Service operates across all regions (e.g., IAM, Route 53)

## 🛡️ AWS Security Services Comparison
| **Service**       | **Purpose**                                                       | **Scope**               | **Integrated With**                        | **Typical Use Case**                             |
| ----------------- | ----------------------------------------------------------------- | ----------------------- | ------------------------------------------ | ------------------------------------------------ |
| **AWS Shield**    | Protects against **DDoS attacks**                                 | Global (for Edge + ELB) | CloudFront, ALB/NLB, Route 53              | Prevent volumetric attacks on apps               |
| **AWS WAF**       | **Web Application Firewall** to block malicious traffic           | Region-level or Edge    | ALB, CloudFront, API Gateway               | Block IPs, SQL injection, XSS                    |
| **GuardDuty**     | **Threat detection** using ML and threat intel feeds              | Region-level            | VPC, CloudTrail, DNS logs, IAM             | Detect compromised instances, anomalous activity |
| **AWS Detective** | **Investigates and visualizes** security findings                 | Region-level            | GuardDuty, AWS Config, CloudTrail          | Root cause analysis of suspicious activity       |
| **AWS Cognito**   | **User authentication and authorization**                         | Region-level            | API Gateway, Lambda, App Clients           | Sign-up/sign-in for users, federated identities  |
| **Security Hub**  | **Aggregates and prioritizes** findings from AWS security tools   | Region-level            | GuardDuty, Inspector, WAF, 3rd party tools | Central dashboard to track security posture      |
| **Inspector**     | **Automated vulnerability management** for EC2 & container images | Region-level            | EC2, ECR, Lambda                           | Scan for CVEs and misconfigurations in workloads |

## 🔎 Summary by Focus Area
| **Security Area**             | **Best Service(s)**                                    |
| ----------------------------- | ------------------------------------------------------ |
| **DDoS protection**           | AWS Shield (Standard for free, Advanced for paid tier) |
| **App-layer protection**      | AWS WAF                                                |
| **Threat detection**          | Amazon GuardDuty                                       |
| **Investigation/Forensics**   | AWS Detective                                          |
| **Identity management**       | Amazon Cognito                                         |
| **Security posture overview** | AWS Security Hub                                       |
| **Vulnerability scanning**    | Amazon Inspector                                       |
