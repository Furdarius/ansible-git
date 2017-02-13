# Ansible Role: Git
[![Build Status](https://travis-ci.org/Furdarius/ansible-git.svg?branch=master)](https://travis-ci.org/Furdarius/ansible-git)

Install latest git client from git-core PPA.
Git-core ppa will be added.

## Install

```bash
ansible-galaxy install Furdarius.git
```

## Variables

All variables can be found in [defaults/main.yml](https://github.com/Furdarius/ansible-git/blob/master/defaults/main.yml)

## Playbook example

```yaml
---
- hosts: all
  become: true
  roles:
    - git
```
