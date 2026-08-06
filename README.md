# CLOUD STORAGE CREATION (S3) AND LAUNCHING AN (EC2) INSTANCE IN AWS (AWS EC2 Web Server Lab)

### Register Number : 212224230300
### Name : VESHWANTH.
## Aim

To understand the basic operations of Amazon Elastic Compute Cloud (EC2) by launching, configuring, monitoring, resizing, and managing an EC2 instance that hosts a simple Apache web server.

---

## Problem Statement

Cloud applications require scalable and reliable computing resources. The objective of this experiment is to learn how to deploy a virtual server on Amazon EC2, configure networking and security settings, host a web application using Apache HTTP Server, monitor the instance, modify its resources, and explore EC2 protection mechanisms and service limits.

---

## Algorithm / Procedure

1. Log in to the AWS Management Console.
2. Navigate to the EC2 Dashboard.
3. Launch a new EC2 instance using the Amazon Linux 2023 AMI.
4. Select the `t2.micro` instance type.
5. Configure the required VPC and subnet.
6. Create a Security Group.
7. Enable termination protection.
8. Add the User Data script to automatically install and start the Apache web server.
9. Launch the EC2 instance.
10. Wait until the instance status changes to **Running**.
11. Monitor the instance using the **Status Checks** and **CloudWatch Monitoring** tabs.
12. Edit the Security Group to allow inbound HTTP (Port 80) traffic.
13. Access the web server using the public IPv4 address.
14. Stop the instance and change the instance type to **t2.small**.
15. Increase the EBS volume size from **8 GB** to **10 GB**.
16. Enable and test Stop Protection.
17. Explore EC2 Service Quotas.
18. Disable Stop Protection and stop the instance successfully.

---

## Outputs


### EC2 Instance Launch

<img width="1918" height="981" alt="1" src="https://github.com/user-attachments/assets/878341d6-28f1-4ddc-adf1-229b58969a8f" />

<img width="1918" height="972" alt="2" src="https://github.com/user-attachments/assets/b3a130ad-a413-4d6b-ab53-66122352cecd" />

---

### Web Server Instance Details
<img width="1918" height="973" alt="3" src="https://github.com/user-attachments/assets/9b0c5ff2-f2e8-43ec-8635-f34b07eaa44c" />


---

### Security Group Configuration

<img width="1918" height="995" alt="5" src="https://github.com/user-attachments/assets/f9d0a175-8d00-45cc-92ab-67a3aaabf095" />

<img width="1918" height="971" alt="6" src="https://github.com/user-attachments/assets/53f8f611-9896-4168-b187-b55b046e4d46" />


### EDIT INBOUND RULES INSIDE WEB SECURITY(SECURITY GROUP)

<img width="1915" height="986" alt="7" src="https://github.com/user-attachments/assets/f1aa4e6f-db8d-4ec8-b483-b900fb3d3e71" />

<img width="1918" height="982" alt="8" src="https://github.com/user-attachments/assets/3766c205-a5b6-481e-93ec-f91450bec25e" />

### STOPPING THE NEWLY CREATED WEB SERVER INSTANCES

<img width="1918" height="990" alt="9" src="https://github.com/user-attachments/assets/8de85e5d-5b4e-4439-ab84-a1dd0fb49f1d" />

### CHANGING WEB SERVER INSTANCE TYPE

<img width="1918" height="977" alt="10" src="https://github.com/user-attachments/assets/3ef9757b-5ac4-4473-ae59-47d20dec568c" />

<img width="1918" height="973" alt="11" src="https://github.com/user-attachments/assets/fbd915d7-9e35-40bc-b143-0465280c0814" />


### DISABLING STOP PROTECTION FOR WEB SERVER INSTANCE

<img width="1918" height="992" alt="12" src="https://github.com/user-attachments/assets/ceaa7d9f-b2da-487f-8259-b6d8749d5092" />


### MODIFYING EBS VOLUME INSIDE THE VOLUMES SECTION

<img width="1918" height="987" alt="13" src="https://github.com/user-attachments/assets/b3033209-2850-437a-b54b-e5511d4fef03" />

<img width="1918" height="977" alt="14" src="https://github.com/user-attachments/assets/4fd2396e-ad06-4cf6-9577-871c0cc35128" />



### RESTARING WEB SERVER INSTANCE

<img width="1917" height="985" alt="15" src="https://github.com/user-attachments/assets/f828f5ee-71c8-456a-aea0-a8a823975eff" />

### OVERVIEW OF AMAZON ELASTIC COMPUTE CLOUD(AMAZON EC2)

<img width="1915" height="973" alt="16" src="https://github.com/user-attachments/assets/042d2a9a-efff-431a-bb51-a9c2691ba2f4" />

<img width="1918" height="970" alt="17" src="https://github.com/user-attachments/assets/cf27fc82-0365-42f7-9be6-76dde39a3b86" />

<img width="1910" height="985" alt="18" src="https://github.com/user-attachments/assets/25ce596e-dc0f-4c9b-aa76-e3bd946b8fb3" />


### STOPPING THE WEB SERVER INSTANCE(FAILED TO STOP)

<img width="1918" height="986" alt="19" src="https://github.com/user-attachments/assets/eecaceb4-c1c9-4d25-afe9-0a947241a343" />

### SUCCESSFULLY STOPPED INSTANCE

<img width="1918" height="982" alt="20" src="https://github.com/user-attachments/assets/752f1e5f-ae8e-45a3-8495-e0d3497b1966" />


---

### EC2 Monitoring

<img width="1918" height="978" alt="4" src="https://github.com/user-attachments/assets/5d2cbff0-c389-4e33-982b-69ad804fc344" />

<img width="1920" height="1080" alt="Screenshot 2026-08-04 093529" src="https://github.com/user-attachments/assets/f55dbfe3-57c7-49ed-9335-52f6f2b1ac8e" />

---

### EC2 System Log
<img width="1920" height="1080" alt="Screenshot 2026-08-04 093634" src="https://github.com/user-attachments/assets/7a6a424a-534a-4f34-afc9-13aed5758ece" />

---

### EC2 Monitoring Diagnosis

<img width="1920" height="1080" alt="Screenshot 2026-08-06 105514" src="https://github.com/user-attachments/assets/4cb2d65a-a43a-4dc3-a9ae-1dfb877fe18d" />

---

### Apache Web Server Output

<img width="1450" height="717" alt="image" src="https://github.com/user-attachments/assets/e90e21db-3b4f-4b04-bc58-714d4f6c3adc" />


---


## Result

Successfully launched and managed an Amazon EC2 instance, configured security settings, deployed an Apache web server using User Data, monitored the instance, resized the instance and storage volume, tested instance protection features, and explored Amazon EC2 service quotas.
