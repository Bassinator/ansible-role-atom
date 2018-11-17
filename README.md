# Ansible Role: bassitnator.atom

[![Build Status](https://travis-ci.com/Bassinator/ansible-role-atom.svg?branch=master)](https://travis-ci.com/Bassinator/ansible-role-atom)

Install tigerjython into user home directory

## Requirements

java installed
installation_os_user must exist

## Role Variables

None


## Dependencies

None


## Example Playbook

    - hosts: all
      roles:
      - role: bassinator.atom
        installation_os_user: <your_user>

## License

GNU GPLv3

## Author Information
This role was created in 2018 by [Bastian Bukatz](https://bassinator.github.io).
