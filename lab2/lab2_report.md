University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FTMI](https://ftmi.itmo.ru/)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://) ADD link
Year: 2024
Group: U4225
Author: Tsvetkova Polina Andreevna
Lab: Lab2
Date of create: 28.10.2024
Date of finished: 28.10.2024

### Лабораторная 2 Облачные сервисы
#### Цветкова Полина

•	Создала Cloud Run из представленного дефолтного сервиса Hello с минимальным количеством ресурсов (128 mib, 1 CPU, port 8080)
![Создание cloud run](/lab2/1.png)

•	Запустила приложение. 
![Запуск](/lab2/2.png)

•	Посмотрела метрики. Например, увидела утилизацию памяти контейнера. И количество запросов. И логи.
![Метрики](/lab2/3.png)
![Метрики](/lab2/4.png)
![Логи](/lab2/5.png)

•	Создала контейнер с портом 8090.
![Контейнер с портом 8090 ](/lab2/6.png)
![Запуск второго контейнера ](/lab2/7.png)

•	Переключала трафик. Настроила трафик 50/50.
![Настройки трафика ](/lab2/8.png)

•	Посмотрела на метрики после изменений. Изменилась утилизация памяти контейнера, например.
![Метрики 2.0 ](/lab2/9.png)

•	Удалила свой Cloud Run.
![Удаление ](/lab2/10.png)

