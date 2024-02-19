# client

Ansible role to install and configure [Fireactions](https://github.com/hostinger/fireactions) client.

## Requirements

None.

## Dependencies

- hostinger.fireactions.firecracker
- hostinger.common.containerd
- hostinger.common.cni
- hostinger.common.cni_plugins

## Role Variables

Refer to [defaults/main.yml](defaults/main.yml) for a list of variables along with documentation.

## Example Playbook

```yaml
- hosts: all
  roles:
    - role: hostinger.fireactions.client
```

## License

MIT
