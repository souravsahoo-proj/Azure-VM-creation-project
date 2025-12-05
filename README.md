# Azure-VM-creation-project
**Auther** -Sourav Sahoo **Date** -December 05,2025
___
### Project Overview
___
This project outlines the step-by-step process of deploying virtual machine and Dist setup in azure cloud.
___
### Azure Virtual Machine Preparation
**Lounch Virtual Machine**
* Step-1: Navigate to the azure vm in azure portal
* Step-2: Select subscription 
* Step-3: Select resources group
* step-4: Virtual machine name - devvm
* Step-5: Region - (US) East us
* step-6: Availibity options - select availibility zone 
* Step-7: Avaibility zone - select zone 3
* Step-8: Security types - select standard
* Step-9: Image - ubuntu server 24.04 LTS x64 gen2
* Step-10: Size - L2 aou_v4
* Step-11: Authentication type - Select SSH public key and denerated secure SSH key pair and added the public key during vm creation for password-less authentication.
  <br>
![image1](https://github.com/souravsahoo-proj/Azure-VM-creation-project/blob/main/images/Screenshot%202025-12-05%20111405.png?raw=true)
![image2](https://github.com/souravsahoo-proj/Azure-VM-creation-project/blob/main/images/Screenshot%202025-12-05%20122442.png?raw=true)
![image3](https://github.com/souravsahoo-proj/Azure-VM-creation-project/blob/main/images/Screenshot%202025-12-05%20122338.png?raw=true)
---
### Os Dist And Data Dist Creation
* Step-1: OS disk size - 64 gib (P6)
* Step-2: OS disk tupes - premium SSD (locally-redundancy storage)
* Step-3: Data disk size - 1024 GB
<br>
![image4](https://github.com/souravsahoo-proj/Azure-VM-creation-project/blob/main/images/Screenshot%202025-12-05%20124712.png?raw=true)
