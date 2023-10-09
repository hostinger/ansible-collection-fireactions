# Ansible collection for Fireactions

This is a collection which contains Ansible roles for installing and configuring [Fireactions](https://github.com/hostinger/fireactions) and its dependencies.

## Installation

Before using this collection, install it with `ansible-galaxy`:

```bash
ansible-galaxy collection install hostinger.fireactions
```

You can also include it in a `requirements.yml` file:

```yaml
collections:
- name: hostinger.fireactions
```

and install it with:

```bash
ansible-galaxy collection install -r requirements.yml
```

## Usage

To use a role from this collection, prefix it with `hostinger.fireactions`:

```yaml
- hosts: all
  roles:
    - role: hostinger.fireactions.fireactions
```

## Contributing

Contributions are welcome! For instructions, please refer to the [Contributing](CONTRIBUTING.md) guide.

## License

See [LICENSE](LICENSE).
