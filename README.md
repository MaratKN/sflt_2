# Домашнее задание к занятию 2 «Кластеризация и балансировка нагрузки»

### Задание 1
- Запустите два simple python сервера на своей виртуальной машине на разных портах
- Установите и настройте HAProxy, воспользуйтесь материалами к лекции по [ссылке](2/)
- Настройте балансировку Round-robin на 4 уровне.
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

![alt text](https://github.com/MaratKN/sflt_2/blob/main/img1.jpg)
![alt text](https://github.com/MaratKN/sflt_2/blob/main/img2.jpg)
![alt text](https://github.com/MaratKN/sflt_2/blob/main/img3.jpg)
![alt text](https://github.com/MaratKN/sflt_2/blob/main/img4.jpg)


### Задание 2
- Запустите три simple python сервера на своей виртуальной машине на разных портах
- Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
- HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.


![alt text](https://github.com/MaratKN/sflt_2/blob/main/img5.jpg)
![alt text](https://github.com/MaratKN/sflt_2/blob/main/img6.jpg)



