---
title: Ssm Parameter Store Vs Secrets Manager
---



**Parameter Store provides a bit more versatility**. It has the option to store data unencrypted or to encrypt the data with a KMS key. With [[Secrets Manager]], the secrets are stored encrypted and there's no option to store unencrypted data. So that's one use case for Parameter Store.

| |**SSM Parameter Store**                 | **AWS Secrets Manager**                                                                         |      |
| --------------------------------------- | ----------------------------------------------------------------------------------------------- | ---- |
| **Store values up to 4096 Characters**  | 4KB or 8KB                                                                                      | 64Kb |
| **Values can be encrypted with KMS**    | Yes                                                                                             | Yes  |
| **Can be referenced in CloudFormation** | Yes                                                                                             | Yes  |
| **Built-in password generator**         |                                                                                                 | Yes  |
| **Automated secret rotation**           |                                                                                                 | Yes  |
| **Cross-account access**                |                                                                                                 | Yes  |
| **Additional Cost**                     | Free for standard parameters. Advanced parameters are charged per parameter and API transaction | Yes  |


![[ACG_SSM_VS_SM.png|720]]