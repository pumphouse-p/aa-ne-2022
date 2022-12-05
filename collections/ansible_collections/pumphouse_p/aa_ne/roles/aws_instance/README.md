# README for `aa_ne.aws_instance`

## Description

An Ansible Role that sets up EC2 instances in AWS.

## Requirements

* `amazon.aws`
* `community.aws`

## Role Variables

Available variables are described in the table below.

| Variable Name | Default | Required | Type | Description |
|:-------------:|:-------:|:--------:|:----:|:-----------:|
|     `var`     | `value` |    no    | str  | Desciption  |


## Dependencies

None.

## Example Playbook

```yaml
---
- name: Play name
  hosts: localhost
  gather_facts: false
  become: false

  roles:
  - role: pumphouse_p.aa_ne.aws_instance
```

## License

GPL

## Author Information

Devin Parrish ([GitHub](https://github.com/pumphouse-p))