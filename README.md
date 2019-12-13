# Deployable xsnd

## Requirements

- Install and configure Ansible

## How to run

Ensure to include in `hosts.ini` the corresponding server ip and user.

Example:
```
[server]
xsnd ansible_host=ubuntu@167.71.157.122
```

```sh
git clone git@github.com:JonSalazar/deployable-xsnd.git
cd deployable-xsnd
ansible-playbook -i hosts.ini xsnd.yml
```

