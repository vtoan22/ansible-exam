# ansible-exam
## Basic example to learn Ansible
### Run this commnand:
ansible-playbook -i inventory/hosts main-playbook.yaml --extra-vars "ansible_ssh_user=your_user" --ask-become-pass
