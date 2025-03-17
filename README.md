COSMAS KAREN EBUBECHUKWU
VUG/CSC/22/7687

1. Amazon Web Services (AWS)

AWS is the pioneer and arguably the most mature cloud computing platform. It offers a vast array of services, catering to virtually every IT need.   

Core Services:

Compute:
EC2 (Elastic Compute Cloud): Virtual servers (instances) with various operating systems and configurations.   
Lambda: Serverless computing for event-driven applications.   
Elastic Beanstalk: Platform-as-a-Service (PaaS) for deploying and managing applications.   
Containers: ECS (Elastic Container Service), EKS (Elastic Kubernetes Service), Fargate (serverless container execution)   
Storage:
S3 (Simple Storage Service): Object storage for various data types.   
EBS (Elastic Block Storage): Block-level storage volumes for EC2 instances.   
EFS (Elastic File System): Scalable file storage for EC2 instances.   
Glacier: Low cost archival storage.   
Databases:
RDS (Relational Database Service): Managed relational databases (MySQL, PostgreSQL, Oracle, SQL Server, etc.).   
DynamoDB: NoSQL database service.   
Aurora: AWS's high-performance relational database.   
DocumentDB: MongoDB compatible database.   
Networking:
VPC (Virtual Private Cloud): Isolated network environment.   
Route 53: DNS service.   
CloudFront: Content Delivery Network (CDN).   
Direct Connect: Dedicated network connection.
Machine Learning:
SageMaker: Platform for building, training, and deploying machine learning models.   
Rekognition: Image and video analysis.
Translate, Comprehend, Polly: Natural language processing services.
Analytics:
Redshift: Data warehousing.
EMR (Elastic MapReduce): Big data processing.   
QuickSight: Business intelligence.   
Kinesis: Real time data streaming.   
Developer Tools:
CodeCommit, CodeBuild, CodeDeploy, CodePipeline: DevOps tools.   
CloudFormation: Infrastructure as Code.   
Internet of Things (IoT):
IoT Core: Managed IoT platform.
Strengths:

Maturity and Breadth of Services: AWS offers the widest range of services, catering to diverse needs.   
Large Ecosystem: A vast community, extensive documentation, and numerous third-party integrations.   
Global Infrastructure: Extensive global presence with numerous data centers.   
Scalability and Reliability: Proven track record of handling massive workloads.
Strong Community support.
Weaknesses:

Complexity: The sheer number of services can be overwhelming.
Cost: While offering various pricing models, costs can become complex and unpredictable.   
Vendor Lock-in: Migrating away from AWS can be challenging due to its proprietary services.
Use Cases:

Web hosting and application deployment.
Big data analytics and data warehousing.
Machine learning and artificial intelligence.
IoT applications.
Enterprise IT infrastructure.
Disaster recovery and backups.
2. Google Cloud Platform (GCP)

GCP is known for its strengths in data analytics, machine learning, and containerization.

Core Services:

Compute:
Compute Engine: Virtual machines.   
Kubernetes Engine (GKE): Managed Kubernetes service.
Cloud Functions: Serverless functions.
App Engine: PaaS for web applications.   
Storage:
Cloud Storage: Object storage.
Persistent Disk: Block storage.   
Cloud Filestore: Managed file storage.   
Databases:
Cloud SQL: Managed relational databases (MySQL, PostgreSQL, SQL Server).   
Cloud Spanner: Globally distributed, scalable relational database.
Cloud Firestore: NoSQL document database.
Bigtable: NoSQL wide column database.
Networking:
Virtual Private Cloud (VPC): Isolated network.   
Cloud DNS: DNS service.   
Cloud CDN: Content Delivery Network.   
Cloud Interconnect: Dedicated network connection.
Machine Learning:
Vertex AI: Unified platform for machine learning.
Cloud Vision API, Cloud Natural Language API, Cloud Translation API: Pre-trained machine learning APIs.   
TensorFlow: Google's open-source machine learning framework.
Analytics:
BigQuery: Data warehousing.   
Dataflow: Data processing and streaming.
Dataproc: Managed Hadoop and Spark.   
Looker: Business intelligence.
Developer Tools:
Cloud Build, Cloud Deploy: CI/CD services.   
Cloud Source Repositories: Private git repositories.   
Strengths:

Data Analytics and Machine Learning: Strong capabilities in big data and AI.
Kubernetes Leadership: Leading provider of managed Kubernetes services.
Pricing: Competitive and often more granular pricing.
Strong Network: Google's global network infrastructure.
Innovation: Google is known for pushing the boundaries of cloud technology.   
Weaknesses:

Smaller Market Share: Compared to AWS and Azure, GCP has a smaller market share.
Fewer Services: While expanding, GCP's service portfolio is still smaller than AWS.
Less Mature in some areas: Some services are newer than the competition.
Use Cases:

Big data analytics and data warehousing.
Machine learning and AI applications.
Containerized applications and microservices.
Web and mobile application development.
Real time data processing.
3. Microsoft Azure

Azure is deeply integrated with the Microsoft ecosystem and is popular among enterprises using Microsoft technologies.   

Core Services:

Compute:
Virtual Machines: Virtual servers.   
Azure Kubernetes Service (AKS): Managed Kubernetes.   
Azure Functions: Serverless functions.
App Service: PaaS for web applications.   
Storage:
Blob Storage: Object storage.
Disk Storage: Block storage.
Azure Files: Managed file storage.   
Databases:
Azure SQL Database: Managed SQL Server.   
Azure Cosmos DB: NoSQL database.
Azure Database for MySQL, PostgreSQL, MariaDB: Managed open source databases.   
Networking:
Virtual Network: Isolated network.   
Azure DNS: DNS service.   
Azure CDN: Content Delivery Network.   
ExpressRoute: Dedicated network connection.
Machine Learning:
Azure Machine Learning: Platform for building and deploying machine learning models.   
Cognitive Services: Pre-built AI APIs.   
Analytics:
Azure Synapse Analytics: Data warehousing and big data analytics.   
Azure Data Factory: Data integration.   
Azure Databricks: Apache Spark-based analytics.   
Power BI: Business intelligence.
Developer Tools:
Azure DevOps: DevOps tools.
GitHub integration.
Internet of Things (IoT):
Azure IoT Hub: Managed IoT platform.   
Strengths:

Integration with Microsoft Ecosystem: Seamless integration with Windows Server, .NET, and other Microsoft products.
Enterprise-Grade Security: Strong security and compliance features.
Hybrid Cloud Capabilities: Strong support for hybrid cloud deployments.
Large Enterprise adoption: Many large enterprises already use microsoft products, so azure is a natural extension.   
Strong support for windows based workloads.
Weaknesses:

Complexity: Similar to AWS, Azure can be complex.
Pricing: Pricing can be complex and vary by region.   
Linux support, while improving, has historically lagged behind.
Use Cases:

Windows-based application deployment.
Enterprise IT infrastructure.
Hybrid cloud deployments.
Data warehousing and business intelligence.
.NET application development.
Active directory integration.
Key Considerations When Choosing a Cloud Provider:

Workload Requirements: Match the provider's strengths to your specific needs.
Cost: Evaluate pricing models and compare costs.
Security and Compliance: Ensure the provider meets your security and compliance requirements.
