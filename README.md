# ansible-swap

Configure a swap file on a new Ubuntu host.

#### Quick Start

First, copy the group_vars/swap.yml to a local group_vars/swap.yml file and customize the variables to your needs.

```bash
ansible-playbook site.yml --extra-vars "target=hostname"
```
