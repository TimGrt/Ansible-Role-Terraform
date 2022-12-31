# Ansible Role: Terraform

[![Ansible Lint](https://github.com/TimGrt/Ansible-Role-Terraform/actions/workflows/ci.yml/badge.svg)](https://github.com/TimGrt/Ansible-Role-Terraform/actions/workflows/ci.yml)

A simple Ansible role to install latest version of Terraform.

Tested against

* AmazonLinux 2022
* CentOS 7
* Fedora 37
* Rocky Linux 8
* Ubuntu 20.04

## Requirements

None, other than sudo permissions.

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  roles:
    - timgrt.terraform
```

## License

MIT / BSD

## Author Information

This role was created in 2022 by Tim Grützmacher
