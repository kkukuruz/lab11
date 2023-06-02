# lab11

```$ sudo snap install ngrok``` - скачиваю ngrok<br />
```$ ngrok config add-authtoken 2QcT5NCElwjvb9WN5MwNS2xHbVi_6GZ4YdDSRNEJAuL9b7zWW``` - Добавляю свой токен в ngrok.yml<br />
```$ sudo apt-get install openssh-server``` - скачиваю сервер <br />
```$ sudo systemctl start ssh``` - запускаю<br />
```$ sudo systemctl status ssh``` - проверяю<br />

```$ python3 -m http.server``` - распакова модуля http.server<br />
![image](https://github.com/kkukuruz/lab11/assets/116309607/85026eda-5ed5-4c6e-a4e0-90d9716b9285)
```$ nano index.html```
```$ ngrok tcp 22``` - запускаю TCP туннель<br />
![image](https://github.com/kkukuruz/lab11/assets/116309607/d7696056-0c2c-4708-bc9d-fe4bd6009a4f)
ssh 7.tcp.eu.ngrok.io -p 14589  
