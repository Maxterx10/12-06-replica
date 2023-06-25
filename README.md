# Домашнее задание к занятию "`12.6. Репликация и масштабирование. Часть 1`" - `Белов Максим`


### Задание 1

Отличия репликации master-master от master-slave заключаются в следующем:  
В первом случае каждая нода является полноценной, т.е. на них можно изменять данные, после чего изменения будут реплицированы. А во втором случае изменения можно производить только на мастере, а слейв является вспомогательной нодой, с которой доступно только чтение. Master-master является менее надежным типом репликации;

---

### Задание 2

Конфиги:  
master  
![alt text](https://github.com/Maxterx10/12-06-replica/blob/main/12-06-2-4.png)  
slave  
![alt text](https://github.com/Maxterx10/12-06-replica/blob/main/12-06-2-5.png)  
Статусы:  
master  
![alt text](https://github.com/Maxterx10/12-06-replica/blob/main/12-06-2-3.png)  
slave  
![alt text](https://github.com/Maxterx10/12-06-replica/blob/main/12-06-2-1.png)  
![alt text](https://github.com/Maxterx10/12-06-replica/blob/main/12-06-2-2.png)  
