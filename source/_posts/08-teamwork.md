---
title: Методология командной работы
description: Глава 8
date: 2017-02-10 16:03:33
tags:
---

Все системы оптимизации деятельности сфокусированы на сокращении непроизводсвенных издержек. 
Каскадная модель разработки — сначала полный план работы, затем работа. Сложно, неудобно, не учитывает меняющихся требований и здравый смысл. 
Итеративный процесс: разработка → проверка → правка. Повторяются на каждом этапе.

### Манифест гибкой разработки:
* Люди и взаимодействие важнее процессов и инструментов
* Работающий код важнее его красоты и документации
* Сотрудничество с заказчиком важнее контрактных обязательств
* Реакция на изменения важнее следования по плану

Мелкие итерации разработки называются *спринты*. Обычно одна неделя.

### Скрам термины
**backlog** — общий список всех задач и проблем по проекту
**product owner** — обычно менеджер проекта, который всё ведёт и направляет
**scrum master** — руководитель группы разработки, который контролирует выполнение задач по Скрам и проблемы в команде

Скрам основан на идее коллективизма. Если все задачи спринта выполнены — молодцы вся команда. Если нет, то вся команда отстой. Задача скрам мастера поддерживать уровень внутри команды на должном уровне. Избавляться от неэффективных людей.

Каждую неделю спринт бэклог наполняется задачами из общего бэклога. 
Ежедневные встречи команды (дейлики) — разбираем задачи из спринт бэклога и творим.
Если команда сделала все недельные тикеты (выполнение 100%), значит она недогружена, о чём разрабы могут и умолчать. Поэтому приемлимый уровень выполнения задач 95%
Оценка затрат на задачу в часах неверная, так как поощряет бездельничество и является лазейкой затягивания процесса разработки. Поэтому ставим фиксированный объём задач на фиксированный объём времени. 

#### После окончания спринта
**Спринт ревью** — обзор, что было сделано и почему что-то было не сделано.
**Спринт ретроспектива** — разработчики дают фидбэк и свои соображения по продукту.

Скрам-доска для спринта: задачи - в процессе - сделано
Канбан-доска: задачи - план - в процессе - тестирование - деплой - сделано

В канбане столбцы должны быть относящиеся к продукту в целом. Каждая задача проходит по конвейеру (столбцам) и улетает в "сделано". При этом досок может быть сколько угодно и даже вложенные. Каждая доска для своего отдела и так далее.

**Покер планирования**: командная оценка затрат времени на разработку фичи. Каждый разраб приватно сообщает свои сроки на решение задачи и после вскрытия карт объясняет уже всем, почему он так решил. Обычно на этом этапе уже понятно, кто лучше знает проблему и готов за нее взяться.
Трудозатратность каждой задачи оценивают в стори поинтах. Причём удобно использовать числа Фибонначи: 1,5,13,20,40. Чем больше разбег, тем проще оценить. Заодно включается механизм регуляции размера задач. Если задача получает кучу сторипоинтов, то в спринт она не влезает и её разбивают на подзадачи. Вместимость спринта сторипоинтами называется **велосити**.
Одна юзер стори должна выполняться максимум 1 день. Тогда разработчик уйдёт домой с чувством выполненной задачи.

Если вам ещё до старта кажется, что вы не успеете, то вам не кажется.

Когда нет жёстких сроков разработки (например, поддержка и развитие сервиса), то лучше использовать канбан. Если есть дедлайн — скрам.

Самые качественные команды получаются у ленивых продукт-менеджеров. Потому что они не мешают. Но это срабатывает только у увлечённых работников.


## Статьи

* [Agile+UX: как подружить качественный пользовательский интерфейс и гибкие методологии](https://habrahabr.ru/post/159019/)
* [Совместная жизнь Agile и UCD на примере реального проекта](https://habrahabr.ru/post/112554/)
* [Scrum — реальный опыт работы по методологии](https://habrahabr.ru/company/unicloud/blog/167059/)
* [Делаем сплав гибкой разработки и User Experience (UX)](https://habrahabr.ru/post/144760/)
* [Как писать пользовательские истории (User Stories)](http://agilevision.blogspot.com/2013/07/user-stories.html)
* [Как писать хорошие user stories: part 1](http://2tickets2dublin.com/how-to-write-good-user-stories-part-1/)