# Домашнее задание к занятию «Система мониторинга Zabbix» - `Александра Бужор`
---

### Задание 1 

Установите Zabbix Server с веб-интерфейсом.

#### Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. Установите PostgreSQL. Для установки достаточна та версия что есть в системном репозитороии Debian 11
3. Пользуясь конфигуратором комманд с официального сайта, составьте набор команд для установки последней версии Zabbix с поддержкой PostgreSQL и Apache
4. Выполните все необходимые команды для установки Zabbix Server и Zabbix Web Server

#### Требования к результаты 
1. Прикрепите в файл README.md скриншот авторизации в админке
2. Приложите в файл README.md текст использованных команд в GitHub

#### Ответ:
![image](https://github.com/user-attachments/assets/364ed17a-37d3-4994-a2ff-982fd8920bf3)

1. git add .
2. git commit -m 'make HW task1'
3. git push origin

---

### Задание 2 

Установите Zabbix Agent на два хоста.

#### Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. Установите Zabbix Agent на 2 виртмашины, одной из них может быть ваш Zabbix Server
3. Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов
4. Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera
5. Проверьте что в разделе Latest Data начали появляться данные с добавленных агентов

#### Требования к результаты 
1. Приложите в файл README.md скриншот раздела Configuration > Hosts, где видно, что агенты подключены к серверу
2. Приложите в файл README.md скриншот лога zabbix agent, где видно, что он работает с сервером
3. Приложите в файл README.md скриншот раздела Monitoring > Latest data для обоих хостов, где видны поступающие от агентов данные.
4. Приложите в файл README.md текст использованных команд в GitHub
#### Ответ:
![image](https://github.com/user-attachments/assets/fe48b364-ef03-4fd2-bf72-efd6e5f09f35)
![image](https://github.com/user-attachments/assets/284cbff9-406f-421b-8fb8-ae35d718f738)
![image](https://github.com/user-attachments/assets/a19e22c7-05a5-4345-be2e-c0e3752b7850)

1. git add .
2. git commit -m 'make HW task2'
3. git push origin

---
## Задание 3 со звёздочкой*
Установите Zabbix Agent на Windows (компьютер) и подключите его к серверу Zabbix.

#### Требования к результаты 
1. Приложите в файл README.md скриншот раздела Latest Data, где видно свободное место на диске C:
#### Ответ:
![image](https://github.com/user-attachments/assets/2799501d-4a7f-4948-8960-9ff8226a95a1)

--- 

