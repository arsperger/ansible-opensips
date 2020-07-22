### Ansible quick script for Opensips installation on Debian 

required: `apt install gnupg2`

Create inventory in `/etc/ansible/hosts`

Optionally:
- Put an opensips config as a j2 template in `template` dir
- Set opensips additional modules in vars/main.yml

usage: `ansible-playbook opensips.yml`
