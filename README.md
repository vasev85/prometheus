# Домашнее задание к занятию "9.4. Prometheus"
**

Домашнее задание выполните в Google Docs и отправьте в личном кабинете на проверку ссылку на ваш документ.

Название файла должно содержать номер лекции и фамилию студента. Пример названия: "9.4. Prometheus - Александр Александров"

Перед тем как выслать ссылку, убедитесь, что ее содержимое не является приватным (открыто на просмотр всем, у кого есть ссылка). Если необходимо прикрепить дополнительные ссылки, просто добавьте их в свой Google Docs.

Любые вопросы по решению задач задавайте в чате учебной группы.

---

### Задание 1. 

Установите Prometheus.

*Приведите скриншот systemctl status prometheus, где будет написано prometheus.service - Prometheus Service Netology Lesson 9.4 - [Ваши ФИО]*

![alt text](https://github.com/vasev85/prometheus/blob/main/ex1.png?raw=true) 
---

### Задание 2. 

Установите Node Exporter.

*Приведите скриншот systemctl status node-exporter, где будет написано node-exporter.service - Node Exporter Netology Lesson 9.4 - [Ваши ФИО]*
![alt text](https://github.com/vasev85/prometheus/blob/main/ex2.png?raw=true) 

---

### Задание 3. 

Подключите Node Exporter к серверу Prometheus.

*Приложите скриншот конфига из интерфейса Prometheus вкладки Status > Configuration*
*Приложите скриншот из интерфейса Prometheus вкладки Status > Targets, чтобы было видно минимум два эндпоинта*

![alt text](https://github.com/vasev85/prometheus/blob/main/ex3.png?raw=true)
![alt text](https://github.com/vasev85/prometheus/blob/main/ex3-1.png?raw=true) 
---
## Дополнительные задания (со звездочкой*)

Эти задания дополнительные (не обязательные к выполнению) и никак не повлияют на получение вами зачета по этому домашнему заданию. Вы можете их выполнить, если хотите глубже и/или шире разобраться в материале.

---

### Задание 4*. 

Установите Grafana.

*Приложите скриншот левого нижнего угла интерфейса, чтобы при наведении на иконку пользователя были видны ваши ФИО*
![alt text](https://github.com/vasev85/prometheus/blob/main/ex4.png?raw=true) 
---

### Задание 5*. 

Интегрируйте Grafana и Prometheus.

*Приложите скриншот дашборда (ID:11074) с поступающими туда данными из Node Exporter*
![alt text](https://github.com/vasev85/prometheus/blob/main/ex5.png?raw=true) 
