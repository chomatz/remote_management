# cockpit_management
ansible role for cockpit deployment

## requirements

## variables

## dependencies

## examples
```
---

- name: deploy cockpit
  ansible.builtin.include_role:
    name: remote_management
    tasks_from: cockpit_deploy.yml

...
```
