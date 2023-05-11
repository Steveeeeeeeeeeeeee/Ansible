# Ansible
contains Ansible ad-hoc commands and playbooks 
## ad-hoc Ansible commands
[x] ansible localhost -m file -a "path=/home/optos/ansible state=directory"
[x] ansible localhost -m ping
[x] ansible localhost -m stat -a "path=/home/optos/ansible"
[x] ansible localhost -m copy -a "src=/home/optos/Ansible/README.md dest=/home/optos/Ansible/to-dos.md"s
[x] ansible localhost -m replace -a "path=/home/optos/Ansible/README.md regexp='^\[\s' replace='[x'"
[x] ansible localhost -m debug -a "msg={{lookup('file', '/home/optos/Ansible/README.md') }}"
