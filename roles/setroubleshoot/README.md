# Ansible Role mafalb.selinux.setroubleshoot

## Basic Usage

```yaml
- name: install mafalb.selinux.setroubleshoot
  hosts: localhost
  roles:
  - role: mafalb.selinux.setroubleshoot
```

```yaml
- name: install mafalb.selinux.setroubleshoot
  hosts: localhost
  roles:
  - role: mafalb.selinux.setroubleshoot
    state: absent
```

## Variables

```state: present``` # setroubleshoot is installed

```state: absent``` # setroubleshoot is not installed

## License

Copyright (c) 2021 Markus Falb <markus.falb@mafalb.at>

GPL-3.0-or-later
