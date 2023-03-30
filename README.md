# Ansible role - apache
[![Maintainer](https://img.shields.io/badge/maintained%20by-claranet-e00000?style=flat-square)](https://www.claranet.fr/)
[![License](https://img.shields.io/github/license/claranet/ansible-role-apache?style=flat-square)](LICENSE)
[![Release](https://img.shields.io/github/v/release/claranet/ansible-role-apache?style=flat-square)](https://github.com/claranet/ansible-role-apache/releases)
[![Status](https://img.shields.io/github/actions/workflow/status/claranet/ansible-role-apache/molecule.yml?branch=main&label=tests&style=flat-square)](https://github.com/claranet/ansible-role-apache/actions?query=workflow%3A%22Ansible+Molecule%22)
[![Ansible version](https://img.shields.io/badge/ansible-%3E%3D2.10-black.svg?style=flat-square&logo=ansible)](https://github.com/ansible/ansible)
[![Ansible Galaxy](https://img.shields.io/badge/ansible-galaxy-black.svg?style=flat-square&logo=ansible)](https://galaxy.ansible.com/claranet/apache)


> :star: Star us on GitHub — it motivates us a lot!

Install and configure Apache 2

## :warning: Requirements

Ansible >= 2.10

## :zap: Installation

```bash
ansible-galaxy install claranet.apache
```

## :gear: Role variables

Variable | Default value | Description
---------|---------------|------------
null     | **null**      | null       

## :arrows_counterclockwise: Dependencies

N/A

## :pencil2: Example Playbook

```yaml
---
- hosts: all
  roles:
    - claranet.apache
```

## :closed_lock_with_key: [Hardening](HARDENING.md)

## :heart_eyes_cat: [Contributing](CONTRIBUTING.md)

## :copyright: [License](LICENSE)

[Mozilla Public License Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)