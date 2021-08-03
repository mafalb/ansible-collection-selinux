# Ansible Role mafalb.selinux.selinux

## Basic Usage

```yaml
- name: install mafalb.selinux.selinux
  hosts: localhost
  roles:
  - role: mafalb.selinux.selinux
```

```yaml
- name: install mafalb.selinux.selinux
  hosts: localhost
  roles:
  - role: mafalb.selinux.selinux
    state: disabled
```

## Variables

```state: enforcing``` # selinux is enforcing

```state: permissive``` # selinux is permissive

```state: disabled``` # selinux is disabled

```policy: targeted``` # targeted policy

```policy: mcs``` # mcs policy

## License

Copyright (c) 2021 Markus Falb <markus.falb@mafalb.at>

GPL-3.0-or-later
