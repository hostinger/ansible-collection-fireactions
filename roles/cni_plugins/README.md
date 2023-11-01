# cni_plugins

Ansible role to install and configure [CNI plugins](https://github.com/containernetworking/plugins).

## Requirements

None.

## Dependencies

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
cni_plugins_version: 1.3.0
```

The version of CNI plugins to install.

```yaml
cni_plugins_url: https://github.com/containernetworking/plugins/releases/download/v{{ cni_plugins_version }}/cni-plugins-linux-{{ cni_plugins_arch }}-v{{ cni_plugins_version }}.tgz
```

The URL to download CNI plugins from.

```yaml
cni_plugins_owner: root
cni_plugins_group: root
```

The owner and group of the CNI plugins binary.

```yaml
cni_plugins_arch: amd64
```

The architecture of the CNI plugins binary.

```yaml
cni_plugins_install_dir: /opt/cni/{{ cni_plugins_version }}
```

The directory to install CNI plugins to.

```yaml
cni_plugins_bin_dir: /opt/cni/bin
```

The directory to install CNI plugins binary to.

```yaml
cni_plugins_binaries:
  - bridge
  - host-local
  - firewall
  - tap
```

The CNI plugins to install.

## Example Playbook

```yaml
- hosts: all
  roles:
    - role: hostinger.fireactions.cni-plugins
```

## License

MIT
