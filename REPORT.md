# Лабораторная работа

## Часть 1

Для того чтобы команда `top` выполнялась каждые 2 минуты, прописываем команду `crontab -e` и в открывшимся файле прописываем 
```
*/2 * * * * top
```
сохраняем изменения и выходим из файла.

<img width="500" src="./images/image1.png"/>

## Часть 2

Выведем на экран список текущих заданий используя команду .

```
crontab -l
```

<img width="500" src="./images/image2.png"/>

## Часть 3
Для того чтобы найти в файле `syslog` две строки о выполнении команды `top` прописываем.
```
cat /var/log/syslog
```

<img width="500" src="./images/image3.png"/>

## Часть 4
Удаляем все задания из планировщика заданий используя команду 

```
crontab -r
```

<img width="500" src="./images/image4.png"/>

<img width="500" src="./images/image5.png"/>

