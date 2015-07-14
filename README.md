## virtualenv

[![Build Status](https://travis-ci.org/Oefenweb/ansible-virtualenv.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-virtualenv) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-virtualenv-blue.svg)](https://galaxy.ansible.com/list#/roles/4387)

Set up (the latest version of) virtualenv(wrapper) in Debian-like systems.

#### Requirements

* `pip` (will not installed)

#### Variables

None

## Dependencies

None

## Recommended

* `ansible-pip` ([see](https://github.com/Oefenweb/ansible-pip)

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
