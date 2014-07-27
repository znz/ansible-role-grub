# Ansible role for `grub`

Setup grub config.

- `GRUB_RECORDFAIL_TIMEOUT=5` : do not stop when reboot after failed
- default runlevel set 4 to reduce getty

## Requirements

- Debian
- Ubuntu
- grub2

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    ---
    - hosts: all
      sudo: yes
      roles:
      - znzj.grub

License
-------

MIT License
