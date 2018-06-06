[![Ansible Galaxy](https://img.shields.io/badge/role-likg.timezone-blue.svg?style=flat)](https://galaxy.ansible.com/likg/timezone/)
[![Build Status](https://travis-ci.org/likg/ansible-role-timezone.svg?branch=master)](https://travis-ci.org/likg/ansible-role-timezone)

# Ansible Role: Timezone

Set system timezone with Ansible [timezone](http://docs.ansible.com/ansible/latest/modules/timezone_module.html) module.

## Requirements

No special requirements.

## Role Variables

Available variables/default values can be found in [defaults/main.yml](defaults/main.yml).

## Dependencies

None.

## Example Playbook

    - hosts: servers
      become: yes
      vars:
        - timezone_zone: 'Etc/UTC'
      roles:
        - { role: lik.timezone }

## License

MIT

## Author Information

This role was created by Lik.
