1. Запустила в контейнере приложение aafire c помощью команды
```
docker run -it aafire
```
![Screenshot_1_lab4](https://github.com/user-attachments/assets/442f88d3-1bc5-45f2-9378-dfd9bff9d1af)

2. Запустила два контейнера с aafire и оставила их в работающем состоянии.

3. Создала сеть с помощью команды
```
docker network create myNetwork
```
![screen2_lab_4](https://github.com/user-attachments/assets/6be203c7-5f6a-4339-aa74-d4c7fd423368)

4. Подключила контейнеры к сети

5. Посмотрела настройти сети
```
docker network inspect myNetwork
```
![screen3_lab_4](https://github.com/user-attachments/assets/7e775a6a-46be-4c70-bcf6-a358973e68f9)

6. Протестировала соединение между контейнерами, используя ```ping```
![screen4_lab_4](https://github.com/user-attachments/assets/c3ac51ba-624b-4e2e-8165-3db3fc059307)
![screen5_lab_5](https://github.com/user-attachments/assets/92fa4b28-c316-4838-9586-aeef9892e471)


