# fireactions

Ansible role to install and configure [Fireactions](https://github.com/hostinger/fireactions)

## Requirements

- Firecracker
- Containerd
- CNI configuration
- CNI plugins (including tc-redirect-tap)

## Dependencies

None

## Role Variables

Refer to [defaults/main.yml](defaults/main.yml) for a list of variables along with documentation.

## Example Playbook

```yaml
- hosts: all
  roles:
    - role: hostinger.fireactions.fireactions
```

## License

MIT
