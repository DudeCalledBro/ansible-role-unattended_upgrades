# Ansible Role: Unattended Upgrades

> An Ansible Role that installs and configures Unattended Upgrades on Debian.

## Variables

The most important variable will be `unattended_upgrades_package_blacklist`. This is a list which contains packages, which should not be upgraded. As default, this is empty. You should consider adding packages to *not* break your system

```yaml
unattended_upgrades_package_blacklist:
- containerd.io
- docker-buildx-plugin
- docker-ce
- docker-ce-cli
- docker-compose-plugin
```

## Example

The following minmal Playbook will setup and configure unattended upgrades.

```yaml
- hosts: all
  roles:
  - dudecalledbro.unattended_upgrades
```

## License

Copyright © 2024 Niclas Spreng

Licensed under the [MIT license](LICENSE).
