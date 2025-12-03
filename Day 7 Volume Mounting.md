# 📌 AWS EBS Volume Mounting – Step-by-Step Guide

**Date:** 01/08/2024   
**Topic:** How to create, attach, mount, unmount, and reuse an EBS Volume in AWS

--- 

## 🚀 What You Will Learn
- Create and attach an EBS Volume
- Mount volume inside Linux EC2 instance
- Store data and verify persistence
- Unmount and reattach the same volume to another instance

---

## 🏗 Step 1: Create an EC2 Instance
Launch a Linux EC2 instance (Amazon Linux / Ubuntu)

---

## 💽 Step 2: Create an EBS Volume
Go to:
EC2 → Volumes → Create Volume

yaml
Copy code
Select:
- **Volume Type:** gp2 / gp3
- **Size:** 5–20 GB (example)
- **Availability Zone:** MUST match EC2 instance AZ

> If AZ is different → ❌ Volume cannot be attached

Click **Create Volume** → **Attach Volume**

---

## 🔗 Step 3: Attach Volume to Instance
EC2 → Volumes → Select Volume → Actions → Attach Volume

java
Copy code
Note the device name (Example):
/dev/xvdf

yaml
Copy code

---

## 🖥 Step 4: Mounting The Volume in Linux (Terminal)

### Check available disks
```bash
lsblk
Check if volume contains data
bash
Copy code
sudo file -s /dev/xvdf
Format the volume (Fresh Volume Only)
bash
Copy code
sudo mkfs -t xfs /dev/xvdf
# OR
sudo mkfs.ext4 /dev/xvdf
Create a mount directory
bash
Copy code
sudo mkdir /home/ec2-user/test
Mount the volume
bash
Copy code
sudo mount /dev/xvdf /home/ec2-user/test
Confirm mount
bash
Copy code
lsblk

## 📁 Step 5: Create Files & Folders
bash
Copy code
cd /home/ec2-user/test
mkdir one two three four five
touch india pune mumbai
✔ Data stored inside EBS volume

🔄 Step 6: Unmount Volume
Go to home directory:

bash
Copy code
cd ~
Unmount:

bash
Copy code
sudo umount /dev/xvdf
📌 Folder looks empty, but data remains in EBS volume

🔁 Step 7: Re-Mount to Verify Data
bash
Copy code
sudo mount /dev/xvdf /home/ec2-user/test
ls /home/ec2-user/test
✔ Your files will appear again!

🔁 Step 8: Attach to Another Instance
Unmount first:

bash
Copy code
sudo umount /dev/xvdf
Detach Volume → Attach it to another EC2 instance

Mount again:

bash
Copy code
sudo mkdir /home/ec2-user/test
sudo mount /dev/xvdf /home/ec2-user/test
🎯 All previously created data is visible!

❓ Interview Questions & Answers
Question	
