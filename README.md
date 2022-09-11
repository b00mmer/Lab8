# Лабораторная работа №8
Дополнительная лабораторная работа — настройка основных параметров ASA с помощью интерфейса командной строки 



## Часть 1 Конфигурирование основных настроек устройств
 
1.	Топология

![alt-текст][Топология]

[Топология]:https://github.com/b00mmer/Lab8/blob/main/Topology.JPG "Топология"

2. Таблица адресации

![alt-текст][Таблица]

[Таблица]:https://github.com/b00mmer/Lab8/blob/main/Address_table.JPG "Таблица адресации"

3. [Сетевые параметры маршрутизатора R1](https://github.com/b00mmer/Lab6/blob/main/R1_running-config_4.txt)
4. [Сетевые параметры маршрутизатора S1](https://github.com/b00mmer/Lab6/blob/main/S1_running-config_4.txt)
5. [Сетевые параметры маршрутизатора S2](https://github.com/b00mmer/Lab6/blob/main/S2_running-config_4.txt)


Проверка связи:

Ping с PC-A на R1

![alt-текст][PING_A]

[PING_A]:https://github.com/b00mmer/Lab6/blob/main/Ping_PC_A.JPG "Ping_A"

Ping с PC-B на R1

![alt-текст][PING_B]

[PING_B]:https://github.com/b00mmer/Lab6/blob/main/Ping_PC_A.JPG "Ping_B"

Ping с PC-A на PC-B

![alt-текст][PING_AB]

[PING_AB]:https://github.com/b00mmer/Lab6/blob/main/Ping_PC_A_B.JPG "Ping_AB"




 ## Часть 2 Настройка безопасных магистральных портов

[Файл образа части 2](https://github.com/b00mmer/Lab6/blob/main/Lab6_2.pkt)

[Сетевые параметры маршрутизатора S1](https://github.com/b00mmer/Lab6/blob/main/S1_running-config_p2.txt)
 
 [Сетевые параметры маршрутизатора S2](https://github.com/b00mmer/Lab6/blob/main/S2_running-config_p2.txt)
 
 
  
  ## Часть 3 Защита от STP-атак

[Файл образа части 3](https://github.com/b00mmer/Lab6/blob/main/Lab6_3.pkt)


  ## Часть 4: Настройка безопасности портов и отключение неиспользуемых портов

[Файл образа части 4](https://github.com/b00mmer/Lab6/blob/main/Lab6_4.pkt)

[Сетевые параметры маршрутизатора S1](https://github.com/b00mmer/Lab6/blob/main/S1_running-config_4.txt)
 
 [Сетевые параметры маршрутизатора S2](https://github.com/b00mmer/Lab6/blob/main/S2_running-config_4.txt)
 
Шаг3 Проверка безопасности портов на S1 F0/5


![alt-текст][S43]

[S43]:https://github.com/b00mmer/Lab6/blob/main/St4_3.JPG "S4_3"

Ping PC-A

![alt-текст][S43b]

[S43b]:https://github.com/b00mmer/Lab6/blob/main/St4_3b.JPG "S4_3b"


Статус порта после смены MAC адреса на R1 G 0/0/1

![alt-текст][S43e]

[S43e]:https://github.com/b00mmer/Lab6/blob/main/St4_3e.JPG "S4_3e"
