# README for `aa_ne.cloud_report`

## Description

An Ansible Role that generates and publishes a report of objects in our cloud
footprint.

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
  - role: pumphouse_p.aa_ne.cloud_report
```

## License

GPL

## Author Information

Devin Parrish ([GitHub](https://github.com/pumphouse-p))