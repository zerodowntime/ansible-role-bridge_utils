# bridge

Role to install bridge-utils.

## Requirements

- Ansible >= 2.7

### Supported platforms

```yml
- EL
  - 7
```

## Default role variables

| Name | Description | Type | Default | Required |
| -----| ----------- | :--: | :------:| :------: |
| bridge__package_name | Package name to be installed | string | `bridge-utils` | True |
| bridge__package_state | Whether to install the package or not | string | `present` | True |

**All default variables are described in [defaults/main.yml](defaults/main.yml) file.**



## Example Playbook

```yaml
    - hosts: all
      become: true
      roles:
        - role: zerodowntime.bridge
```

## License

[Apache License 2.0](LICENSE)

## Support

ZeroDowntime Team <support@zdt.io>

For more information about the project, please visit https://www.zdt.io/building-blocks/.
