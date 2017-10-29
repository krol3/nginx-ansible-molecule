# nginx-ansible-molecule
Playbook to install nginx and molecule to test in the Ubuntu distribution

## run playbook
ansible-playbook -i local default.yml --check

## test with molecule (python 2.7)
source activate env2.7

- roles/nginx> molecule test
- roles/swap> molecule test