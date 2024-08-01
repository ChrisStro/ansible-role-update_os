# Ansible Role: samba_standalone

Ansible role for standalone samba-fileserver

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):
```yaml
smb_users:
  - name: smbadmin    # need to be present for ownershit
    passwd: smbadmin
  - name: smbaccess
    passwd: smbaccess
```