# Azure-VM-tagging-with-ansible-automation-platform

## Inputs (AAP → Extra Vars)
```yaml
subscription_id: 00000000-0000-0000-0000-000000000000
VM_LIST:
  - vm-01
  - vm-02
az_tags:
  - key: owner
    value: cloudzee
  - key: env
    value: prod
