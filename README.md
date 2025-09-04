# Azure-VM-tagging-with-ansible-automation-platform

## Inputs (AAP → Extra Vars)
```yaml
subscription_id: "00000000-0000-0000-0000-000000000000"
LIMIT_VM_LIST: ["vm-one","vm-two"]
az_tags:
  - { key: "owner", value: "cloudzee" }
  - { key: "env", value: "prod" }
