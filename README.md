Задание 1

Запустите два simple python сервера на своей виртуальной машине на разных портах
Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
Настройте балансировку Round-robin на 4 уровне.
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

![alt text](https://github.com/Skorp712/balance/blob/main/1.png)
![alt text](https://github.com/Skorp712/balance/blob/main/2.png)
![alt text](https://github.com/Skorp712/balance/blob/main/3.png)

Задание 2

Запустите три simple python сервера на своей виртуальной машине на разных портах
Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

![alt text](https://github.com/Skorp712/balance/blob/main/1111.png)
![alt text](https://github.com/Skorp712/balance/blob/main/12.png)
![alt text](https://github.com/Skorp712/balance/blob/main/113.png)
