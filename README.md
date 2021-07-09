## How to add new alert
### In this folder policy_var.tf contains data required for terraform resource vault_policy
1. Add new variable in [```alert-variable-initialization.tf```](https://github.com/VibrentHealth/alerting-response/blob/d488dfa55d33fb4edc73cc06277e8bed2cfdae44/alerts/newrelicRules/modules/alerts/alert-variable-initialization.tf) file \
Suppose you want to add alert which is of type ```hellow_world_alert``` then add somehing like below in this file.

```
variable "hello_world_alert" {
}
```
2. Inside ```vars``` folder create a new file for this alert and add your values in this file \
> **_NOTE:_**  Name of the variable in this file is same as you give in step 1
[Follow this structure] (https://github.com/VibrentHealth/alerting-response/blob/d488dfa55d33fb4edc73cc06277e8bed2cfdae44/alerts/newrelicRules/modules/alerts/vars/hello-world-alert.tf#L1)
