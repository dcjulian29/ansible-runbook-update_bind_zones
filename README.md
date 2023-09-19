# Ansible Runbook: update_bind_zones

[![Build](https://github.com/dcjulian29/ansible-runbook-update_bind_zones/actions/workflows/build.yml/badge.svg)](https://github.com/dcjulian29/ansible-runbook-update_bind_zones/actions/workflows/build.yml) [![Release](https://github.com/dcjulian29/ansible-runbook-update_bind_zones/actions/workflows/release.yml/badge.svg)](https://github.com/dcjulian29/ansible-runbook-update_bind_zones/actions/workflows/release.yml) [![GitHub Release](https://img.shields.io/github/v/release/dcjulian29/ansible-runbook-update_bind_zones)](https://github.com/dcjulian29/ansible-runbook-update_bind_zones/releases) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-runbook-update_bind_zones.svg)](https://github.com/dcjulian29/ansible-runbook-update_bind_zones/issues)

This is an Ansible runbook that will update zones and restart Bind.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
collections:
- name: dcjulian29.update_bind_zones
  type: git
  source: https://github.com/dcjulian29/ansible-runbook-update_bind_zones.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy collection install -r requirements.yml
```

To excute the runbook:

```shell
ansible-playbook dcjulian29.update_bind_zones.runbook.yml
```
