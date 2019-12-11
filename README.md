# Deployable xsnd

## Requirements

- Install and configure Ansible
- Download XSN-Core [xsn-core](https://github.com/X9Developers/XSN/releases/download/v1.0.21/xsn-1.0.21-x86_64-linux-gnu.tar.gz) 

## How to run

put `xsn-1.0.21-x86_64-linux-gnu.tar.gz` on root directory

```sh
ansible-playbook -i hosts.ini xsnd.yml
```

