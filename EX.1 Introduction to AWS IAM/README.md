# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  

<img width="1919" height="907" alt="image" src="https://github.com/user-attachments/assets/5c0e759f-0105-46b0-af40-76c10ee28531" />

### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  

<img width="1532" height="674" alt="image" src="https://github.com/user-attachments/assets/c607689e-344c-4908-b242-0a11ae959152" />

<img width="1533" height="692" alt="image" src="https://github.com/user-attachments/assets/e903712e-8172-4f97-ab44-8760f1cf7112" />

<img width="1535" height="734" alt="image" src="https://github.com/user-attachments/assets/06d592d4-0ea7-4f23-9399-739d7246209a" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**

<img width="1537" height="763" alt="image" src="https://github.com/user-attachments/assets/1f9fcd5d-3d65-470a-971c-24c63d365440" />

<img width="1539" height="763" alt="image" src="https://github.com/user-attachments/assets/c8ec1b7c-f509-40c4-bd8c-873795f09e49" />

<img width="1540" height="769" alt="image" src="https://github.com/user-attachments/assets/bb20adcc-9e61-47e3-8ffa-d99580b3fa9b" />


## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** A.NABITHRA

**Reg No:** 212224230172

**Course:** Introduction to Cloud Computing  

