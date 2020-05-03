# ansible-role-baseline

## Requirements
- Ubuntu 18.04 LTS +
- CentOS 7 / RHEL 7 +

## Installation

Define in requirements.yml
```
- src: https://github.com/ig33kmor3/ansible-role-baseline.git
  version: master
  name: baseline
```

Add to project:
```
ansible-galaxy install -r requirements.yml -f
```

## Configuration

Set variables in playbook
```
initialize: False
reboot_host: False
domain_name: none-configured
hosting_environment: bare-metal
```