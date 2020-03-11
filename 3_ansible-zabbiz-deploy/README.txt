#Написать docker-compose файл, который будет содержать zabbix-server с базой данных PostgreSQL и zabbix-agent, 
#задеплоить docker-compose файл на ВМ и добавить агента в zabbix-server с помощью Ansible.


1. run playbook

ansible-playbook -i inventory playbook_deploy_zabbix.yml 
