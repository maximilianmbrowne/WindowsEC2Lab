
# Watch the video of me building the Virtual Machine HERE:
https://www.loom.com/share/64b6b936cade48b0847952e1fa09351e

# EC2 Instance Lab

## Overview
This lab covers the process of creating and connecting to a Windows Virtual Machine EC2 instance in AWS.

## Steps

### 1. Created a Windows Virtual Machine EC2 Instance
- Logged into the AWS Management Console.
- Navigated to EC2 Dashboard.
- Launched a new EC2 instance with a Windows Server AMI.
- Configured the instance settings as needed.
- Started the instance and noted its public DNS/IP address.

### 2. Created a Key Pair for Virtual Machine
- In the process of launching the instance, created a new key pair.
- Downloaded the `.pem` file and stored it securely for future connection purposes.

### 3. Connected to Virtual Machine using Remote Desktop Protocol (RDP)
- Ensured the security group allowed RDP access (port 3389).
- Retrieved the administrator password for the Windows instance using the key pair.
- Used an RDP client to connect to the instance's public DNS/IP.
- Entered login credentials to access the Windows environment.

## Conclusion
Successfully launched, configured, and connected to a Windows EC2 instance in AWS.

