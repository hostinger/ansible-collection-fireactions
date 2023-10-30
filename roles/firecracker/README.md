# firecracker

Ansible role to install and configure [Firecracker](https://firecracker-microvm.github.io/)

## Requirements

None.

## Dependencies

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
firecracker_version: 1.4.1
```

The version of Firecracker to install.

```yaml
firecracker_url: https://github.com/firecracker-microvm/firecracker/releases/download/v{{ firecracker_version }}/firecracker-v{{ firecracker_version }}-{{ firecracker_arch }}.tgz
```

The URL to download Firecracker from.

```yaml
firecracker_arch: x86_64
```

The architecture to install Firecracker for. Currently only `x86_64` and `aarch64` are supported.

```yaml
firecracker_symlink_path: /usr/local/bin/firecracker
```

The path to create a symlink to Firecracker binary.

```yaml
firecracker_create_symlink: true
```

Whether to create a symlink to Firecracker binary.

```yaml
firecracker_install_dir: /opt/firecracker/v{{ firecracker_version }}
```

The installation directory for Firecracker.

```yaml
firecracker_owner: root
```

The owner of Firecracker files.

```yaml
firecracker_group: root
```

The group of Firecracker files.

## Example Playbook

```yaml
- hosts: all
  roles:
    - role: hostinger.fireactions.firecracker
```

## License

MIT
