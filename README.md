# podman_install

This is an Ansible role that installs Podman an Debian Linux using APT.

## Requirements

- root access on the target host

## Role Variables

To install podman-compose set this variable to `true`.

```yaml
podman_install_compose: false
```

## Dependencies

none

## Example Playbook

```yaml
    - hosts: all
      roles:
         - role: podman
```

## License

MIT

## Author Information

Tamas Molnar - <tmolnar0831@gmail.com> - <https://tomsitcafe.com>
