# Ansible Role: update_os

Ansible role for os updates/patching

## Role Variables

To prevent package updates:
```yaml
update_os_debian_holds:
  - mypackage
```

## Supported Operating Systems

- debian based distributions
- windows