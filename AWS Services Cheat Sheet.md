
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

> ℹ️ Pricing scales with usage for Developer, Business, and Enterprise plans.

