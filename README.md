## Информация о проекте

Необходимо организовать систему учета для питомника, в котором живут домашние и вьючные животные.

## Задание

1. Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные (заполнив файл собаками, кошками, хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного файла. Переименовать файл, дав ему новое имя (Друзья человека).
   
и

2. Создать директорию, переместить файл туда.

![image](https://github.com/NikitaM039/IntervalAttestation/assets/123829781/bde10441-064c-44a4-96a1-ac5c23eb56ca)

3. Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.

![image](https://github.com/NikitaM039/IntervalAttestation/assets/123829781/3056e0b4-84bc-4d84-ac74-4707af071145)

4. Установить и удалить deb-пакет с помощью dpkg.

![image](https://github.com/NikitaM039/IntervalAttestation/assets/123829781/ec613452-5fa9-4d69-a832-b64126d670fa)

5. Выложить историю команд в терминале ubuntu
```
Task 1
mkdir Kennel
cd ~/Kennel
cat > home_animals
cat > pack_animals
cat home_animals pack_animals > animals
cat animals
mv animals mans_friends
ls -ali

Task 2
cd ..
mkdir Kennel_system
cd ~/Kennel
mv mans_friends ~/Kennel_system
cd ~/Kennel_system
ls -ali

Task 3
sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb
sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb
sudo apt-get update
sudo apt-get install mysql-server

Task 4
sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
sudo dpkg -i docker-ce-cli_20.10.133-0ubuntu-jammy_amd64.deb
sudo dpkg -r docker-ce-cli
```

6. Нарисовать диаграмму, в которой есть класс родительский класс, домашние животные и вьючные животные, в составы которых в случае домашних животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные войдут: Лошади, верблюды и ослы).

   



