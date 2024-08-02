# Ansible Project

This project contains Ansible configurations for managing web servers.

## Inventory

The `inventory` file contains the list of managed nodes.

## Playbooks

The `site.yml` playbook installs and starts Nginx on web servers.

## Usage

To run the playbook, use:

```sh
ansible-playbook -i inventory site.yml
```
