# 📅 Day 18 | AWS CloudFormation — Infrastructure as Code (IaC) in AWS 🏗️☁️

Today, I learned about **AWS CloudFormation**, which is an **Infrastructure as Code (IaC)** service that helps create, update, and delete AWS resources automatically using **YAML or JSON templates**.

CloudFormation is widely used in DevOps to deploy infrastructure in a **repeatable, consistent, and automated way**.

---

## 🏗️ AWS CloudFormation (DevOps – Infrastructure Automation)

### 🔹 Amazon CloudFormation

**Service Type**  
Infrastructure as Code (IaC)

**Template Format**  
YAML / JSON

**Key Features**
- Automated infrastructure creation
- Manages full lifecycle (Create, Update, Delete)
- Consistent deployments
- Automatic rollback on failure
- Fully managed by AWS

---

## 🔹 Why We Use CloudFormation in DevOps

CloudFormation is used when we need:

- ✅ Automated infrastructure deployment  
- ✅ Repeatable environments (Dev / Test / Prod)  
- ✅ Version-controlled infrastructure  
- ✅ Reduced manual errors  
- ✅ Easy rollback and recovery  

---

## 🔹 Real-World DevOps Use Cases

| Use Case | Why CloudFormation |
|--------|-------------------|
| EC2 & VPC setup | One-click infrastructure |
| Auto Scaling | Consistent scaling |
| CI/CD pipelines | Infrastructure automation |
| Disaster recovery | Easy recreation |
| Multi-environment setup | Template reuse |

---

## 🔹 How CloudFormation Works (Architecture)

User  
↓  
CloudFormation Template (YAML / JSON)  
↓  
CloudFormation Stack  
↓  
AWS Resources (EC2, S3, VPC, IAM, RDS)

---

## 🔹 Key CloudFormation Components

- **Template** – Blueprint of infrastructure  
- **Stack** – Deployed version of template  
- **Resources** – AWS services defined  
- **Parameters** – Input values  
- **Outputs** – Results like IP, DNS  

---

## 🔹 Step-by-Step: How to Use CloudFormation

### 🔹 Step 1: Create Template
Create a YAML or JSON file defining AWS resources.

```yaml
Resources:
  MyS3Bucket:
    Type: AWS::S3::Bucket
```
---

## Thank You

## 🔗 Connect With Me
| 🌐 Platform                  | 🔗 Link                                              |
| ---------------------------- | ---------------------------------------------------- |
| 🐙 **GitHub**                | [https://lnkd.in/d2F3JPa3](https://lnkd.in/d2F3JPa3) |
| ✍️ **Dev.to Blog**           | [https://lnkd.in/dNtgqAME](https://lnkd.in/dNtgqAME) |
| 💼 **LinkedIn**              | [https://lnkd.in/d3NctxFT](https://lnkd.in/d3NctxFT) |
| 📄 **Resume (Google Drive)** | [https://lnkd.in/dHDNsd_D](https://lnkd.in/dHDNsd_D) |

## 🔖 Hashtags
#AWS #DevOps #CloudComputing #AWSLearning #EBS #VolumeMounting #DataPersistence #LearningJourney #CareerGrowth #DevOpsEngineer #AWSCommunity

---

⭐ If you like this guide, don’t forget to star the repo!
