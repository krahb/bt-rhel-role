## bt-rhel-role
Ansible bt rhel role

## description
some basic stuff to setup and keep a Centos/RHEL 7 server clean and updated

## example playbook snippet
```yaml
- import_role:
    name: bt-rhel-role
  tags:
  - rhel
  when: "ansible_os_family == 'RedHat'"
```
