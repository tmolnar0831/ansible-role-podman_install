# podman_install

This is an Ansible role that installs Podman an Debian Linux using APT.

## Requirements

- root access on the target host

## Role Variables

install_podman_compose: false

## Dependencies

none

## Example Playbook

    - hosts: all
      roles:
         - role: podman

## License

MIT

## Author Information

Tamas Molnar - tmolnar0831@gmail.com - https://tomsitcafe.com
