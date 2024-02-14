## Цель:
Провести когортный анализ.

## Данные:
В качестве данных был взят датасет с информацией о розничных онлайн-транзакциях в период с 12.2010 по 12.2011. 

[Ссылка на датасет](https://www.kaggle.com/datasets/mathchi/online-retail-ii-data-set-from-ml-repository)

- InvoiceNo - уникальный номер транзакции.
- StockCode - код товара.
- Description - наименование продукта.
- Quantity - количество.
- InvoiceDate - дата и время транзакции.
- UnitPrice - цена за штуку.
- CustomerID - ID покупателя.
- Country - страна.

Когортный анализ [здесь](https://github.com/ValeriaGlushkova/Cohort-Analysis-Online-Retail/blob/main/Cohort%20Analysis.ipynb)

## Выводы:

Уже на следующий месяц во всех когортах можно наблюдать резкий спад - в среднем примерно 80% клиентов не возвращается спустя месяц. При этом наилучшие показатели продемонстрировала когорта "2010-12". Через год из этой когорты вернулась половина клиентов, но и в течении года возвращались примерно 35% покупателей.

Также удержание во всех когортах характеризуется колебаниями, что говорит о том, что часть клиентов предпочитает совершать покупки с периодичностью в несколько месяцев.

![cohort](https://github.com/ValeriaGlushkova/Cohort-Analysis-Online-Retail/blob/main/output.png)

