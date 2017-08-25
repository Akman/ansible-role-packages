# Ansible Role: packages

Install packages on Linux.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    packages: []

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - Akman.packages

*Inside `vars/main.yml`*:

    packages:
      - tree
      - build-essential
      - git
      - dnsutils
      - curl

## License

MIT / BSD

## Author Information

This role was created in 2017 by Alexander Kapitman
