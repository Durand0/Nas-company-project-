## Nas Company project 


***Description***

The NAS Financial Group is currently running its workloads on premise and would like to
migrate some applications to the AWS cloud platform.
They hire CloudSpace Consulting engineers to design, implement and manage a solution that will meet their requirements.

1) CloudSpace Consulting engineers must ensure that the NAS Financial Group AWS account should be accessible and managed by the following groups.

* CloudSpace engineers

* NAS Financial Group security team 

* NAS Financial Group operations team 

Each group has specific tasks.

2) CloudSpace consulting engineers will create a dynamic, secure, high-availability website that is accessible to the public.

* Because of PCI compliance all traffic from users to the website should be encrypted.

* The site should be Highly available and fault tolerant.

* Because of GDPR compliance only USA customers should be able to access the dynamic
website, but users in Europe and other continent should land on a static website.

* The website should be able to self-heal and adapt to the volume of traffic from customers.

*  For disaster recovery, the application tier & the database tier should be backed up in a
different location.

* There should be at least 2 monitoring systems in place to notify us in case the website site is
down.

* The management of the web server should only be done by CloudSpace engineers using the
most secured methods as per AWS best practices.

3) CloudSpace consulting engineers will build a dynamic application that is not accessible to the public (intranet).

* Make sure the server hosting the intranet has the ability to download and update packages on
the internet.

* Users within the company should access the application through HTTP.

4) NAS Financial Group recently hired an auditing firm called N2G Auditing to 
to ensure the visibility and auditing of NAS internal application.

* N2G Auditing should only have access to NAS Financial internal (intranet) application
through its web interface using HTTP and the underline database from their own AWS account.

* Recommend an AWS service when N2G auditing can have a centralized way of reviewing if
NAS Financial Group is following AWS best practices (Cost Optimization, Performance,
Security, Fault Tolerance). Their console access should only grant them full access to that
service and NOTHING else.

5) Storage ( NAS Financial Group stores files of customers information. That information contains PII and
should be encrypted at rest. The files are regularly access for 30 days and then need to be
archived and records kept for 5 years. )

* Recommend a storage solution that will help NAS meet these requirements. 
 
**Getting started:**

Prerequisites : 

Resources required for this project

-Iam group

-Iam user

-Managed policy

-VPC

-Internet gateway

-Nat gateway

-Public subnet (2)

-Private subnet (2)

-Public route table

-Private route table

-Security groups (5)

-KeyName

-Ec2 instance profile

-Ec2 instance ssm role

-Launch template (2)

-Auto scaling (2)

-Load balancer

-Listener

-Target group

-Route 53 (2)

-Host Zone

-Cloudfront distribution

-S3 bucket

-Cloudfront origin

-Bucket policy

-Certificate

-KMS key

-EFS

-Mount target (2)

-Scaling up policy

-Scaling down policy

-Cloudwatch alarm for high CPU utilization

-Cloudwatch alarm for low CPU utilization

-Sns topic

-Sns subscription

-Database

-Backup vault

-Backup plan

-Backup selection

-Backup IAM role

-Cross account role
