# Ansible playbook to automate setting up linux authentication via LDAP

- Developed and used with Ansible 2.8 on Ubuntu 18.04, tested only on Ubuntu.

## Features
- Install and configure LDAP Authentication

## Usage
- Copy directory `samples/ansible-inventory` to the project root
- Edit `hosts` and `host_vars` to your needs
- Create a `playbook-vars.yml` file, using the [sample](samples/playbook-vars.yml) as inspiration
- Deploy: `./run-playbook.sh -e ldap_auth_config_rootbindpw=hackme`

## TODO
- [ ] Create molecule tests

## Changelog
- [2020-06-15] v0.0.1
  - Initial release

## License
MIT
