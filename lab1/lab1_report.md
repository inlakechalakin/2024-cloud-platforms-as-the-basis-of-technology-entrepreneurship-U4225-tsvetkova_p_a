University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FTMI](https://ftmi.itmo.ru/)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://) ADD link
Year: 2024
Group: U4225
Author: Tsvetkova Polina Andreevna
Lab: Lab1
Date of create: 21.10.2024
Date of finished: 21.10.2024

### Лабораторная 1 Облачные сервисы
#### Цветкова Полина

•	Доступ к Google Cloud получен через гугл-форму.

•	Зашла во вкладку IAM, создала service account со своим именем и с ролью Storage Admin.
![Сервис аккаунт создан ptsvetkova-sa-lab1, назначена роль storage admin.](/lab1/1.png)

 
•	Создала минимальный compute engine (виртуальную машину) с Machine type e2-micro в режиме spot.
![Вирт машина создана с именем ptsvetkova-vm-lab1](/lab1/2.png)
![Вирт машина создана с именем ptsvetkova-vm-lab1](/lab1/3.png)

•	С помощью утилиты gsutils нашла бакет lab1-bucket-itmo и скопировала 3 файла в локальную папку на VM. Используя команду ls -lah отобразила, что эти файлы хранятся у меня на VM.
![Файлы скопированы](/lab1/4.png)
 
•	Поменяла права доступа для моего service account с Storage Admin на Compute Viewer, попробовала повторить пункт с копированием данных, сделала выводы. Доступ пропал с новой ролью.
![Роль изменена. ](/lab1/5.png)
![Роль изменена. ](/lab1/6.png)
![Доступ к копированию из-за роли пропал.](/lab1/7.png)
 
•	Удалила за собой все созданные сервисы, написала отчет с использованием скриншотов. ВМ удалена через delete.
 
