## Name – Sudarshan Yadav, Contact - 7709877817
## Email Id – sudarshanyadav4080@gmail.com
GitHub: https://github.com/Sudarshanydv
Dev.to Blog: https://dev.to/sudarshan_yadav
LinkedIn: https://www.linkedin.com/in/sudarshan-yadav
Resume (Drive) - https://drive.google.com/file/d/1jas-UeQuCSR6OZCP6pAPTnLiWcJiAVk1/view?usp=drive_link

# Web Hosting - EC2
Amazon EC2 (Elastic Compute Cloud) works by providing scalable virtual servers (instances) in the cloud. The overall process involves defining the required software and hardware, launching the instance, configuring security and networking, and managing the instance's lifecycle and associated services. 

## Key Components of EC2
The process of using EC2 relies on several fundamental building blocks: 
•	Amazon Machine Images (AMIs): These are templates that contain the operating system and necessary software packages to launch an instance. You can select from various AWS-provided AMIs, AWS Marketplace AMIs, or create custom ones.
•	Instances: These are the actual virtual servers running on the AWS infrastructure. You select an instance type based on your specific needs for CPU, memory, storage, and networking capacity (e.g., general-purpose, compute-optimized, memory-optimized, etc.).
•	Amazon EBS (Elastic Block Store) Volumes: These provide persistent, durable block-level storage for your instances, functioning like a virtual hard drive. Data on an EBS volume persists even after the instance is stopped.
•	Security Groups: These act as a virtual firewall for your instance, controlling inbound and outbound traffic at the instance level. You define rules that specify allowed ports, protocols, and IP address ranges.
•	Key Pairs: AWS uses public-key cryptography to secure remote access to your instances. A key pair consists of a public key stored by AWS and a private key file (.pem or .ppk) that you securely manage to connect via SSH or RDP.
•	Regions and Availability Zones: You can launch instances in specific geographical Regions and Availability Zones (AZs) to ensure high availability, fault tolerance, and low latency for your applications. 

## The Process of Using EC2
The typical process for using Amazon EC2 to run an application involves the following steps: 
1.	Sign Up and Access: You log in to the AWS Management Console.
2.	Launch an Instance: From the EC2 dashboard, you use the launch instance wizard (or a launch template) to start the process.
3.	Choose an AMI: You select a pre-configured Amazon Machine Image (AMI) (e.g., Amazon Linux, Ubuntu, Windows Server) that has the desired operating system and base software.
4.	Select an Instance Type: You choose an appropriate instance type (e.g., t2.micro, m5.xlarge) based on your application's computing and memory requirements.
5.	Configure Instance Details: You specify details like the network (VPC and subnet), add user data scripts for automated setup at launch, and assign IAM roles for permissions.
6.	Add Storage: You configure the necessary storage, typically adding Amazon EBS volumes to the instance.
7.	Configure Security Group: You define firewall rules (security groups) to control which traffic is allowed to reach your instance (e.g., enabling SSH access on port 22 or HTTP on port 80).
8.	Create/Select Key Pair: You generate a new key pair or select an existing one to securely connect to the instance later.
9.	Launch and Connect: After reviewing the configurations, you launch the instance. Once it's running, you can connect to it using an SSH or RDP client and your private key file.
10.	Manage and Scale: You monitor the instance using Amazon CloudWatch, and use services like Amazon EC2 Auto Scaling and Elastic Load Balancing to automatically adjust capacity based on demand and distribute traffic.
11.	Terminate Instance: When the instance is no longer needed, you terminate it to avoid incurring further charges. You can stop an EBS-backed instance to preserve data and restart it later if needed. 

## ⚙️ How EC2 Works (Step-by-Step Process)
1️⃣ Login to AWS Management Console
2️⃣ Go to EC2 Dashboard → click Launch Instance
3️⃣ Choose AMI (Ubuntu/Amazon Linux etc.)
4️⃣ Choose Instance Type (e.g., t2.micro for Free Tier) based on CPU/RAM
5️⃣ Configure Instance Details
•	Select VPC, Subnet
•	Add User Data for automated setup
•	Assign IAM role for permissions
6️⃣ Add Storage using EBS volume
7️⃣ Set Security Group Rules (e.g., allow SSH or web traffic)
8️⃣ Select/Create Key Pair for secure login
9️⃣ Launch & Connect
•	Use SSH for Linux
•	Use RDP for Windows
10️⃣ Monitor & Scale
•	CloudWatch → performance monitoring
•	Auto Scaling → adjust capacity based on demand
•	Load Balancer → distribute traffic
11️⃣ Stop/Terminate when done
•	Stop → Data persists
•	Terminate → Server + data removed (unless backup)
________________________________________

