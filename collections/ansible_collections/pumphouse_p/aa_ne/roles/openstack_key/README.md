# README for `aa_ne.openstack_key`

## Description

An Ansible Role that uploads a key for use with nova-compute instances.

## Requirements

* ``

## Role Variables

Available variables are described in the table below.

| Variable Name | Default | Required | Type | Description |
|:-------------:|:-------:|:--------:|:----:|:-----------:|
|     `var`     | `value` |    no    | str  | Desciption  |


## Dependencies

* ``

## Example Playbook

```yaml
---
- name: Play name
  hosts: localhost
  gather_facts: false
  become: false

  roles:
  - role: pumphouse_p.skel.role
```

## License

GPL

## Author Information

Devin Parrish ([GitHub](https://github.com/pumphouse-p))