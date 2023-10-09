# ansible-role-fireactions

Ansible role to install and configure [Fireactions](https://github.com/hostinger/fireactions).

## Requirements

None.

## Dependencies

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
fireactions_version: 0.1.0
```

The version of Fireactions to install.

```yaml
fireactions_install_dir: /opt/fireactions
```

The installation directory for Fireactions.

```yaml
fireactions_os: linux
```

The OS to install Fireactions for. Currently only `linux` is supported.

```yaml
fireactions_arch: amd64
```

The architecture to install Fireactions for. Currently only `amd64` and `arm64` are supported.

```yaml
fireactions_create_group: true
```

Whether to create a group for Fireactions. Useful if you want to run Fireactions with already existing group.

```yaml
fireactions_group: fireactions
```

The group to create for Fireactions.

```yaml
fireactions_create_owner: true
```

Whether to create a user for Fireactions. Useful if you want to run Fireactions with already existing user.

```yaml
fireactions_owner: fireactions
```

The user to create for Fireactions.

```yaml
fireactions_config_file_path: "{{ fireactions_config_dir }}/config.yml"
```

The path to the Fireactions configuration file.

```yaml
fireactions_config_dir: /etc/fireactions
```

The configuration directory for Fireactions.

```yaml
fireactions_config_server_url: http://127.0.0.1:8080
```

The URL of the Fireactions server.

```yaml
fireactions_config_organisation: example
```

The organisation name for Fireactions. The name must match the organisation name in GitHub.

```yaml
fireactions_group: us-east-1
```

The group name for Fireactions. The group must already exist in Fireactions server.

```yaml
fireactions_cpu_overcommit_ratio: 1.0
```

CPU overcommit ratio is the ratio of CPU to allocate to the client compared to the actual CPU cores available on the host.

```yaml
fireactions_mem_overcommit_ratio: 1.0
```

RAM overcommit ratio is the ratio of RAM to allocate to the client compared to the actual RAM available on the host.

```yaml
fireactions_log_level: info
```

The log level for Fireactions.

## Example Playbook

```yaml
- hosts: all
  roles:
    - { role: hostinger.fireactions }
```

## License

See [LICENSE](LICENSE).
