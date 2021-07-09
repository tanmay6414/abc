## How to add new alert
### In this folder policy_var.tf contains data required for terraform resource vault_policy
1. Add new variable in [```alert-variable-initialization.tf```](https://github.com/VibrentHealth/alerting-response/blob/d488dfa55d33fb4edc73cc06277e8bed2cfdae44/alerts/newrelicRules/modules/alerts/alert-variable-initialization.tf#L4-L5) file \
Suppose you want to add alert which is of type ```hellow_world_alert``` then add somehing like below in this file \
```
variable "hello_world_alert" {
}
```
