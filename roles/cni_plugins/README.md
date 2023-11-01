# cni_plugins

Ansible role to install and configure [CNI plugins](https://github.com/containernetworking/plugins).

## Requirements

None.

## Dependencies

None.

## Role Variables

Refer to [defaults/main.yml](defaults/main.yml) for a list of variables along with documentation.

## Example Playbook

```yaml
- hosts: all
  roles:
    - role: hostinger.fireactions.cni_plugins
```

## License

MIT
