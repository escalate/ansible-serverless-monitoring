[![Test](https://github.com/escalate/ansible-serverless-monitoring/actions/workflows/test.yml/badge.svg?branch=master&event=push)](https://github.com/escalate/ansible-serverless-monitoring/actions/workflows/test.yml)

# Ansible Role: Serverless Monitoring

An Ansible role that setups a serverless monitoring based on Nagios plugins and crond on Raspbian and Debian OS.

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
