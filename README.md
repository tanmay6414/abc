## This modules contains all the variable related to devk8s
### In this folder policy_var.tf contains data required for terraform resource vault_policy
### Following are the import statement for vault-acl-policies for devk8s

```
terraform import 'module.devk8s.module.acl_policy["devk8s-aws-operator-policy"]'.vault_policy.vault_acl_policy devk8s-aws-operator-policy 
terraform import 'module.devk8s.module.acl_policy["devk8s-cloudability-policy"]'.vault_policy.vault_acl_policy devk8s-cloudability-policy 
terraform import 'module.devk8s.module.acl_policy["devk8s-cloudwatch-exporter"]'.vault_policy.vault_acl_policy devk8s-cloudwatch-exporter 
terraform import 'module.devk8s.module.acl_policy["devk8s-db-operator-policy"]'.vault_policy.vault_acl_policy devk8s-db-operator-policy 
terraform import 'module.devk8s.module.acl_policy["devk8s-elasticsearch-policy"]'.vault_policy.vault_acl_policy devk8s-elasticsearch-policy 
terraform import 'module.devk8s.module.acl_policy["devk8s-grafana"]'.vault_policy.vault_acl_policy devk8s-grafana 
terraform import 'module.devk8s.module.acl_policy["devk8s-pagerduty"]'.vault_policy.vault_acl_policy devk8s-pagerduty 
terraform import 'module.devk8s.module.acl_policy["devk8s-prometheus-policy"]'.vault_policy.vault_acl_policy devk8s-prometheus-policy 
terraform import 'module.devk8s.module.acl_policy["devk8s-s3-operator-policy"]'.vault_policy.vault_acl_policy devk8s-s3-operator-policy 
terraform import 'module.devk8s.module.acl_policy["devk8s-services-role"]'.vault_policy.vault_acl_policy devk8s-services-role 
terraform import 'module.devk8s.module.acl_policy["devk8s-sonar-test-policy"]'.vault_policy.vault_acl_policy devk8s-sonar-test-policy 
terraform import 'module.devk8s.module.acl_policy["devk8s-thanos-policy"]'.vault_policy.vault_acl_policy devk8s-thanos-policy 
terraform import 'module.devk8s.module.acl_policy["devk8s.vibrenthealth.com-lowerenvir-velero"]'.vault_policy.vault_acl_policy devk8s.vibrenthealth.com-lowerenvir-velero  
```
