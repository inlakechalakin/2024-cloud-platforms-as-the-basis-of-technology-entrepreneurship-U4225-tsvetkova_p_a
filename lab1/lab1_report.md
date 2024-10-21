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

•	Вам необходимо заполнить гугл форму, приложив свою Gmail почту, чтобы вам выдали доступы к Google Cloud.
Доступ предоставлен 

•	Зайдите в вкладку IAM, создайте service account с ролью Storage Admin.
![Сервис аккаунт создан ptsvetkova-sa-lab1, назначена роль storage admin.](/lab1/1.png)

 
•	Создать минимальный compute engine (виртуальную машину) с Machine type e2-micro в режиме spot.
![Вирт машина создана с именем ptsvetkova-vm-lab1](/lab1/2.png)
![Вирт машина создана с именем ptsvetkova-vm-lab1](/lab1/3.png)

•	С помощью утилиты gsutils найдите бакет lab1-bucket-itmo и скопируйте 3 файла в локальную папку на VM. Используя команду ls -lah отобразите что эти файлы хранятся у вас на VM.
![Файлы скопированы](/lab1/4.png)
 
•	Поменяйте права доступа для вашего service account с Storage Admin на Compute Viewer, попробуйте повторить пункт с копированием данных, сделать выводы.
![Роль изменена. ](/lab1/5.png)
![Роль изменена. ](/lab1/6.png)
![Доступ к копированию из-за роли пропал.](/lab1/7.png)
 
•	Удалите за собой все созданные сервисы, напишите отчет с использованием скриншотов.
ВМ удалена через delete.
 
