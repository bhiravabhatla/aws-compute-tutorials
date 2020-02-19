# aws-compute-tutorials

## With local Mysql

ansible-playbook -ilocal wordpress.yml

## With RDS
ansible-playbook -ilocal wordpress.yml --skip-tags "mysql"
