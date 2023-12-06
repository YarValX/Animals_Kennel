yaroslav@yaroslav-VirtualBox:~$ echo "собаки, кошки, хомяки" > "Домашние животные"

yaroslav@yaroslav-VirtualBox:~$ echo "лошади, верблюды, ослы" > "Вьючные животные"

yaroslav@yaroslav-VirtualBox:~$ cat "Домашние животные" "Вьючные животные" > "Друзья человека"

yaroslav@yaroslav-VirtualBox:~$ cat "Друзья человека"

собаки, кошки, хомяки

лошади, верблюды, ослы

yaroslav@yaroslav-VirtualBox:~$ mkdir Kennel

yaroslav@yaroslav-VirtualBox:~$ cd ~/Kennel

yaroslav@yaroslav-VirtualBox:~$ mv "Друзья человека" ~/Kennel

yaroslav@yaroslav-VirtualBox:~$ sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb

yaroslav@yaroslav-VirtualBox:~$ sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb

yaroslav@yaroslav-VirtualBox:~$ sudo apt-get update

yaroslav@yaroslav-VirtualBox:~$ sudo apt-get install mysql-server

yaroslav@yaroslav-VirtualBox:~$ sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb

yaroslav@yaroslav-VirtualBox:~$ sudo dpkg -i docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb

yaroslav@yaroslav-VirtualBox:~$ sudo dpkg -r docker-ce

(Чтение базы данных … на данный момент установлено 190154 файла и каталога.)

Удаляется docker-ce (5:24.0.6-1~ubuntu.22.04~jammy) …

yaroslav@yaroslav-VirtualBox:~$ sudo dpkg -r docker-ce-cli

(Чтение базы данных … на данный момент установлено 190145 файлов и каталогов.)

Удаляется docker-ce-cli (5:20.10.13~3-0~ubuntu-jammy) …

Обрабатываются триггеры для man-db (2.10.2-1) …

