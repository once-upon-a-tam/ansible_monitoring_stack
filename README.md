# Ansible monitoring stack

An set of ansible roles and playbooks to deploy, configure and manage a full monitoring suite using systemd services.

## Installation

### Inventory

This repository does not ship with an inventory, you must create your own:

```bash
cp inventory/hosts.example.yaml inventory/hosts.yaml
```

Then edit `inventory/hosts.yaml` with your actual hostnames and connection details.

> Note: you do not need the file to be yaml, you can use INI if you prefer
> For more information, refer to the [official ansible documentation](https://docs.ansible.com/projects/ansible/latest/inventory_guide/intro_inventory.html).
