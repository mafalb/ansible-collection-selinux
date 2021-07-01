# Ansible Role mafalb.selinux.mcstrans

## Basic Usage

```yaml
- name: install mafalb.selinux.mcstrans
  hosts: localhost
  roles:
  - role: mafalb.selinux.mcstrans
```

```yaml
- name: install mafalb.selinux.mcstrans
  hosts: localhost
  roles:
  - role: mafalb.selinux.mcstrans
    state: absent
```

## Variables

```state: present``` # mcstrans is installed

```state: absent``` # mcstrans is not installed

## License

Copyright (c) 2021 Markus Falb <markus.falb@mafalb.at>

GPL-3.0-or-later
