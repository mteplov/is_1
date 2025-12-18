
# Домашнее задание к занятию «12-07.md Репликация и масштабирование. Часть 2» - Теплов Михаил 

### Инструкция по выполнению домашнего задания

1. Сделайте fork [репозитория c шаблоном решения](https://github.com/netology-code/sys-pattern-homework) к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/gitlab-hw или https://github.com/имя-вашего-репозитория/8-03-hw).
2. Выполните клонирование этого репозитория к себе на ПК с помощью команды `git clone`.
3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
   - впишите вверху название занятия и ваши фамилию и имя;
   - в каждом задании добавьте решение в требуемом виде: текст/код/скриншоты/ссылка;
   - для корректного добавления скриншотов воспользуйтесь инструкцией [«Как вставить скриншот в шаблон с решением»](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md);
   - при оформлении используйте возможности языка разметки md. Коротко об этом можно посмотреть в [инструкции по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md).
4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`).
5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
6. Любые вопросы задавайте в чате учебной группы и/или в разделе «Вопросы по заданию» в личном кабинете.

Желаем успехов в выполнении домашнего задания.

---



### Задание 1

Опишите основные преимущества использования масштабирования методами:

- активный master-сервер и пассивный репликационный slave-сервер; 
- master-сервер и несколько slave-серверов;


*Дайте ответ в свободной форме.*

---

### Задание 2


Разработайте план для выполнения горизонтального и вертикального шаринга базы данных. База данных состоит из трёх таблиц: 

- пользователи, 
- книги, 
- магазины (столбцы произвольно). 

Опишите принципы построения системы и их разграничение или разбивку между базами данных.

*Пришлите блоксхему, где и что будет располагаться. Опишите, в каких режимах будут работать сервера.* 

## Дополнительные задания (со звёздочкой*)
Эти задания дополнительные, то есть не обязательные к выполнению, и никак не повлияют на получение вами зачёта по этому домашнему заданию. Вы можете их выполнить, если хотите глубже шире разобраться в материале.

---
### Задание 3*

Выполните настройку выбранных методов шардинга из задания 2.

*Пришлите конфиг Docker и SQL скрипт с командами для базы данных*.







Скриншоты master1:  
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master1/3.1.png)
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master1/3.2.png)
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master1/3.3.png)
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master1/3.4.png)
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master1/3.5.png)
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master1/3.6.png)
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master1/3.7.png)

Конфигурационный файл master1:  
[Master1](https://github.com/mteplov/SQL1/blob/main/img/z3_master1/mysqld.cnf)

Скриншоты master2:  
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master2/2.1.png)
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master2/2.2.png)
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master2/2.3.png)
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master2/2.4.png)
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master2/2.5.png)
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master2/2.6.png)
![3 задание](https://github.com/mteplov/SQL1/blob/main/img/z3_master2/2.7.png)

Конфигурационный файл master2:  
[Master2](https://github.com/mteplov/SQL1/blob/main/img/z3_master2/mysqld.cnf)


