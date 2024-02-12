# Reading Notes 19

- **What are some of the IoCs that GuardDuty can detect?**
  GuardDuty can detect IoCs such as escalation of privileges, use of exposed credentials, communication with malicious IP addresses and domains, malware on EC2 instances, and unusual login patterns.

- **What are some of the data sources which GuardDuty can use?**
  GuardDuty uses data sources including AWS CloudTrail management events, AWS CloudTrail event logs, VPC flow logs, DNS logs, Kubernetes audit logs, RDS login activity, S3 logs, EBS volumes, runtime monitoring, and Lambda network activity logs.

- **How does GuardDuty use access behavior to spot potential malicious activity?**
  GuardDuty uses access behavior to monitoring AWS account access patterns, looking for signs of compromise such as unauthorized instance deployments or unusual API calls.

#### source: https://docs.aws.amazon.com/guardduty/latest/ug/what-is-guardduty.html