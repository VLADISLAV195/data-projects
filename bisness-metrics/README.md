# Проект по определению выгодного источника трафика

### Структура данных:
Таблицы с визитами: 
* device - тип устройства с которого заходил пользователь 
* end_ts - дата конеца сессии 
* source_id - номер источника откуда пришел клиент 
* start_ts - дата начала сессии 
* uid - уникальный номер пользователя 
Таблицы с покупками: 
* buy_ts - время покупки * revenue - выручка по пользователю 
* uid - уникальный номер пользователя 
Таблицы с затратами: 
* source_id - номер источника откуда пришел клиент, 
* dt - дата затрат 
* costs - затраты на пользователя 
### Задача:
* изучить как клиенты пользуются сервисом, 
* изучить когда делают первые покупки на сайте, 
* изучить сколько денег приносит компании каждый клиент, 
* изучить когда расходы на привлечение клиента окупаются.
### Вывод:
* Лучшие источники это 1 и 2 по оценке окупаемости и прибыли, с компьютера больше покупали, когорта №6 более доходная, общее снижение наблюдается 1) по длительности сессии 2) по кол-ву пользователей 3) по кол-ву сессий с 12-2017 по 05-2018, 3 источник самый не окупаемый
