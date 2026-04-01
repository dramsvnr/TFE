## Module 1 – Topic 1
**What Problem Terraform Cloud Solves (DevOps View)**

----

**1.The DevOps Pain Before Terraform Cloud**  

Typical Terraform OSS Setup  
``
Engineer Laptop
 ├── terraform apply
 ├── state stored locally or S3
 ├── credentials in env vars
 └── no centralized control
``

**Real Problems DevOps Teams Faced**

- State File Issues  

State stored locally → lost / corrupted  
S3/AzureStorage backend misconfiguration  
State locking failures  

- No Team Collaboration  

Two engineers running apply at same time  
No visibility on who changed what  
No approval workflows  

- Security Risks  

Secrets in .tfvars  
Credentials on laptops  
No audit trail  

- No Governance  

Anyone can provision anything  
No policy guardrails  
No compliance enforcement  


Note : **“Terraform worked great for individuals—but broke down for teams.”**  

