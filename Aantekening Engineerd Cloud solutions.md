# Engineering Cloud Solutions:
- [Engineering Cloud Solutions:](#engineering-cloud-solutions)
- [Introduction](#introduction)
- [To Do](#to-do)
  - [Leerstof](#leerstof)
  - [Labs](#labs)
- [Cloud Particionar](#cloud-particionar)
  - [Module 1](#module-1)
    - [Interact with AWS](#interact-with-aws)
    - [Moving to the cloud](#moving-to-the-cloud)
  - [Module 2](#module-2)
    - [Price model](#price-model)
    - [how do you pay](#how-do-you-pay)
    - [Opslag reserveren](#opslag-reserveren)
    - [AWS Organizations](#aws-organizations)
    - [Support plans](#support-plans)
  - [Module 3](#module-3)
    - [AWS Regions](#aws-regions)
    - [Availability Zone](#availability-zone)
    - [Data center](#data-center)
    - [AWS infrastructure features](#aws-infrastructure-features)
    - [AWS foundation services](#aws-foundation-services)
  - [Module 4](#module-4)
    - [Security of cloud](#security-of-cloud)
    - [Identity and Access Management (IAM)](#identity-and-access-management-iam)
  - [Module 5](#module-5)
    - [Internet gateway](#internet-gateway)
    - [NAT gateway](#nat-gateway)
    - [VPC endpoint](#vpc-endpoint)
    - [AWS transit gateway](#aws-transit-gateway)
    - [Security groups](#security-groups)
    - [Custom security groups](#custom-security-groups)
    - [Network access control list (ACL)](#network-access-control-list-acl)
    - [Custom network ACL](#custom-network-acl)
    - [Content deliver network (CDN)](#content-deliver-network-cdn)
  - [Module 6](#module-6)
    - [Amazon EC2 storage options](#amazon-ec2-storage-options)
    - [AWS Elastic Beanstalk](#aws-elastic-beanstalk)
  - [Module 7](#module-7)
    - [Block storage versus object storage](#block-storage-versus-object-storage)
  - [Module 8](#module-8)
    - [Module 9](#module-9)
      - [Best practices:](#best-practices)
    - [Module 10](#module-10)
- [Cloud architecting](#cloud-architecting)
  - [Module 4](#module-4-1)
  - [Module 5](#module-5-1)
    - [Data base consirations](#data-base-consirations)
  - [Module 6](#module-6-1)
    - [Acritectural need](#acritectural-need)
      - [Network Access control list:](#network-access-control-list)
  - [Module 7](#module-7-1)
    - [AWS site-to-site VPN <br>](#aws-site-to-site-vpn-)
    - [AWS Direct Connect (DX)](#aws-direct-connect-dx)
    - [Connecting VPCs](#connecting-vpcs)
  - [Module 8](#module-8-1)
  - [Module 9](#module-9-1)
    - [Amazon EC2 auto scaling](#amazon-ec2-auto-scaling)
    - [Autoscaling RDS](#autoscaling-rds)
  - [Module 10](#module-10-1)
    - [Cloud front](#cloud-front)
    - [AWS Systems Manager](#aws-systems-manager)
    - [AWS OpsWorks](#aws-opsworks)
    - [AWS Elastic Beanstalk](#aws-elastic-beanstalk-1)
  - [Module 11](#module-11)
- [Services in AWS](#services-in-aws)
  - [Compute services](#compute-services)
    - [Amazon EC2](#amazon-ec2)
    - [Amazon EC2 (Elastic Compute Cloud) Auto Scaling](#amazon-ec2-elastic-compute-cloud-auto-scaling)
    - [AWS Lambda](#aws-lambda)
    - [AWS Elastic Beanstalk](#aws-elastic-beanstalk-2)
    - [Amazon ECS (Elastic Container Registry)](#amazon-ecs-elastic-container-registry)
    - [Amazon EKS (Elastic Kubernetes Service)](#amazon-eks-elastic-kubernetes-service)
    - [Amazon ECR (Elastic Container Service)](#amazon-ecr-elastic-container-service)
    - [AWS Fargate](#aws-fargate)
  - [Security, identiy and Compliance services](#security-identiy-and-compliance-services)
    - [AWS IAM (Identity and Access Management)](#aws-iam-identity-and-access-management)
    - [AWS organizations](#aws-organizations-1)
    - [Amazon Cognito](#amazon-cognito)
    - [AWS Shield](#aws-shield)
    - [AWS artifact](#aws-artifact)
    - [AWS KMS (Key Management Service)](#aws-kms-key-management-service)
  - [Storage Services](#storage-services)
    - [Amazon S3](#amazon-s3)
    - [Amazon S3 Glacier](#amazon-s3-glacier)
    - [Amazon EFS](#amazon-efs)
    - [Amazon EBS](#amazon-ebs)
  - [Database services](#database-services)
    - [Amazon RDS (Relational Database Service)](#amazon-rds-relational-database-service)
    - [Amazon DynamoDB](#amazon-dynamodb)
    - [Amazon Redshift](#amazon-redshift)
    - [Amazon Aurora](#amazon-aurora)
  - [AWS networking and content delivery services](#aws-networking-and-content-delivery-services)
    - [Amazon Virtual Private Cloud (Amazon VPC)](#amazon-virtual-private-cloud-amazon-vpc)
    - [Elastic Load Balancing](#elastic-load-balancing)
    - [AWS Cloud Front](#aws-cloud-front)
    - [AWS Transit Gateway](#aws-transit-gateway-1)
    - [Amazon Route 53](#amazon-route-53)
    - [AWS Direct conect](#aws-direct-conect)
    - [AWS VPN](#aws-vpn)
  - [AWS Cost management services](#aws-cost-management-services)
    - [AWS Cost and usage Report](#aws-cost-and-usage-report)
    - [AWS Budget](#aws-budget)
    - [AWS Cost explorer](#aws-cost-explorer)
  - [AWS managed and governance services](#aws-managed-and-governance-services)
    - [AWS Management console](#aws-management-console)
    - [AWS config](#aws-config)
    - [Amazon CloudWatch](#amazon-cloudwatch)
    - [AWS Autscaling](#aws-autscaling)
    - [AWS Command line interface](#aws-command-line-interface)
    - [AWS Trusted advisor](#aws-trusted-advisor)
    - [AWS Well-architected Tool](#aws-well-architected-tool)


# Introduction
Deep dive in AWS cloud solutions </br>
AZ-900 certficaat halen in eigen tijd

Week 3 Pracital exam 1, voorbeeld praktijk toets
Open vragen op theorie toets

# To Do

## Leerstof
- [x] Module 1
- [x] Module 2
- [x] Module 3
- [x] Module 4
- [x] Module 5
- [x] Module 6
- [x] Module 7 
- [x] Module 8
- [x] Module 9
- [x] Module 10

## Labs

- [x] Lab 1
- [x] Lab 2
- [ ] Lab 3
- [ ] Lab 4
- [x] Lab 5
- [x] Lab 6

# Cloud Particionar
## Module 1

- What is cloud?
  - Cloud computing on-demand via the internet pay-as-you-go
- What are web services:
  - A web service piece of software available over the internet with a standardized format -- such as JSON, XML --- for the request and respone wordt een application programming interface (API) gebruikt.

### Interact with AWS

- AWS Management Consule
  - Easy to use graphical interface
- Command Line Interface (AWS CLI)
  - Access to services by deiscrete commands or scripts
- Software Development Kits (SDKs)
  - Access services directly from code (such as Java, Python and others)

All three options are built on a commen REST like API serves.

### Moving to the cloud

AWS Cloud Adoption Framewerk (AWS CAF) provide guidance nad best practices to help organization moving to the cloud. 
AWS CAF is organized into six perspectives each perspective consist of sets of capabilities.

Six core perspectives
- Business
  - Business
    - IT is aligned with business needs
  - People
    - Training, staffing and organization changes to build an agile organization
  - Governance
    - Skills and process align IT strategy and goals with business strategy and goals.
- Technical
  - Platform
    - understand and communicate the nature of IT systems and their ealtions shitp. Describing the architecture of the targget state environment
  - Security 
    - Meet the organization security objectives
  - Operations
    - Defining how day-to-day , quarter-to-quarter and year-to-year business will be conducted


Similarities between AWS and traditional IT <br>

Route 53 DNS server off AWS

## Module 2

### Price model

Het prijs model is als volgt opgebouwd:
- Compute
  - Charger per hour / second (Second Linux only)
  - Varies by instance type
- Storage
  - Charged typically per GB
- Data tranfer
  - Outbound is aggregated and charged
  - Inbound has no charge (with some exceptions)
  - Charged typically per GB

### how do you pay

Op de volgende manieren kan betaald worden:
- Pay for what you use
- Pay less when you reserve
- Pay less when you use more and as AWS grows

###  Opslag reserveren

Er zijn drie opties om capiciteit te reserveren je kan tot 75% korting krijgen:
- All Upfrond Reserved Istance (AURI) hiermee krijg je de grootste korting
- Partial Upfront Reserver INstance (PURI) hiermee krijg je een lagere korting
- No Upfront Payment Reserved Instance (NURI) hiermee krijg je de kleinste korting


### AWS Organizations
The main benefits of AWS Organizations are:
- Centrally managed access policies acress multiple AWS accounts
- Controlled access to AWS services
- Automated AWS account creation and management
- Consolidated billing across multiple AWS accounts

Key features and benefits:
- Policy-based account management
- Group based account management
- Application programming interface (API) that automate account management
- Consolidated billing

### Support plans
- Basic
- Develper
- Business
- Enterprise

## Module 3

AWS global infrastructe designed to deliver **flexibe, reliable, scalabe** and **secure** cloud computing with high-quality **global network performance**.

Op dit moment zijn er 22 AWS regions 

### AWS Regions
Een AWS region is a geogrpahical area
- Data replicatoin acros regions is controlled by you
- Communication between REgions uses AWS backbone network infra structure

Een AWS region bestaat uit twee of meer Availability Zones, een Availbality zones bestaat weer uit een of meer data centers. 

Data in een region zij geïsoleerd van elkaar, en zullen ook nooit automatisch naar een andere region gaan.  

### Availability Zone
- Elke region heeft meerde availability zones
- Elke availability zone is een volledig geïsoleerd
- Designed for fault isolation

### Data center
- A customer choses a Availability zone instead of a data center 
- Datacenters a designer for security 
- A datacenter has redundant power, networking and connectivity
- Consist typically of 50.000 to 80.000 physical servers
- Each location is carefully evaluted to mitigate environmental risks
- Data center locations are not disclosed
- In case of failure, automated processes move data traffic away from the affected area. 
- AWS uses custom netowkr equipmentent sources from multiple original device manufactureers (ODMs)


AWS has a global network of 187 point of presence.
176 edge location
11 regional edge caches

Amazon Clouud front is a content delivery network (CND) used to distrubte content to end users to reduce latency. 
Amazon Route 53 is a DNS service. Requests going to to either one of these services will be routed to the nearest edge location automatically in order to lower latency. 
AWS Point of Presence arelocated in most of the major cities (69 cities in total) across 30 countries around the world. By continouusly measuring internet connectivity, performance andcomputing to find the bestway to route request. The Points of presence deliver a better near real-time user experience. They are used by many AWS services. 

Regional edge caches are used default with Amazon CloudFront. Regional edge cahces are used when content when you have content that is not accessed frequently enough to remain in an edge location. 

### AWS infrastructure features

- Elasticity and scalabiltiy
  - Elastic infrastructure
    - Dynamic adaption of capacity
  - Scalable infrastructure
    - adapts to accommodate growth  
- Fault-tolerance
  - Continues operation properly in the presence of a failure
  - Built-in redundancy of components
- High availability 
  - High level of operational performance
  - Minimized downtime
  - No human intervention
  
### AWS foundation services
  - Compute (Virutal, automatic scaling, and load balancing)
  - Networking
  - Storage (object, block and archive)

## Module 4

### Security of cloud

AWS responsibility
- Physical security of data centers
  - Controlled, need-based access
- Hardware and software infrastructure
  - Storage decommissioning, host operating system (OS) access logging, and auditing
- Network infrastructure
  - Intrusion detection
- Virtualization infrastructure
  - Instance isolation

Customer responsibility
- Amazon EC2 OS
  - Including patching, maintenance
- Applications
  - Passwords, role-based access, etc.
- Security group configuration
- OS or host-based firewalls 
  - Including intrusions detection or prevention systems
- Network configurations
- Account management
  - Login and permission settings for each user. 

Infrastructure as a Service (IaaS)
- Customer has more flexibility over configuring networking and storage settings
- Customer is responsible for managing more aspects of the security
- Customer configures the access controls

Platform as a Service (PaaS)
- Customer does not need to manage the underlying infrastructure
- AWS handles the operating sytem, database patching, firewall configuration, and disaster recovery
- Customer can focus on manageing code or data

Software as a Service (SaaS)
- Software is centrally hosted
- Licensed on a subscription model or pay-as-you-go basis
- Services are typically accessed via web browser, mobile app, or application programming interface (API)

### Identity and Access Management (IAM)

- Use IAM to manage access to AWS resources
  - A resource is an enity in an AWS account tha you can work with
  - Example; An EC2 instance or an Amazon S3 bucket
- Define fine grained access rights
  - Who can access the resource
  - Which resources can be accessed and what can the user do to the resource
  - How resources can be accessed

Essential components:
- IAM User: A person or application that can authenticate with an AWS account
- IAM Group: A collection of IAM users that are grandted identical authorization
- IAM policy: The document that defines which resources can be accessed and the level of access to each resource
- IAM role: Useful mechanism to grant a set of permissions for amking AWS service requests

Authenticate as an IAM USer
- Programmatic access:
  - Authenticate using:
    - Access key ID
    - Secret access key
  - Provides AWS CLI and AWS SDK access

AWS management Console access:
- Authenticate usig
  - 12-dagit account ID or alias
  - IAM user name
  - IAM password
- If enalbed, MFA

IAM policies
- An IAM policy is a document that defines permissions
  - Enables fine-grained access control
- Two types of policies - identity based and resource based
- Identity based policies:
    - Attach a policy to an IAM User, IAM group or IAM role
  - Policies specify:
    - Actions that may be performed by the entity
    - Actions that may not be performed by the entity
  - A single policy can be attached to multiple entities
  - A single entity can have multiple policies attached to it.
- Resource based polcies
  - Attached to a resource
  - Always an inline policy
 
IAM role characteristics:
- Provides temporary security credentials
- Is not uniquely associated with one person
- Is assumable by a person, application, or service
- Is often used to delegate access
Use cases: 
- Provide AWS resources with access to AWS service
- Provide access to externally authenticated users
- Provide access to third parties
- Switch role to access resources in-
  - Your AWS account
  - Any other AWS account (cross-account access)

Best practises:
- Create an IAM ADMIN account
- Lock away the root user credential
- IAM admin user for the following up task


IAM policies are stored in AWS as JSON documents. Identity-based polcies are poliy docuemnts that you attach to a user or role. It includes multiple statement, AWS applies a logical OR across the sttements when it evalutes them.
The following are common elements found in an IAM policy document:
- Version: Specify the version of the policy language that you want to use. As a best practice, use the latest 21-10-17 version.
- Statement: Use this main policy element as a container for the following elements. You can include more than one statement in a policy
- Effect: Use Allow or Deny to indicate whether the policy allows or denies access
- Principel: If you create a resource-based policy, you must indicate the account, user, role, or federated user that you would like to allow or deny access to.  If you are creating an IAM permission policy to attatch to a user or role, you cannot include this elemnt. The principal is implied as that user or role.
- Action: Include a list of actions that the policy allows or denies
- Resource: If you create an IAM permission policy, you must specify a list of resources to which the actions apply. If you create a resource-based policy, this element is optional.
- Condition (optional): Specify the circumstances where the policy grants permissions.


<br>

## Module 5

### Internet gateway

An internet gateway is the gateway from a public subnet in a VPC to the internet. The internetgateway is scalable, redundant and highly available. It allows a connection from outside from AWS to the public subnet in AWS.

### NAT gateway
A NAT gateway enables you that a private subnet can connect to het internet or other AWS services. It doesn't allow a connection from outside AWS (Internet).

### VPC endpoint
A VPC endpoint enables you that you can privately connect your VPC to supported AWS services and VPC endpint services that are powered by AWS privatelink. There are two types of VPC endpoint:
- an interface VPC endpoint
- Gateway endpoints 

### AWS transit gateway 
With VPC peering you need to maintain an connection with every service with a point-to-point connection. To solve this problem and make it easier to maintain. You can use AWS transit gateway, you only need to create and manage a single connection from the central gateway into each VPC, on-premise data center, or remote office across your network. A transit gateway acts as a hub that control how traffic is routed among all the connected networks.

### Security groups

A security group acts a virtual firewall for you instance, and it have rules that controls inbound an outbound traffic. The default security groups deny all inbound traffic and allow all outbound traffic. The security groups are statefull. 

### Custom security groups
In a custom security groups you can specify allow rules, but not deny rules. All rules are evaluated before the decision to allow traffic.

### Network access control list (ACL)

A Network ACL is an optional layer of security for your Amazon VPC. It acts as a firewall for controlling traffic in and out of one or more subnets. Each subnet in your VPC must be associated with a network ACL. If not it will automatically associated with the default network ACL. You can associate a network ACL with multiple subnets; however, a subnet can be associated with only one network ACL at a time. 

### Custom network ACL

Custom network ACLs deny all inbound and outbound traffic until you addrules. You can specify both allow and deny rules. 
Rules are evaluated in number order, starting with the lowest number.

### Content deliver network (CDN)
CDN is a globally distributed system of caching server
Caches copies of commonly requested files (Static content)
Delivers a local copy of the requested content from a nearby cache edge point of Presence
Accelerates delivery of dynamic content 
Improves application performance and scaling

## Module 6

### Amazon EC2 storage options

- Amazon Elastic Block store (Amazon EBS)
  - Durable, block level storage volumes
  - You can stop the instance and start it again, and the data will still be there
- Amazon EC2 instance store 
  - Ephemeral storage is provided on disks that are attached to the host computer where the EC2 instance is running
  - If the instance stops, data stored here is deleted
- Other option for storage (not for the root volume)
  - Mount an Amazon Elastic File system (Amazon EFS)
  - Connect to Amazon S3 

### AWS Elastic Beanstalk

- Easy way to get web applications up and running
- a Managed service that automaticlly handles
  - Infrastructure provisioning and configuration
  - Deployment
  - Load balancing
  - Automatic scaling
  - Health monitoring
  - Analysis and debugging
  - Logging

## Module 7

### Block storage versus object storage

- Block storage
  - Change on block (piece of the file) that contains the chracter
- Object storage
  - Entire file must be updated


## Module 8

Amazon RDS support six databases:
- MySQL
- Amazon Aurora
- Microsoft SQL server
- PostgreSQL
- MariaDB
- Oracle

### Module 9

#### Best practices:
- Identity and Access Management:
  - Define requirements for identity and access management
  - Secure AWS account root user
  - Enforce use of multi-factor authentication
  - Integrate with centralized federation provider
  - Enforce password requirements
  - Rotate credentials regularly
  - Audit credentials periodically
- Operational excellence design principles
  - Perform operations as code
  - Make frequent, small, reversible changes
  - Refine operations procedures frequently
  - Anticipate failure
  - Learn from all operational events and failures
- Security design principles:
  - Implement a strong identity foundation
  - Enable traceability
  - Apply security at all layers
  - Automate security best practices
  - Protect data in transit and at rest
  - Keep people away from data
  - Prepare for security events
- Reliability design principles:
  - Automatically recover from failure
  - Test recovery procedures
  - Scale horizontaly to increase aggregate workload availability
  - Stop guessing capacity
  - Manage change in automation
- Performance efficiency design principles
  - Democratize advanced technologies
  - Go global in minutes
  - Use serverless architectures
  - Experiment more often
  - Consider mechanical sympathy
- Cost optimization design principles
  - Implement Cloud financial management
  - Adopt a consupmtion model
  - Measure overall efficiency
  - Stop spending money on undifferentiated heavy lifting
  - Analyze and attribute expenditure

AWS trusted advisor looks at your entire AWS environment and gives you recommendations in five categories:
- Cost optimization
- Performance
- Security
- Fault tolerance
- Service limits

### Module 10

Types of load balancers 
- Application Load Balancer
  - Load balancing of HTTP and HTTPS traffic
  - Routes traffic to targets based on content of request
  - Provides advanced request routing targeted at the delivery of modern appicatoin architectures, including microservices and containers
  - Operates at the application layer (OSI layer 7)
- Network Load Balancer
  - Load balacning of TCP, UDP and TLS traffic where extreme performance is required
  - Routes traffic to targets based on IP protocol data
  - Can handle millions of requests per second while maintaining ultra-low latencies
  - Is optimized to handle sudden and volatile traffic patterns
- Classic Load Balancer
  - Load balancing of HTTP, HTTPS, TCP and SSL traffic
  - LOAD balancing across multiple EC2 instances
  - Operates at both the application and transport layers

# Cloud architecting

## Module 4

To provision an EC2 instance you must take decisions regarding its configuration details. The main parameters that you must specify to launch a secure instance include:

- Amazon Mahcine Image (AMI): An AMI defines the base software configuration for an instance and is used by Amazon EC2 to launch the instance.
- Instance Type: An instance type defines a combination of CPU, memory, storage and networking capacity that provides a certain level of compute capability to run an application.
- Network placement andaddressing: When you launch an isntance,  you can speicfy the appropriate network placement and addressing to provide the network access and security that you want.
- Assumed role: Optionally, you can attach an AWS IAM role, which grants permissions for accessing AWS services to applications that run on the instance or user that are connected to the instance.
- User data: You can further initialize or customize instnace configuration by specifying a user data script. This script automatically runs when the instance is launched.
- Storage: You must specify the type of storage that will be used ot store the root or boot volume of the instance.
- Security group: You must also configure a new security group or use an existing one. The security group defines which ports network traffic is allowed on. 
- Key pair: A key pair is typically also specified at launch. The key pair is used for SSH connections or for establishing RDP access to the instance. 

When you launch an EC2 instance, you must choose an AMI and an instance type.

There are three ami approaches:
- Full AMI: The applications and all dependencies are pre-installed, which shortens boot times but increased build times. Full AMIs typically have a shortes lifespan. Consider your rollback stategy.
- Hyberd (partially configurerd) AMIs- Only prerequisite software and utilities are pre-installed, which leads to a longer shell life for the AMI. This approach provides a balance between boot speed and build time. Rollbacks become easier
- OS-only AMI: This approach is fully configurable over time and shortens build times. However itmakes your EC2 isntance alow to boot all rquired-installations and configurationmust be run at boot tie.


When placing an EC2 instances you have the same considerations

When you launch a new EC2 instance, the default behavior of Amazon EC2 is to minimize correlated failures by spreading out new instances across underlying hardware. You can use *placement groups* to influence the palcement of a group of *interdependet* instances so they meet the needs of your workload.

Depending on the type of workload you can creat eaplacement group by using one of the following placement strategies:
- Cluster: Packs instances close together inside an Availability Zone. This strategy enables workloads to achieve low-latency network performance.
- Partition: Spreads your instances across logical partitions so that groups of instances in one partition do not share the underlying hardware with groups of instances in different partitions.
- Spread: Strictly places a small group of instances across distinct underlying hardware to reduce correlated failures. 
- 

## Module 5
### Data base consirations

To choose the best Database you have to think about the following considerations:

- Scalability
  - How much throughput is needed?
  - Will the chosen solution be able to scale up alter, if needed? 
- Total storage requirements
  - How large does the database need to be?
  - Will it need to store GB, TB or petabytes of data?
- Object size and type
  - Do you need to store simple data structures, large data objects, or both?
- Durability
  - What level of data durability, data availability, and recoverability is required?
  - Do regulatory obligations apply?

There are two database options avaible:
- Relational
  - Microsfot SQL
  - Oracle
  - MySQL
- Non-Relational
  - MongoDB
  - Cassandra
  - Redis

Relational:
- Benefits
  - Ease of use
  - Data integrity
  - Reduced data storage
  - Common language (SQL)
- Ideal 
  - Need strict scheme rules, ACID (Atomic, consitent, isolated and durable) compliance and data quality enforcement
  - Do not need extreme read/write capacity
  - Do not need extreme performance

Non-relational database type
  - Benefits
    - Flexibility
    - Scalability
    - High performance
    - Highly functional API's
- Ideal
  - Database must scale horizontally to handle massive data volume
  - Data does not lend itself well to traiditnoal schemas
  - Read/write rates exceed what can be economically supported through traiditonal RDBMS  

Securing Amazon RDS databases:
Recommendations
- Run the RDs in a Virtual private cloud (VPC)
  - Provides service isolation and IP firewall protection
- Use AWD IAM policies for authentication and access
  - Permissions determine who is allowed to manage Amazon RDS resources
- Use security groups to control what IP addresses or Ec2 instances can connect to your databases
  - By default, network access is disabled
- Use SSL for encryption in transit
- Use Amazon RDS encryption on DB instances and snapshots to secure data at rest
- Use the security features of your DB engine to control who can log in to the databases on a DB instance.
- Configure event notifications to alert your when important Amazon RDS events occur

Securing Amazon DynamoDB
- Use IAM roles to authenticate access
- Use IAM policies:
  - To define fine-grain access permissions to use DynamoDB APIs
  - Define access at the table, item or attribute level
  - Follow the principle of granting least privilege
- Configure VPC endpoints
  - Prevents connection traffic from traversing the open internet
  - VPC endpoint policies allow you to control and limit API access to a DynamoDB table
- Consider client-side encryption
  - Encrypt data as close as possible to its origing
- Security provided by default:
  - Encryption at rest of all user data stored in tables, indexes, streams, and backups
  - Encyrption in transit, All communications to and from DynamoDB and other AWS resource use HTTPS


## Module 6
### Acritectural need 

Amazon VPC 
Provision a logically isolated section of the AWS cloud wheren you can launch AWS resources in a virtual network that you define.
A VPC belgons to a single AWS region. A VPC spans all the Availability zones in a Region, so it can host supported resources from any Availability Zone within its Region
Default IP range in een VPC is: 10.0.0.0/16 
Subnets:
- A subnet is a segment or partition of a VPC's IP address range where you can allocate a group of resources
- Subnets are not isolation boundaries
- Subnets are a subset of the VPC CIDR block
- Subnet CIDR blocks cannot overlap
- Each subnet resides entirely within one Availability Zone
- You cann add one or more subnets in each Availability Zone or in a Local Zone
- AWS rserves five (5) IP addresses in each subnet

AWS reserves the follewing five ip addresses in the followeing subnet 10.0.0.0/24:
- 10.0.0.0: network address
- 10.0.0.1: VPC local router
- 10.0.0.2: DNS resolution
- 10.0.0.3: Future use
- 10.0.0.255: Network broadcast address

VPC design best practices:
- Create one subnet per available Availability Zone for each group of hosts that have unique routing requirements
- Divide you VPC network range evenly across all available Availability Zones in a Region
- Do not allocate all network addressess at once. Instead, ensure that you reserve some address space for future use
- Size your VPC CIDR and subnets to support significant grrowth for the expected workloads
- Ensure that your VPC network range (CIDR block) does not overlap with you organization's other private network ranges.

#### Network Access control list:

- Act at the subnet level
- Allow all inbound and outbound traffic by default
- Are stateless firewalls that require explicit rules for both inbound and outbound traffic


- Secuirty groups are statefull firewall that act at the isntance level
- Network ACLs are stateless firewalls that act at the subnet level
- When you set inbound and outbound rules to allow traffic to flow from the top tier to the bottom thier of you architecture, you can chain security groups together to isolate a security breach
- You should structure your infrastructure with multiple layers of defense



## Module 7

### AWS site-to-site VPN <br>
AWS Site-to-Site is a highly available solution that enables you to securely connect your on-premises network or branch office site to your VPC. <br>
- Uses IPSec to create a VPN
- Provides two encrypted tunnels pers VPN connection
- Charged per VPN connecion hour

Two types of VPN:
- Static routing
  - Requires you to specify all routes (IP prefixes)
  - Specify static routing if your customer gateway device does not support BGp
- Dynamic routing
  - Uses the Border Gateway Protocol (BGP) to advertise its routes to the virtual private gateway
  - Specify dynamic routing if your customer gateway device supports BGP

You can establisch multiple VPN connections from multiple customer gateway devices to a single virtual private gateway using AWS VPN Cloudhub.  
AWS Cloudhub operates on a hub-and-spoke model to enable multiple sites to access your VPC. 

### AWS Direct Connect (DX)
AWS direct connect provides you with a dedicated, private network connection capacity of either 1 Gbps or 10 Gbps. DX is capable to use 802.1q (VLAN)

DX use cases:
- Hybrid environments
- Transferring large datasets
- Network performance predictability
- Security and compliance

You can access any VPC or public AWS service in any Region (except China) from any supported DX location.  
You can implement highly available connectivity between your data centers and your VPC by coupling one or more DX connections that you use for primary connectivity with a lower-cost, backup VPN connection  
To implement a highly resilient, fault-tolerant architecture, connect your AWS network from multiple data centers so you can have physical location redundancy.

### Connecting VPCs
- Isoling some of your workload is generally a good practice
- However, you might need to transfer data between two or more VPCs

VPC peering:
- one-to-one networking connection between two VPCs
- No gateways, VPN connections, and separate network appliances needed
- Highly available connections
- No single point of failure or bandwidth bottleneck
- Traffic always stays on the global AWS backbone

VPC peering connections:
- Use private IP addresses
- Can be established between different AWS accounts
- Cannot have overlapping CIDR blocks
- Can have only one peering resource between any two VPCs


Inter-Region VPC peering enables VPC resources to communicatie with each other using private IP addresses without requiring gateways, VPN connections, or separate network appliances.

AWS transit gateway is a service that enables you to connect your VPCs and on-premsises network to a single gateway.
- It is fully managed, highly available, flexible routing service.  
- Acts as a hub for all traffic to flow through between your networks  
- Connects upt to 5000 VPC and on-premises environments with a single gateway

VPC endpoint:
- enable you to privately connect your VPC to supported AWS services and to VPC endpoint services that are powered by AWS PrivateLink
- Enable traffic between your VPC and the other service without leaving the Amazon network
- Do not require an internet gateway, VPN, NAT devices, or firewall proxies
- Are horizontally scaled, redundant, and highly available
  
Two types of VPC endpoints:
- interface endpoint
  - An elastic network interface with a private IP address that serves as an entry point for traffic destined to a supported service
  - Powered by AWS Privatelink
  - Examples:
    - Amazon CloudWatch	  
    - Amazon EC2 API
    - Elastic Load Balancing
- Gateway endpoint
  - A gateway that you specify as a target for a route in your route table for traffic destined to a supported AWS service
  - Supprted AWS services:
    - Amazon S3
    - Amazon DynamoDB

## Module 8

AWS Cloud trail is a service that enables governance, complaince, and auditing of your AWS account.
- Logs and monitors user activity
- Provides event history of AWS account
  - Actions taken through the AWS Management Console, SDKs, AWS CLI
  - Increases visibility into your user and resource activity
  - 90-day event history provided by default, at no cost 
- Idenitify
  - Who accessed your account
  - When and from where
  - What action they took on an AWS service
- Helpful tool to
  - Perform secuirty analysis
  - Discover which calls where blocked (for example IAM policies)

One or multiple accounts?

Two architectural patterns
- Most organizations choose to create multiple accounts

Advantages of multiple accounts:
- Isolate business units or departments
- Isolate development, test, and production environments
- Isolate auditing data, recovery data
- Separate accounts for regulated workloads
- Easier to trigger cost alerts for each business unit's consuption

Challenges for managing multiple accounts:
- Security managment across account
  - IAM policy replication
- Creating new accounts
  - Involves many manual processes
- Billing consoidation
- Centralized governance is needed to ensure consitency

Centrally manage and enforce policies across multiple AWS accounts. AWS Organizations is a managed service for account managent. An organization is an enitity that you create to consolidate, centrally view, manage all your AWS accounts.
- Groups-based account management
- Policy-based access to AWS services
- Automated account creation and management
- Consolidated billing
- API-based

Service control policies (SCPs) enable you to control which service are accessible to IAM users in member accounts. Say that you have specific policies that you want to apply across multiple accounts. It is easier to define these policies in an SCP than to replicate these permissions settings into IAM policy documents in each account.

## Module 9

Reactive architectures
- Elastic and scalable
- Resilient
- Responsive
- Message-driven

There are two types of scaling
- horizontal scaling
  - Scale out (launcing instances)
  - Scale in (terminate instances)
- Vertical scaling
  - Scale up (increase instance size)
  - Scale down (decrease instance size)

### Amazon EC2 auto scaling
- Launches or terminates instances based on specified conditions
- Automatically registers new instances with load balancers when specified
- Can launch across Availability Zones

Scaling options
 - Scheduled
    - Good for predictable workloads
      - Scale based on date and time
        - Use case turning off your development and test instances at night
- Dynamic
  - Good for changing conditions
    - Supports target tracking
      - Use case Sclaing based on CPU utilization
- Predictive
  - Good for predicted demand
    - Scale based on machine learnign
      - Use case Handling an increase in workload for ecommerce website during a major sales event

Dynaming scaling policy types
- simple scaling - single scaling adjustment
  - Example new workloads, spiky workloads
- Step sclaign - Adjustment depends on size of alarm breach
  - Example predictable worklaods
- Target tracking scaling - Target value for specific metric
  - Example Horizontally scalable applications, such as load-balanced applications and batch data-prossing applications

Autoscaling purchasing options
- On demand- or reserved instances
- Spot instances

### Autoscaling RDS

Vertical scaling with Amazon RDS: Push button scaling
- Scale DB instances vertically up or down
- From micro to 24xlarge and everything in between
- Scale vertically wtih minimal downtime

Amazon Aurorara Servelss  
Respond to your application automatically:
- Scales capacity
- Starts up 
- Shutdwon 

Pay for the number of Aurora capacity units (ACUs) that are used  
Good for intermittent and unpredictable workloads

## Module 10

Without automation, it will take a significant time and energy to build a large-scale computing environment.

Risk of manual processes:
- Does not support repeatability at scale
- No version control
- Lack of audit trails
- Inconsistent data management

### Cloud front
- AWS cloudformation provides a simplified way to model, create and manage a collection of AWS resources
  - Collection of resources is called an AWS CloudFormation stack
  - No extra charge (pay only for resources you create)
- Can create, update and delete stacks
- Enables orderly and predictable provisioning and updating of resources
- Enables version control of AWS resource deployments

Infrastructure as Code
- IaC is the process of provisioning and managing your cloud resources by writing a template file that is:
  - Human readable
  - Machine consumable
- It is infrastructure you can replicate, redeploy, re-purpose 
- You can roll back to the last good state on failures

Benefits of IaC:
- Rapid deployment of complex environments
- Provides configuration consistency
- Simple clean up when wanted (deleting the stack deletes the resources created)
- Easy to propagate a change to all stacks
  - Modify the template, run update stack on all stacks
- Reusability
- Repeatability
- Maintainability

As your organization starts to use more AWS CloudFormation templates, it will be important for you to have a stategy for templates. This strategy will define the scope of what a single template should create, and the general characteristics that wouold make you want to define your AWS infratrcuture in mofre than one template.

### AWS Systems Manager

Even if you use an IaC tool like AWS CloudFormation to create and maintain your AWS resource deployments, it is helpful to have other tools that you can use. For eample, these tool can address the environment's ongoing needs for configuration management. These needs can occur both after infrastructure resources are provisioned and after the infrastructure is up and running. AWS system manager is a service that address this challange.

AWS Systems manager:
- Automates operational tasks:
  - Example: Apply OS patches and software upgrades across a fleet of EC2 instances
- Simplifies resource and application management
  - Manage software inventory
  - View detailed system configurations across the fleet
- Manages servers on-premises and in the cloud

Systems Manager capabilities:
- Run Command
- Patch Manager
- Session Manager
- Maintenance Windows
- State Manager
- Inventory
- Parameter Store
- Automation
- Documents

### AWS OpsWorks

AWS OpsWorks is a service for configuration management. You can use OpsWorks to automate how EC2 instances are configured, deployed and managed.

AWS OpsWorks is a configuration management service:
 - Automate how servers are configured, deployed and managed
 - Provides managed instances of Chef and Puppet
- Three versions available
  - AWS OpsWorks for Chef Automate
  - AWS OpsWorks for Puppet Enterprise
  - AWS OpsWorks Stacks (ansible)

Model your application as a stack that consists of layers

### AWS Elastic Beanstalk
General challenges:
- Managing infrastructure around application deployment can be difficult
- It can be time-consuming to mange and configure servers
- You might have lack of consistency across multiple projects or applications

AWS Elastic Beanstalk is another AWS compute service option. It is a platform as a service (PaaS) offering that facilitates the quick deployment, scaling and management of your web applications and services. It addresses many of the challenges that you just learned about. 

AWS elastic Beanstalk is:
- easy way to get web application up and running
- Managed service that automatically handles:
  - Infrastructure provisioning and configuration
  - Deployment
  - Load balancing
  - Automatic scaling
  - Health monitoring
  - Analysis and debugging
  - Logging
- No additional charge for using it
  - Pay only for the underlying resources that are used

Elastic Benastalk configures each EC2 instances in your environment with the components that are needed to run applications for the selected platform. You don't need to worry about logging in to instances to install and configure your application stack.

The only thing that you must create is your code. Elastic beanstalk is designed to amke deploying your applicatino a quick and easy process. It supports a range of platforms, including, Docker, Go, Java, .NET, Node.js, PHP, Python and Ruby.

## Module 11



# Services in AWS

<br>

## Compute services

### Amazon EC2

Amazon EC2 provides resizable compute capacity as virtual machines in the cloud. 

### Amazon EC2 (Elastic Compute Cloud) Auto Scaling

enables you to automaticcly add or remove EC2 instances according to conditions that you define

### AWS Lambda

AWS Lambda enables you to run code without provisioning or managening server. You pay only ofr the compute time that you consume. There is no charge when your code is not running. 

### AWS Elastic Beanstalk

AWS elastic Beanstalk is a servvice for deploying and scaling web applications and srevices on familiar servrs such as Apache and Mircosoft Internet Information Services (IIS)

### Amazon ECS (Elastic Container Registry)

Amazon ECs is a highly scalable, high-performance container orhestration service that supports Docker containers. 

### Amazon EKS (Elastic Kubernetes Service)

Amazon EKS makes it easy to deploy, manage, and scale containerezied applications that use Kubernetes on AWS

### Amazon ECR (Elastic Container Service)

Amaozn ECR is a fully-managed Docker container regsitry that makes it easy for developers to sore, manage, and deploy Docker container images. 

### AWS Fargate

AWS Fargate is compute engine for Amazon ECS that allows you to run containers without having to manage server or clusters 


<br>

## Security, identiy and Compliance services 

### AWS IAM (Identity and Access Management)

AWS IAM enables you to manage access to AWS services and resources securely. By using IAM, you can create and manage AWS users and groups. You can use IAM permissions to allow and dney user and group access to AWS recources

### AWS organizations

AWS organizations allows you to restrict what services and action are allowed in your accounts 

### Amazon Cognito

Amazon Cognito lets you add user sign-up, sign-in, and access control to your web and mobile apps 

### AWS Shield 

AWS shield is amanaged Distrubted Denial of Service (DDoS) protction service that safeguards applications running on AWS.

### AWS artifact

AWS artifact provides on-demand access to AWS security and compliance reports and select online agreements

### AWS KMS (Key Management Service)

AWS KMS enables you to create and manage keys, You can use AWS KMS to control the use of encryption across a wide range of AWS services and in our applications 

<br>

## Storage Services

### Amazon S3

is an object storage service that offers scalability, data vailability, security and performance. 
By default the data is not shared publicly.

- Pay only for what you use, including:
  - GBs per month
  - Transfer OUT to other regions
  - PUT, COPY, POSST, LIST and GET requests

### Amazon S3 Glacier
Amazon S3 glacier is a data archiving service that is designed for security, durability and an extremely low cost
- Amazon S3 glacier is designed to provide 11 9s of durability for objects
- It support the enctryption of data in transit
- The vault lock feature enforces compliance through a policy
- Extremely low cost design works well for long term archiving

There are three options for trieving data, each with varying access times and costs:
- **Expedited** retrievals are typically made available within 1-5 minutes (highsest cost)
- **Standard** retrievals complete within 3-5 hours (less  than expedited, more time than bulk)
- **Bulk** retrievals typically complete within 5-12 hours (lowest cost)

You can configure lifecycle archiving of amazon S3 content to amazon S3 glacier

### Amazon EFS

Amazon EFS provides a scalable, fully managed elastic Network Filse System (NFS) for use with AWS Cloud services and on-premise resources. It is built to scale on demand, growing and shrinking automatically as you add and remove files. 

### Amazon EBS

Amazon EBS is high performace block storage that is designed for use with Amazon EC2 for both throughput and transaction intensive workloads. Each Amazon EBS volume is automatically replicated within its availability zone to protect you from component failure.
It durable, block level storage volumes
The data is persistant

- uses:
  - Boot volumes and storage for EC2 instances
  - Data storage with a file system
  - Database hosts
  - Enterprise application

- EBS features:
  - Snapshots
    - Point in time snapshot
    - Recreate a new volume at any time
  - Encryption:
    - Encrypted amazon EBS volumes
    - No additional cost
  - Elasticity
    - Increase capacity
    - Change to different types
<br>

## Database services

### Amazon RDS (Relational Database Service)

Amazon RDS makes it easy to set up, operate, and scale a relation database in the cloud. It provides resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching, and backups

### Amazon DynamoDB

Amazon DynamoDB is a key-value and docuemnt database that deliver single-digit millisecond performance at any scale, with built-in security, backup and restore, and in-memory caching.

### Amazon Redshift

Amaozn Redshift enables you to run analytic queries against petabytes of data that is stored locally in Amazon Redshift, and directly against exabytes of data that are stored in Amazon S3. It devliers fast perfomance at any scale.

### Amazon Aurora 

Amaozn Aurora is a MySQL and PostgreSQL-compatible relational database. It is up to five times fasther than standard MySQL databases and three times faster than standerd PostgreSQL databases.

## AWS networking and content delivery services 

### Amazon Virtual Private Cloud (Amazon VPC)

Amazon VPC enables you to provisoin logically isolated sections of the AWS cloud where you can launch AWS resources in a virtual network that you define
Gives you control over your virtual networking resources including:
- Selection of IP address range
- Creation of subnets
- Configuration of route tables and network gateways
Enables you to use multiple layers of security

### Elastic Load Balancing

Elastic load balancing automaticlly distributes incoming application traffic acroos multiple targets, such as Amazon EC2 instances, containers, IP addresses, and lambda functions

### AWS Cloud Front

Amazon Cloudfront is a fast content devilery network (CDN) service that securly delivers data, videos, applications, and application programming interfaces (APIs) to customers gloablly, with low latency and high transfers speeds.
Amazon cloudfront proved the follwing benefits:
- Fast and global: Amazon Cloudfront is massively scaled and globally distributed. 
- Security at the edge: Amazon cloudfront provides both network-level and application-level protection
- Highly programmable: Amazon CloudFront features can be customized for specific application requirements.
- Deeply integrated with AWS: Amazon Cloudfront is integrated with AWS, with both physical locations that are directly connected to the AWS global infrastructure and other AWS services. 
- Cost effective: Amazon Cloudfront is cost-effective because it has no minimum commitments and chrages you only for what you use.

Pricing:
- Charged for the volume of data transferred out from Amazon Cloudfront edge location to the internet or to your origin
- Charged for number of HTTP(S) requests
- No addition charge for the first 1000 paths that are requested for invalidation each month
- Dedicated IP custom SSL for 600$ per month for each SSL certificate.

###  AWS Transit Gateway

AWS transit gateway is a service that enables customers to connect their Amazon Virtual Private Clouds (VPCs) and their on-premises networks to a single gateway.

### Amazon Route 53

Amaonz Route 53 is a high available and scalable cloud Domain Name System (DNS) web service designed to give you a reliable way to route end users to internet applications.

The supported routing of Route 53 are:
- simple routing: Use in single server environments
- Weighted round robing routing: Assign weight to resource record sets to specify the frequency
- Latency routing: Help improve your global applications
- Geolocation rouing: Route traffic based on location of your users
- Geoproximity routing: Route traffic based on location of your resources
- Failover routing: Fail over to a backup site if your primary site becomes unreachable
- Multivalue answer routing: Respond to DNS queries with up to eight healthy records selected at random. Its not substitute for a load balancer.

### AWS Direct conect

AWS direct connect provides a way to establish a dedicated private network ocnnection from your data center or office to AWS, which can reduce network costs and increase bandwidth throughput.

### AWS VPN

AWS VPN provides a secure private tunnel from your network or device to the AWS global network 


## AWS Cost management services 

### AWS Cost and usage Report

The AWS cost and Usage Report contains the most comprehensive set of AWS cost and usage data available, including metadate about AWS services, pricing, and reservations

### AWS Budget

AWS budgets enables you to set custom budgets that alert you when your costs or usage exceed your budgeted amount

### AWS Cost explorer

AWS cost eplorer has an easy-to-use interface that enables your to visualize, understand, and manage your AWS costs and usage over time.

## AWS managed and governance services 

### AWS Management console

The AWS management console provides a web-based user interface for accessing your AWS account

### AWS config

AWS config provides a service that helps you track resource inventory and changes

### Amazon CloudWatch

Amazon Cloudwatch allows you to monitor resources and applications

### AWS Autscaling

AWS Auto sclaing provides features that allow you to scale multiple resources to meet demand

### AWS Command line interface

AWS command line interface proviced a unified tool to manage AWS services

### AWS Trusted advisor

AWS trusted advisor helps you optimize performance and security.

### AWS Well-architected Tool

AWS Well-architected tool tracks user activity and API usage.


---

