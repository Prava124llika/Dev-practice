\# AWS EC2 Setup and SSH Login using PuTTY



\## Task Objective

Create an Amazon Linux EC2 instance and connect using PuTTY with private key authentication.



\## Steps Performed



\### Step 1: Create EC2 Instance

\- Selected Amazon Linux 2023

\- Instance type: t3.micro

\- Generated key pair

\- Launched instance



\### Step 2: Get Public IP

\- Copied Public IPv4 address from EC2 dashboard



\### Step 3: Convert Key using PuTTYgen

\- Opened PuTTY Key Generator

\- Loaded .pem file

\- Saved as .ppk file



\### Step 4: Connect using PuTTY

\- Opened PuTTY

\- Entered Host Name: ec2-user@<public-ip>

\- Loaded .ppk file under SSH → Auth

\- Clicked Open



\### Step 5: Successful Login

\- Logged into Amazon Linux server



\## Commands Used



ssh -i "key.pem" ec2-user@<public-ip>



\## Tools Used

\- AWS EC2

\- PuTTY

\- PuTTYgen

