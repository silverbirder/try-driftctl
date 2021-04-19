# Driftctl Quick AWS Tutorial

This is the code to be used with the quick how-to available on this page.

TL;DR: 

```shell
$ terraform init && terraform apply
# manual changes on the IAM user using the AWS Console
$ terraform apply
$ AWS_ACCESS_KEY_ID=XXX AWS_SECRET_ACCESS_KEY=YYY AWS_REGION=us-east-1 driftctl scan
Scanned resources:    (20)
Found resources not covered by IaC:
  aws_sns_topic_policy:
  aws_sns_topic_subscription:
  aws_sns_topic:
Found 6 resource(s)
 - 33% coverage
 - 2 covered by IaC
 - 4 not covered by IaC
 - 0 missing on cloud provider
 - 0/2 changed outside of IaC
```
