---
- name: "Install yc cli on management host"
    shell:
      cmd: curl https://storage.yandexcloud.net/yandexcloud-yc/install.sh | bash

- name: "Apply env PATH change"
    shell:
      cmd: source "/home/ildargr/.bashrc"


#AgAAAAASYBWcAATuwTX27A1gIUzdjWMNsZ_pMt4
- name: "Get Oauth token by browsing link "
    shell:
      cmd: source "/home/ildargr/.bashrc"

