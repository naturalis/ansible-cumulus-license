# Ansible Role: Cumulus license

This role will setup the license. Initially this is already done by ZTP, but in case of a change (or error) this role can be used on running switches.

Naturalis uses this role together with a private inventory.

## Requirements

None.

## Role Variables

Available variables are listed below.

An example would be:

```bash
cl_oob_server: 172.16.200.10
```

## Dependencies

None.

## Example Playbook

    - hosts: switches
      roles:
        - ansible-cumulus-license

## License

Apache2
