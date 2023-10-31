# containerd

Ansible role to install and configure [containerd](https://containerd.io/).

## Requirements

None.

## Dependencies

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
containerd_version: 1.7.0
```

The version of containerd to install.

```yaml
containerd_url: https://github.com/containerd/containerd/releases/download/v{{ containerd_version }}/containerd-{{ containerd_version }}-linux-{{ containerd_arch }}.tar.gz
```

The URL to download containerd from.

```yaml
containerd_install_dir: /opt/containerd/{{ containerd_version }}
```

The directory to install containerd to.

```yaml
containerd_arch: amd64
```

The architecture of the system to install containerd on.

```yaml
containerd_config_dir: /etc/containerd
```

The directory to store containerd configuration in.

```yaml
containerd_config: ""
```

The containerd configuration to use.

```yaml
containerd_owner: root
containerd_group: root
```

The owner and group of the containerd configuration directory.

```yaml
containerd_binaries:
  - containerd
  - ctr
```

The containerd binaries to install.

## Example Playbook

```yaml
- hosts: all
  roles:
    - role: hostinger.fireactions.containerd
```

## License

MIT
