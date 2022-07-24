### О репозитории:

В данном репозитории я публикую свои проекты по продуктовой аналитике, а именно:проекты по подсчету метрик, сегментации пользователей и на другие темы.


### Projects:
____

- [Метрики и их царство](https://github.com/0n1xx/Product_analysis/blob/main/Product_Metrics/product_metrcis.ipynb):

  Задачи:

  Вы работаете продуктовым аналитиком в компании по доставке продуктов на дом. Сервис доступен как в приложении на ios, так и на android. Вы настроили фронтовую аналитику в AppMetrica, и в конце квартала маркетинг-менеджер попросил вас проанализировать поведение пользователей, а также оценить эффективность каналов их привлечения. Ответьте на следующие вопросы;

  1. MAU февраля;

  2. Количество установок в январе;

  3. Присвойте пользователям когорты по дню установки приложения и посчитайте для них  конверсию из установки в покупку в течение 7 дней. Для какой когорты конверсия была наибольшей? Ответ впишите в формате: дд.мм.гггг;

  4. Укажите значение CR из предыдущего вопроса в % (округлите до 1 цифры после запятой). Формат числа - с точкой;
  5. С какого платного маркетингового канала пришло больше всего новых пользователей?;

  6. Проанализируйте на каком этапе воронки отваливается бОльшая часть клиентов. Посмотрите отдельно сценарии для зарегистрированных и для незарегистрированных пользователей. На каком шаге отваливается больше всего зарегистрированных пользователей?;

  7. Пользователи, пришедшие с каких каналов, показали самую низкую конверсию в первую покупку?;

  8. Пользователи, пришедшие с какого канала, имеют медианный первый чек выше? (учитываются только первые покупки пользователей);

  9. Какой платный канал привлечения имеет самый высокий ROMI?


- [Методы сегментации клиентов и целевой аудитории](https://github.com/0n1xx/Product_analysis/blob/main/RFM_Cohort/rfm_cohort.ipynb):

  Задачи:

  Проведите RFM анализ. В каждом подсегменте поделите пользователей на 4 класса (как на занятии). Отсчитывайте количество дней, прошедших с момента последней покупки, с максимальной даты покупки в датасете. После ответьте на следующие вопросы:

  1. Какое максимальное кол-во покупок было совершено одним пользователем?;

  2. Какая верхняя граница у суммы покупок у пользователей с классом 4 в подсегменте М? (Другими словами: пользователи, у которых сумма покупок от 0 до Х попадают в 4 класс в подсегменте М)?;

  3. Какая нижняя граница у количества покупок у пользователей с классом 1 в подсегменте F?;

  4. Какая верхняя граница у количества покупок у пользователей с классом 2 в подсегменте R?;

  5. Сколько пользователей попало в сегмент 111?;

  6. Сколько пользователей попало в сегмент 311?;

  7. В каком RFM-сегменте самое большое кол-во пользователей?;

  8. В каком RFM-сегменте самое маленькое кол-во пользователей?;

  9. Какое количество пользователей попало в самый малочисленный сегмент?;


- [RFM и когортный анализ](https://github.com/0n1xx/Product_analysis/blob/main/RFM_Cohort/rfm_cohort.ipynb):

  Задачи:

  Продакт-менеджер Василий попросил вас проанализировать совершенные покупки и ответить на следующие вопросы:

  1. Сколько у нас пользователей, которые совершили покупку только один раз?;

  2. Сколько заказов в месяц в среднем не доставляется по разным причинам (вывести детализацию по причинам)?;

  3. По каждому товару определить, в какой день недели товар чаще всего покупается;

  4. Сколько у каждого из пользователей в среднем покупок в неделю (по месяцам)? Не стоит забывать, что внутри месяца может быть не целое количество недель. Например, в ноябре 2021 года 4,28 недели. И внутри метрики это нужно учесть;

  5. Используя pandas, проведи когортный анализ пользователей. В период с января по декабрь выяви когорту с самым высоким retention на 3й месяц;

  6. Часто для качественного анализа аудитории использую подходы, основанные на сегментации. Используя python, построй RFM-сегментацию пользователей, чтобы качественно оценить свою аудиторию. В кластеризации можешь выбрать следующие метрики: R - время от последней покупки пользователя до текущей даты, F - суммарное количество покупок у пользователя за всё время, M - сумма покупок за всё время. Подробно опиши, как ты создавал кластеры. Для каждого RFM-сегмента построй границы метрик recency, frequency и monetary для интерпретации этих кластеров. Пример такого описания: RFM-сегмент 132 (recency=1, frequency=3, monetary=2) имеет границы метрик recency от 130 до 500 дней, frequency от 2 до 5 заказов в неделю, monetary от 1780 до 3560 рублей в неделю. 
