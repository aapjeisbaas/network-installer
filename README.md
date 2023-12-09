# Network Installer

An Ansible playbook to setup a network install server.

## usage

### install dependencies

Fetch the requirements from ansible galaxy

```sh
ansible-galaxy install -r requirements.yml
```

### run

```sh
ansible-playbook -i inventory.ini playbook.yml
```
