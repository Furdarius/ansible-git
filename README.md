# Ansible Role: Git
[![Build Status](https://travis-ci.org/Furdarius/ansible-git.svg?branch=master)](https://travis-ci.org/Furdarius/ansible-git)

Install latest git client from git-core PPA.
Git-core ppa will be added.

## Install

```bash
ansible-galaxy install Furdarius.git
```

## Playbook example

```yaml
---
- hosts: all
  become: true
  roles:
    - git
```
