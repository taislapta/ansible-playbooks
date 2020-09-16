### Ansible rsyslog auto update

`files/99-remote.conf` - modify, add your destination IP or FQDN   
`playbook.yml` - hosts: all <- modify or it will run on all from your invetory file `/etc/ansible/hosts`

run:  
`ansible-playbook -vvv --private-key=~/.ssh/your_rsa_key /path/to/playbook.yml`

