# ansible-ubuntu
My Ansible configs for Ubuntu (16.04)

# Usage

```
ansible-playbook -i "localhost," -c local localhost.yml --ask-sudo-pass
```

Or

set `localhost ansible_connection=local` in `/etc/ansible/hosts`, then run

```
ansible-playbook localhost.yml --ask-sudo-pass
```
