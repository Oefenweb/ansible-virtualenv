## virtualenv

[![CI](https://github.com/Oefenweb/ansible-virtualenv/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-virtualenv/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-virtualenv-blue.svg)](https://galaxy.ansible.com/Oefenweb/virtualenv)

Set up (the latest version of) virtualenv(wrapper) in Debian-like systems.

#### Requirements

* `pip` (will not installed)

* `python(2|3)` (will be installed)

when using `virtualenv_install_method: pip`

#### Variables

* `virtualenv_install_method`: [default: `native`]: The way to install `virtualenv` (e.g. `native` (from Ubuntu/Debian repo) or `pip`, `< 24.04` only)

* `virtualenv_python_version_major` [default: `3`]: Python version to install `virtualenv` for.

## Dependencies

None

## Recommended

* `ansible-pip` ([see](https://github.com/Oefenweb/ansible-pip))

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.virtualenv
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-virtualenv/issues)!
