# Nginx Server with Ansible

## Installation

Use this code for connect your inventory to your Vitrual Machine/Server

```bash
ansible web -m ping -i inventory.ini
```

## Playbook config to server

```bash
ansible-playbook -i inventory.ini playbook.yml
```
