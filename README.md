# Deployable xsnd

## Requirements

- Install and configure Ansible

## How to run

Ensure to include in `~/.ssh/config` the corresponding server ip and user.

Example:
```
Host xsnd
    HostName 167.71.156.125
    User ubuntu
```

```sh
git clone git@github.com:JonSalazar/deployable-xsnd.git
cd deployable-xsnd
ansible-playbook -i hosts.ini xsnd.yml
```

