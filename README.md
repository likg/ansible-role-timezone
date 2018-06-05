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
        - timezone_zone: 'UTC'
      roles:
        - { role: lik.timezone }

## License

MIT

## Author Information

This role was created by Lik.
