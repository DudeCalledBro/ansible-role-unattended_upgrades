# Ansible Role: Unattended upgrades

[![CI](https://github.com/DudeCalledBro/ansible-role-unattended_upgrades/actions/workflows/molecule.yml/badge.svg)](https://github.com/DudeCalledBro/ansible-role-unattended_upgrades/actions/workflows/molecule.yml)

Install and configure unattended-upgrades.

## Prerequisites

- Ensure you have Ansible installed (e.g. `pip3 install ansible`)
- **Development**: Install the pip packages listed in [requirements.txt](requirements.txt)

## Role Variables

The default values for the variables are set in [defaults/main.yml](defaults/main.yml)

```yaml
- hosts: all
  roles:
  - role: dudecalledbro.unattended_upgrades
```

## License

Copyright © 2024 Niclas Spreng

Licensed under the [MIT license](LICENSE).
