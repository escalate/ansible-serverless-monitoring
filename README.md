[![Test](https://github.com/escalate/ansible-serverless-monitoring/actions/workflows/test.yml/badge.svg?branch=master&event=push)](https://github.com/escalate/ansible-serverless-monitoring/actions/workflows/test.yml)

# Ansible Role: Raspberry - Serverless Monitoring

An Ansible role that setups a serverless monitoring based on [Nagios Plugins](https://nagios-plugins.org/) and [cron](https://wiki.debian.org/cron) on Raspberry Pi OS (Debian Bookworm).

## Role Variables

Please see [defaults/main.yml](https://github.com/escalate/ansible-serverless-monitoring/blob/master/defaults/main.yml) for a complete list of variables that can be overridden.

## Dependencies

This role relies on the following dependencies:

- Roles: None
- Collections: None

## Installation

```
$ ansible-galaxy role install escalate.serverless_monitoring
```

## Example Playbook

```
- hosts: all
  roles:
    - role: escalate.serverless_monitoring
      tags: monitoring
```

## License

MIT
