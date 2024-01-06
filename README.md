[![Tests](https://github.com/escalate/ansible-serverless-monitoring/actions/workflows/tests.yml/badge.svg?branch=master&event=push)](https://github.com/escalate/ansible-serverless-monitoring/actions/workflows/tests.yml)

# Ansible Role: Serverless Monitoring

An Ansible role that setups a serverless monitoring based on Nagios plugins and crond on Raspbian and Debian OS.
This role is compatible with OS version Stretch (9) and Jessie (8).

## Requirements

This role is tested with Ansible version greater equal 2.4.

## Install

```
$ ansible-galaxy install escalate.serverless-monitoring
```

## Role Variables

Please see [defaults/main.yml](https://github.com/escalate/ansible-serverless-monitoring/blob/master/defaults/main.yml) for a complete list of variables that can be overridden.

## Dependencies

None

## Example Playbook

```
- hosts: all
  roles:
    - escalate.serverless-monitoring
```

## License

MIT
