# Cloud-Storage-Setup
Task 1
COMPANY: CLOUDTECH IT SOLUTIONS
NAME: NEHA SATPUTE
INTERN ID: CTIS5002
DOMAIN: CLOUD COMPUTING 
DURATION: 4 WEEKS
MENTOR: NEELA SANTOSH

TASK DESCRIPTION ( AWS AND IAM):
Worked extensively with Amazon Web Services (AWS) S3 and IAM to understand and implement cloud storage management and secure access control mechanisms. The task focused on creating, configuring, and managing storage resources using Amazon S3, while enforcing security and access restrictions through AWS Identity and Access Management (IAM) following the principle of least privilege.

As part of this task, I signed in to the AWS Management Console using secure authentication methods including username, password, and Multi-Factor Authentication (MFA). All configurations were performed in the
ap-south-1 (Mumbai) region, ensuring region-specific resource management and compliance.

Using Amazon S3 (Simple Storage Service), I created a storage bucket with a globally unique name. During bucket creation, I ensured that Block All Public Access was enabled to prevent unauthorized public exposure of data. This step helped reinforce best practices related to cloud data security and privacy. Inside the bucket, I uploaded and managed sample files such as sample.txt and index.html, gaining hands-on experience with object storage, file versioning concepts, and basic data organization within S3.

I also explored bucket-level configurations and permissions to understand how AWS controls access to stored data. This included verifying that objects were accessible only to authorized users and not publicly exposed. Through this, I gained a strong understanding of how S3 manages data durability, availability, and security in a cloud environment.

In parallel, I worked with AWS IAM (Identity and Access Management) to create and manage users. I created an IAM user and attached the AmazonS3ReadOnlyAccess managed policy to it. This configuration ensured that the user had restricted, read-only permissions to S3 resources, preventing any unauthorized modifications or deletions. By implementing this setup, I practiced applying role-based access control (RBAC) and enforcing least-privilege access to cloud resources.

I tested the IAM user’s permissions by validating access behavior, ensuring that the user could view S3 objects but could not upload, delete, or modify data. This practical testing strengthened my understanding of IAM policies, permission boundaries, and real-world access management scenarios.

Overall, this task provided valuable hands-on experience in cloud security, access control, and data management using AWS services. It enhanced my understanding of how organizations securely store data in the cloud while controlling access through well-defined IAM policies. The task also helped me develop confidence in navigating the AWS Console, managing cloud resources, and implementing security best practices aligned with industry standards

KEY POINTS:
Improved understanding of cloud security and access management.
Hands-on experience with AWS Console.
Learned real worl permission handling using IAM policies.
Ensured data security and controlled access.

STEPS:
Signed in using AWS account using username, password and MFA (Multi Factor Authentication)
Region: ap-south-1
In AWS Console search opened S3 (Simple Storage Service) create bukcet with unique name and keep block all public access on
Go to the bucket and click UPLOAD then select the files you want to store in bucket then upload that files, I uploaded sample.txt and some index.html
Search open IAM (Identity Access Management) and create USER using IAM
Attach policy - AmazonS3ReadOnlyAccess
Here i configures IAM USER with restricted S3 permission.
