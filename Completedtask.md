Используя команду cat в терминале операционной системы Linux, создать
два файла Домашние животные (заполнив файл собаками, кошками,
хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и
ослы), а затем объединить их. Просмотреть содержимое созданного файла.
Переименовать файл, дав ему новое имя (Друзья человека).
![Снимок экрана от 2024-05-30 21-48-06](https://github.com/LOLkol733/final_test/assets/149338633/5d12970a-f3b6-4fb7-9fb4-fa3a0b4eb97d)

 Создать директорию, переместить файл туда.
 ![Снимок экрана от 2024-05-30 21-55-04](https://github.com/LOLkol733/final_test/assets/149338633/827daaab-f0af-4af0-96ff-00a8b710924d)

Подключить дополнительный репозиторий MySQL. Установить любой пакет
из этого репозитория.
![Снимок экрана от 2024-05-30 22-10-15](https://github.com/LOLkol733/final_test/assets/149338633/ba08f024-112f-4a52-aec8-b9023043d24c)
![Снимок экрана от 2024-05-30 22-09-29](https://github.com/LOLkol733/final_test/assets/149338633/3b49e124-6971-4d26-bb7f-38427049bf47)
![Снимок экрана от 2024-05-30 22-13-33](https://github.com/LOLkol733/final_test/assets/149338633/fddb8121-7cef-40e3-83d0-91469bdd0cac)

Установить и удалить deb-пакет с помощью dpkg.
![Снимок экрана от 2024-05-30 22-31-49](https://github.com/LOLkol733/final_test/assets/149338633/b0f03b1f-a052-4f01-bcee-d3ff0b820341)

Выложить историю команд

mkdir Pitomnik
cd ~/Pitomnik
cat > home_animals
cat > pack_animals
cat home_animals pack_animals > animals
cat animals
mv animals mans_friends
ls -ali


cd ..
mkdir Pitomnik_system
cd ~/Pitomnik
mv mans_friends ~/Pitomnik_system
cd ~/Pitomnik_system
ls -ali


sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb
sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb
sudo apt-get update
sudo apt-get install mysql-server


sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
sudo dpkg -i docker-ce-cli_20.10.133-0ubuntu-jammy_amd64.deb
sudo dpkg -r docker-ce-cli

Нарисовать [диаграмму], в которой есть класс родительский класс, домашние
животные и вьючные животные, в составы которых в случае домашних
животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные
войдут: Лошади, верблюды и ослы).
![Pitomnik](https://github.com/LOLkol733/final_test/assets/149338633/05772684-b718-4b13-a216-561727e12bd4)



