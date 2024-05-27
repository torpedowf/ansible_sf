__Для запуска playbook sshkey.yml__
1. Необходимо выполнить команду: ansible-playbook sshkey.yml -vvv --ask-become-pass --ask-vault-pass


__Для запуска playbook postfix.yml__
1. ansible-playbook postfix.yml --tags "init postfix" установит на сервер postfix
2. ansible-playbook postfix.yml --tags "drop postfix" удалит с сервера postfix

