# ansible-ec2-docker-nginx
Ansible playbook, for create ec2 instance, and launch Nginx Docker container, with Hello World page.
ansible v.2.8.x
Run wit command
$ chmod -v 400 ./ansible.pem && ansible-playbook -i ./hosts --ask-vault-pass playbook.yml
