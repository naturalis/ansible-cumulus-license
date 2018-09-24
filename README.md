# Ansible Role: Cumulus license

Used in [network](https://github.com/naturalis/network/) repo.

Runnable with:
```bash
ansible-playbook playbooks/cumulus_license.yml -i environments/prod
```

This role will setup the license. Initially this is already done by ZTP, but in case of a change (or error) this role can be used on running switches.

## Requirements

None.

## Role Variables

Available variables are listed below.

An example would be:

```bash
cl_license_server: 172.16.200.10
```

## Dependencies

None.

## Example Playbook


    - hosts: switches
      roles:
        - ansible-cumulus-license

## License

Apache2
