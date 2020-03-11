#Развернуть ВМ с характеристиками 2 CPU, 4GB RAM, 30GB HDD,  Centos7 через yc cli в Ansible  (у Яндекс.Облака есть возможность тестового использования).



1. before run playbook, you must install yc-cli, receive Oauth token, run yc init and choose location
https://cloud.yandex.ru/docs/cli/quickstart

2. run playbook 

ansible-playbook -i inventory playbook_create_vm.yml 


3. copy external IP to inventory files of the next playbooks for host yc-instance-1  (will fix later)

4. next playbook
cd ../2_ansible-install-docker-to-vm/  
