# wordpress
1. Создать инфраструктуру с помощью cloud-formation (OC: CentOS)
2. Добавить host, ssh_key в конфигурационный файл /etc/ansible/hosts

[wordpress]

3.139.232.233

[wordpress:vars]

ansible_ssh_user=centos

ansible_ssh_private_key_file=/home/hoangtungkey.pem

4. Установить Jenkins с ansible plugin, указать play-book "wordpressplaybook.yml" и запустить job, после успешного выполнения всех задач, сервер готов к использованию
