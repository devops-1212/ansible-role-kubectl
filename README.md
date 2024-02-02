# Ansible role kubectl

The Ansible role to install kubectl.

## Example playbook

```yaml
- name: Install kubectl
  hosts: all
  roles:
    - role: devops_1212.kubectl
```

## Parameters

* `kubectl_version` - set the version of kubectl


