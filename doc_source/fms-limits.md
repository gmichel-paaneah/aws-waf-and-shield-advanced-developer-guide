# AWS Firewall Manager quotas<a name="fms-limits"></a>

AWS Firewall Manager is subject to the following quotas \(formerly referred to as limits\)\. 

AWS Firewall Manager has default quotas on the number of entities per account\. You can [request an increase](https://console.aws.amazon.com/support/home#/case/create?issueType=service-limit-increase&limitType=service-code-waf) in these quotas\.


| Resource | Default quota | 
| --- | --- | 
| Accounts per organization in AWS Organizations | Varies\. An invitation sent to an account counts against this quota\. The count is returned if the invited account declines, the master account cancels the invitation, or the invitation expires\. | 
| Firewall Manager policies per organization in AWS Organizations | 20 | 
|  Tags that include or exclude resources per Firewall Manager policy  | 8 | 
| AWS WAF rule groups per Firewall Manager administrator account | 100 | 
| AWS WAF Classic rule groups per Firewall Manager administrator account | 10 | 
| Rule groups per AWS WAF policy | 50 | 
| Total web ACL capacity units \(WCU\) for the rule groups in an AWS WAF policy\. | 1500 | 
| Primary security groups per common Firewall Manager policy | 1 | 
| Audit security groups per content audit Firewall Manager policy | 1 | 
| Amazon VPC instances in scope per Firewall Manager common security group policy | 5 | 

The security group policies managed by Firewall Manager are subject to standard Amazon VPC quotas\. For more information, see [Amazon VPC Quotas](https://docs.aws.amazon.com/vpc/latest/userguide/amazon-vpc-limits.html) in the [Amazon VPC User Guide](https://docs.aws.amazon.com/vpc/latest/userguide/)\. 

The following quotas related to AWS Firewall Manager can't be changed\.


| Resource | Quota | 
| --- | --- | 
| AWS WAF Classic rule groups per Firewall Manager AWS WAF Classic policy | 2: 1 customer\-created rule group and 1 AWS Marketplace rule group | 
| AWS WAF Classic rules per Firewall Manager AWS WAF Classic rule group | 10 | 