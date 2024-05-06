---
title: Ec2
---

# Elastic Cloud Compute 
---
title: Ec2
------------- | ------------------------------------------------------------------------------------------------------ | -------------------------- | ------------------ |
| **On Demand** | pay by hour or second  | For Short Term   |  |
| **Spot** | Spin by defining what's the maximum we can pay, can be stopped or terminated if the spot price exceeds the defined | Non-Critical| Up to 90% Discount |
| **Reserved**| Reserve for 1 or 3 years | When the Duration is fixed | up to 72% discount |
|  **Dedicated**| Physically Dedicated Server | License , Compliance  |  |
****

### Instance Types
Defines the type of Server - GPU Based, CPU Based, Memory Based


### [[EBS]] Volumes 


### Permissions 
- [[IAM]] ROLES 
	- Best way - select required permissions and create a [[IAM]] role and then assign the role to EC2.
	- Policy updates to the roles takes effect immediately.
	- attaching and detaching the policies to the roles wont require restarting the machine.
- You can also hard code a user credentials inside EC2 and grant permissions to that user.
