## virtualenv

[![CI](https://github.com/Oefenweb/ansible-virtualenv/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-virtualenv/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-virtualenv-blue.svg)](https://galaxy.ansible.com/Oefenweb/virtualenv)

Set up (the latest version of) virtualenv(wrapper) in Debian-like systems.

#### Requirements

* `pip` (will not installed)

* `python(2|3)` (will be installed)

#### Variables

* `virtualenv_python_version` [default: `2`]: Python version to install `virtualenv` for.

## Dependencies

None

## Recommended

* `ansible-pip` ([see](https://github.com/Oefenweb/ansible-pip))

#### Example

```yaml
---
- hosts: all
  roles:
    - virtualenv
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-virtualenv/issues)!
