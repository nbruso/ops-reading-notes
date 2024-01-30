# Reading notes 16

**What were the three commands used for the attack?**
The three commands used for the attack were:
1. **Get Credentials**: This command obtained security credentials known as ****-WAF-Role account (an IAM account) for an elevated role access AWS Web Application Firewall (WAF).
2. **List Buckets**: This second command used the security credentials *****-WAF-Role account to list files and folders (aka S3 buckets).
3. **Download Files**: The third command used the *****-WAF-Role account to download files that were accessible by the credentials.

**What misconfiguration of AWS components allowed the attacker to access sensitive data?**
The misconfiguration of AWS components that allowed the attacker to access sensitive data included:
1. A misconfiguration error at the application layer of the firewall installed by the Financial Institution.
2. Permissions set by the Financial Institution that were too broad.

**What are two of the AWS Governance practices that could have prevented such attack?**
Two of the AWS Governance practices that could have prevented the attack are:
1. Use Cloud Infrastructure Entitlement Management (CIEM) solutions to detect over-privileged identities and over-exposed data.
2. Scope the permissions of each role to enable access only to the AWS resources required.

#### source: https://www.zscaler.com/resources/white-papers/capital-one-data-breach.pdf