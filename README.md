# Ansible Role: Microsoft Azure CLI
[![Build Status](https://travis-ci.org/brentwg/ansible-role-azure-cli.svg?branch=master)](https://travis-ci.org/brentwg/ansible-role-azure-cli)

This role installs the Microsoft Azure CLI for Linux.

## Requirements  

None.  

## Role Variables 
Sane and opinionated defaults have been provided for creating YUM and APT repositories. See `defaults/main.yml` for more information.

## Dependencies

None.  

## Sample Playbook
```
- hosts: all
  
  roles:
    - brentwg.azure-cli
```
