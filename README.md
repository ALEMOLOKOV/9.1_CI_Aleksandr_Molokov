# 9.1_CI_Aleksandr_Molokov

## Основная часть

Необходимо создать собственные workflow для двух типов задач: bug и остальные типы задач. Задачи типа bug должны проходить жизненный цикл:

1. Open -> On reproduce.
2. On reproduce -> Open, Done reproduce.
3. Done reproduce -> On fix.
4. On fix -> On reproduce, Done fix.
5. Done fix -> On test.
6. On test -> On fix, Done.
7. Done -> Closed, Open.

Остальные задачи должны проходить по упрощённому workflow:

1. Open -> On develop.
2. On develop -> Open, Done develop.
3. Done develop -> On test.
4. On test -> On develop, Done.
5. Done -> Closed, Open.

**Что нужно сделать**

1. Создайте задачу с типом bug, попытайтесь провести его по всему workflow до Done. 
1. Создайте задачу с типом epic, к ней привяжите несколько задач с типом task, проведите их по всему workflow до Done. 
1. При проведении обеих задач по статусам используйте kanban. 
1. Верните задачи в статус Open.
1. Перейдите в Scrum, запланируйте новый спринт, состоящий из задач эпика и одного бага, стартуйте спринт, проведите задачи до состояния Closed. Закройте спринт.
2. Если всё отработалось в рамках ожидания — выгрузите схемы workflow для импорта в XML. Файлы с workflow приложите к решению задания.


## ОТВЕТЫ
Попробовал создать свои workflow

Тип задач Bug

![Type task Bug](https://user-images.githubusercontent.com/109212419/222253553-fb42159c-b891-4166-a75a-7ff656b44f9c.jpg)

Тип задач All

![Type task all](https://user-images.githubusercontent.com/109212419/222253630-2bb4bbb2-78e2-4f0c-b711-120fec5359a7.jpg)

Созадние Kanban доски и задач

![KANBAN](https://user-images.githubusercontent.com/109212419/222253746-7f999516-c681-45a1-b1a1-e49fbc74bb75.jpg)

Создание Scrum доски и спринта

![SCRUM](https://user-images.githubusercontent.com/109212419/222253856-5f59eb70-0081-40eb-978f-1ece08bb8cec.jpg)

![SCRUM CLOSED](https://user-images.githubusercontent.com/109212419/222253932-104d15e6-01eb-4332-a434-ddcc2d144ef1.jpg)

Схемы workflow










