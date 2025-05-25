# IFMO_DistributedComputing_for_DevOps
Distributed Computing course for DevOps 2025

Все плейбуки запускать с корневой директории
ansible-playbook -i inventory.yml playbook1.yml 
ansible-playbook -i inventory.yml playbook2.yml 
ansible-playbook -i inventory.yml playbook3.yml 
ansible-playbook -i inventory.yml playbook4.yml 

Запуск с определенного таска:
ansible-playbook -i inventory.yml playbook4.yml --start-at-task "Проверить статус galera кластера"