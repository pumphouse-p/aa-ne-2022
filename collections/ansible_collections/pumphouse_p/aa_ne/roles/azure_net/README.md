# README for `aa_ne.azure_net`

## Description

An Ansible Role that manages networking objects in Microsoft Azure.

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
  - role: pumphouse_p.aa_ne.azure_net
```

## License

GPL

## Author Information

Devin Parrish ([GitHub](https://github.com/pumphouse-p))