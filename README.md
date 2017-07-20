# ansible-ubuntu
Use [ansible](https://www.ansible.com/) to automatically setup my development environment on Ubuntu (16.04)

# Usage

1. Install `ansible`.

2. Download this repo and `cd` to the directory.

3. Setup the environment on local machine:

Run:

```
ansible-playbook -i "localhost," -c local localhost.yml --ask-sudo-pass
```

Or

set `localhost ansible_connection=local` in `/etc/ansible/hosts`, then run:

```
ansible-playbook localhost.yml --ask-sudo-pass
```
